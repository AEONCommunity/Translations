# Contribuyendo a Aeon

Siendo un fork de Monero, Aeon comparte la mayor parte de su base de código con Monero mientras hace algunas modificaciones críticas para
que puede ofrecer una alternativa única a Monero. El código se mantiene intencionalmente cerca de Monero para
aproveche la mayor confiabilidad del código debido a la mayor fuente de revisión por pares disponible en Monero.

## Merging upstream patches

El objetivo anterior se logra a través del esfuerzo continuo de fusionar los mejores adelantamientos del código de Monero. Cualquiera con suficiente
conocimiento se alienta a contribuir a este esfuerzo. Con el fin de garantizar la coherencia de los cambios (que en gran medida
ayuda a los nuevos desarrolladores a navegar fácilmente a través del registro de confirmación y la referencia cruzada entre los dos repositorios) también
para acreditar correctamente al autor original, utilice el comando: `git cherry-pick`

También se recomienda 'postfix' la primera línea del mensaje de confirmación con el correspondiente número de solicitud de extracción (PR).
para que pueda hacer referencia fácilmente al original PR de Monero. Por ejemplo, si va a combinar el PR 4356 
que tiene dos confirmaciones con los siguientes mensajes de confirmación:

    Docker android: use common prefix
    Docker android: add libsodium

A continuación, realice los mensajes de confirmación correspondientes de la siguiente manera:

    Docker android: use common prefix /monero#4356
    Docker android: add libsodium /monero#4356

Tenga en cuenta que el postfix se agrega a la primera línea de cada mensaje de confirmación. También, por favor, hacer un esfuerzo razonable para que
mantenga el orden de los parches combinados de manera consistente con el original para que los problemas potenciales como conflictos de fusión, etc.
se evitan, aunque este no es un requisito estricto.

## Proponiendo cambios

El esfuerzo anterior se facilita al evitar la creación de diferencias innecesarias en el repositorio. Esto implica que
**cualquier cambio propuesto que también se aplique a Monero lo deben someter al código de Monero.** Específicamente, por favor envíe un 'PR'
a Monero primero, luego envíe un PR correspondiente a Aeon por 'cherry picking', como se describe anteriormente. Si tu Monero PR
se fusiona, su correspondiente Aeon PR se fusionará posteriormente. 

Si va a proponer algunos cambios que son específicos de Aeon y distintos de Monero, envíe un 'PR' directamente
a Aeon y justifica tus cambios exponiendo cómo son *más* o *únicamente* aplicables a Aeon. Con buen
justificación se puede superar la carga de un aumento en el costo de mantenimiento.


# Contribuyendo a Monero

Una buena manera de ayudar es probando e informando errores. Vea
[How to Report Bugs Effectively (by Simon Tatham)](https://www.chiark.greenend.org.uk/~sgtatham/bugs.html)
si quieres ayudar de esa manera. La prueba de codigo es invaluable para hacer una pieza.
de software sólido y utilizable.


## Reglas generales

* Se anima a los comentarios.
* Si se modifica el código para el cual existen encabezados de Doxygen, ese encabezado debe modificarse para que coincida.
* Sería bueno tener pruebas si estás agregando funcionalidad.

Parches se envían preferiblemente a través de un PR en Github. Si eso
no se puede hacer, se pueden enviar parches en formato "git format-patch"
(por ejemplo, publicado en fpaste.org con un vencimiento lo suficientemente largo y un enlace
publicado en # monero-dev en irc.freenode.net).

Parches deben ser autocontenidos. Una buena regla de oro es tener
Un parche por problema, característica o cambio lógico por separado. También no
otros cambios, como cambios de espacios en blanco aleatorios o reindentación.
Se recomienda siguiendo el estilo de código del fragmento particular de código que estás modificando.
Se debe realizar un aplastamiento adecuado (squashing) (por ejemplo, si
estás haciendo un parche cual es 'buggy', luego un parche posterior para corregir el error,
ambos parches deben ser fusionados).

Si ha realizado cambios aleatorios no relacionados (ya sea porque su editor
es molesto o los hiciste por otras razones), puedes seleccionar
cuales cambios entran en el próximo compromiso usando 'git add -p', cual
te guíara a través de todos los cambios y pregunta si debes o no
incluir este cambio particular. Esto ayuda a crear parches limpios.
sin ningún cambio irrelevante. 'git diff' te mostrará los cambios
en tu repositorio. 'git diff --cached' mostrará lo que está en escena actualmente
para commit. A medida que agregues hunks con 'git add -p', esos hunks se
"moverán" de la salida de 'git diff' a la salida de 'git diff --cached',
para que pueda ver claramente cómo se verá su commit.

## Commits y solicitud de extracción (Pull Requests 'PR')

Commit mensajes deben ser sensatos. Eso significa una línea de asunto que
describe el parche, con un cuerpo más largo opcional que da detalles,
documentación, etc.

Al enviar una solicitud de extracción (PR) en Github, asegúrese de que su código esté
rebasado. Por favor no 'merge commmits' ni se desvía con 'commits' de otras personas en
su código enviada. Se le puede pedir que rebase si hay
conflictos o errores.

Se recomienda encarecidamente la firma de PGP. Eso debería explicar por qué
El párrafo anterior está aquí.

# [Code of Conduct (22/C4.1)](http://rfc.zeromq.org/spec:22)

## Licencia

Copyright (c) 2009-2015 Pieter Hintjens.
Copyright (c) 2017-2019 The Monero Project.

Esta especificación es software libre; puede redistribuirlo y / o modificarlo según los términos de la Licencia Pública General de GNU publicada por la Free Software Foundation; ya sea la versión 3 de la Licencia, o (a su elección) cualquier versión posterior.

Esta Especificación se distribuye con la esperanza de que sea útil, pero SIN NINGUNA GARANTÍA; sin ni siquiera la garantía implícita de COMERCIABILIDAD o APTITUD PARA UN PROPÓSITO PARTICULAR. Vea la Licencia Pública General de GNU para más detalles.

Debería haber recibido una copia de la Licencia Pública General de GNU junto con este programa; si no, vea <http://www.gnu.org/licenses>.

## Language

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in RFC 2119.

El "Equipo de mantenimiento de Monero" se define en este documento como los siguientes usuarios:
- fluffypony
- moneromooo
- hyc

## Metas

CC4 es proporcionar un modelo de colaboración óptimo reutilizable para proyectos de software de código abierto. Tiene estos objetivos específicos:

- Para maximizar la escala y la diversidad de la comunidad en torno a un proyecto, reduciendo la fricción para los nuevos contribuyentes y creando un modelo de participación escalado con una fuerte retroalimentación positiva;
- Para aliviar las dependencias de individuos clave al separar diferentes conjuntos de habilidades para que haya un grupo más grande de competencias en cualquier dominio requerido;
- Para permitir que el proyecto se desarrolle más rápido y con mayor precisión, al aumentar la diversidad del proceso de toma de decisiones;
- Para respaldar el ciclo de vida natural de las versiones de proyectos, desde experimentales hasta estables, permitiendo una experimentación segura, fallas rápidas y aislamiento del código estable;
- Para reducir la complejidad interna de los repositorios de proyectos, facilitando así la participación de los Colaboradores y reduciendo el margen de error;
- Para imponer la propiedad colectiva del proyecto, lo que aumenta el incentivo económico para los contribuyentes y reduce el riesgo de secuestro por parte de entidades hostiles.

## Diseño

### Preliminares

- El proyecto DEBE usar el sistema de control de revisión distribuido 'git'.
- El proyecto DEBE ser alojado en github.com o equivalente, aquí denominado "Plataforma".
- El proyecto DEBE usar el rastreador de problemas de la plataforma.
  - Ejemplo no GitHub:
    - "Plataforma" podría ser un repositorio de git de vainilla y Trac alojado en la misma máquina / red.
    - El rastreador de problemas de la plataforma sería Trac.
- El proyecto DEBE tener directrices claramente documentadas para el estilo del código.
- Un "colaborador" es una persona que desea proporcionar un parche, ya que es un conjunto de confirmaciones que resuelven algún problema claramente identificado.
- Un "Mantenedor" es una persona que fusiona parches al proyecto. Los mantenedores no son desarrolladores; Su trabajo es hacer cumplir el proceso.
- Contribuyentes NO DEBEN tener acceso comprometido al repositorio a menos que también sean Mantenedores.
- Mantenedores DEBERÁN tener acceso comprometido al repositorio.
- Todas las personas, sin distinción ni discriminación, DEBEN tener el mismo derecho de convertirse en Contribuyentes según los términos de este contrato.

### Licencia y propiedad

- El proyecto DEBERÁ utilizar una licencia de acciones similares, como BSD-3, la GPLv3 o una variante de la misma (LGPL, AGPL) o la MPLv2.
- Todas las contribuciones al código del proyecto ("parches") DEBEN utilizar la misma licencia que el proyecto.
- Todos los parches son propiedad de sus autores. NO DEBE haber ningún proceso de asignación de derechos de autor.
- Los derechos de autor en el proyecto DEBEN ser propiedad colectiva de todos sus Contribuyentes.
- Cada Colaborador DEBERÁ ser responsable de identificarse en la lista de Colaboradores del proyecto.

### Requisitos de Parches

- Mantenedores DEBEN tener una cuenta de plataforma y DEBERÍAN utilizar sus nombres reales o un alias conocido.
- Contribuyentes DEBEN tener una cuenta de la plataforma y PUEDEN usar sus nombres reales o un alias conocido.
- Un parche DEBE ser una respuesta mínima y precisa para exactamente un problema identificado y acordado.
- Un parche DEBE adherirse a las pautas de estilo del código del proyecto si están definidas.
- Un parche DEBE cumplir con las pautas de "Evolución de los contratos públicos" definidas a continuación.
- Un parche NO DEBE incluir código no trivial de otros proyectos a menos que el Colaborador sea el autor original de ese código.
- Un parche DEBE compilar limpiamente y pasar las autopruebas del proyecto al menos en la plataforma objetivo principal.
- Un mensaje de confirmación de parche DEBE consistir en una sola línea corta (menos de 50 caracteres) que resuma el cambio, opcionalmente seguida de una línea en blanco y luego una descripción más completa.
- Un "parche correcto" es uno que cumple con los requisitos anteriores.

### Proceso de Desarrollo

- Cambio en el proyecto DEBE regirse por el patrón de identificación precisa de problemas y la aplicación de soluciones mínimas y precisas a estos problemas.
- Para solicitar cambios, un usuario DEBE registrar un problema en el rastreador de problemas de la plataforma del proyecto.
- El usuario o el colaborador DEBERÍAN escribir el problema describiendo el problema que enfrentan o observan.
- El usuario o el Colaborador DEBERÍA buscar el consenso sobre la exactitud de su observación y el valor de resolver el problema.
- Usuarios NO DEBEN registrar solicitudes de características, ideas o sugerencias no relacionadas con el código de Monero o el código de dependencia de Monero o el código de dependencia potencial / futuro de Monero o la investigación que implemente con éxito Monero.
- Usuarios NO DEBEN registrar ninguna solución a los problemas (verificables o hipotéticos) de los cuales no están explícitamente documentados y / o no son demostrables y / o no pueden ser probados razonablemente.
- Por lo tanto, el historial de lanzamiento del proyecto DEBE ser una lista de los problemas significativos registrados y resueltos.
- Para trabajar en un problema, un Colaborador DEBE 'fork' el repositorio del proyecto y luego trabajar en su fork del repositorio.
- Para enviar un parche, un colaborador DEBE crear un 'PR' en la plataforma para el proyecto.
- Un colaborador NO DEBE enviar cambios directamente al proyecto.
- Para discutir un parche, la gente PUEDE comentar sobre el 'PR' en la Plataforma, sobre el 'commit' o en otro lugar.
- Para aceptar o rechazar un parche, un Mantenedor DEBERÁ usar la interfaz de la plataforma.
- Mantenedores NO DEBEN fusionar sus propios parches, excepto en casos excepcionales, como la falta de respuesta de otros Mantenedores durante un período prolongado (más de 30 días) o a menos que sea urgente según lo define el Equipo de Mantenedores de Monero.
- Mantenedores NO DEBEN hacer juicios de valor en los parches correctos a menos que el Mantenedor (como puede suceder en circunstancias excepcionales) sea un desarrollador de código central.
- Mantenedores NO DEBEN fusionar las solicitudes de extracción en menos de 168 horas (1 semana) a menos que lo consideren urgentes al menos 2 personas del Equipo de mantenimiento de Monero.
- El Contribuidor PUEDE etiquetar un problema como "Ready" después de realizar un 'PR' para el problema.
- El usuario que creó un problema DEBE cerrar el problema después de verificar que el parche sea exitoso.
- Mantenedores DEBEN pedir mejoras a los parches incorrectos y DEBEN rechazar los parches incorrectos si el Contribuidor no responde de manera constructiva.
- Cualquier Colaborador que tenga juicios de valor en un parche correcto DEBE expresarlo a través de sus propios parches.
- Mantenedores PUEDEN enviar cambios a documentación que sean 'non-source' directamente en el proyecto.

### Creando lanzamientos estables

- El proyecto DEBE tener una rama ("master") que siempre contiene la última versión en progreso y DEBE construir siempre.
- El proyecto NO DEBE utilizar ramas temáticas por ningún motivo. Los 'forks' personales PUEDEN utilizar ramas temáticas.
- Para hacer un lanzamiento estable, alguien DEBE 'fork' el repositorio copiándolo y, por lo tanto, se convierte en mantenedor de este repositorio.
- Forking a project for stabilization MAY be done unilaterally and without agreement of project maintainers.
- Un parche para un proyecto de estabilización declarado "stable" DEBE ir acompañado de un caso de prueba reproducible.

### Evolución de los contratos públicos

- Todos los contratos públicos (API o protocolos) DEBEN documentarse.
- Todos los contratos públicos DEBEN tener espacio para la extensibilidad y la experimentación.
- Un parche que modifica un Contrato público estable NO DEBE romper las aplicaciones existentes a menos que exista un consenso primordial sobre el valor de hacer esto.
- Un parche que introduce nuevas características a un Contrato Público DEBE hacerlo usando nombres nuevos.
- Los nombres antiguos DEBEN estar en desuso de manera sistemática al marcar los nuevos nombres como "experimental" hasta que estén estables, y luego marcar los nombres antiguos como "deprecated".
- Cuando haya transcurrido el tiempo suficiente, los nombres antiguos desaprobados DEBEN marcarse como "legacy" y, finalmente, eliminarse.
- Los nombres antiguos NO DEBEN ser reutilizados por nuevas características.
- Cuando se eliminan los nombres antiguos, sus implementaciones DEBEN provocar una excepción (aserción) si las utilizan las aplicaciones.

### Administración de proyecto

- Los fundadores del proyecto DEBERÁN actuar como administradores para administrar el conjunto de mantenedores del proyecto.
- Los Administradores DEBERÁN asegurar su propia sucesión en el tiempo mediante la promoción de los Mantenedores más efectivos.
- Un nuevo colaborador que haga un parche correcto DEBE ser invitado a convertirse en mantenedor.
- Administradores PUEDEN eliminar a los Mantenedores que están inactivos por un período prolongado de tiempo o que repetidamente no aplican este proceso con precisión.
- Administradores DEBEN bloquear o prohibir a los "bad actors" que causan estrés y dolor a otros en el proyecto. Esto debe hacerse después de una discusión pública, con la posibilidad de que todas las partes hablen. Un mal actor es alguien que ignora repetidamente las reglas y la cultura del proyecto, que es innecesariamente argumentativo y hostil, o que es ofensivo, y que no puede autocorregir su conducta cuando otros lo piden.