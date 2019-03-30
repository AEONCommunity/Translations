# Mitwirken bei AEON

Als Abspaltung von Monero teilt AEON den größten Teil seiner Codebasis mit Monero und nimmt dabei einige kritische Änderungen vor, um eine einzigartige Alternative zu Monero zu sein. Die Codebasis wird absichtlich in der Nähe von Monero gehalten, um von der höheren Zuverlässigkeit des Codes zu profitieren, die durch die größere Menge an Überprüfungen in Monero gegeben ist.


## Zusammenführen von Upstream-Patches

Das oben genannte Ziel wird durch die kontinuierliche Anstrengung erreicht, vorgelagerte Verbesserungen zusammenzuführen. Jeder, der über ausreichende Kenntnisse verfügt, wird ermutigt, sich an diesen Bemühungen zu beteiligen. Um die Konsistenz der Änderungen zu gewährleisten (was neuen Entwicklern sehr hilft, einfach durch das Commit-Log und die Querverweise zwischen den beiden Repositories zu navigieren) und den ursprünglichen Autor richtig anzugeben, verwenden Sie bitte den Befehl `git cherry-pick`.

Es wird auch dringend empfohlen, die erste Zeile der Commit-Nachricht mit der entsprechenden Pull-Request-Nummer zu korrigieren, damit man leicht auf den ursprünglichen Monero PR verweisen kann. Wenn Sie beispielsweise den vorgelagerten PR 4356, der zwei Commits mit den folgenden Commit-Meldungen hat, zusammenführen möchten:

    Docker android: use common prefix
    Docker android: add libsodium

kann man dies mit den folgenden Befehlen erreichen:

    Docker android: use common prefix /monero#4356
    Docker android: add libsodium /monero#4356

Es ist dabei zu beachten, dass der Postfix in der ersten Zeile jeder Commit-Nachricht hinzugefügt wird. Es wird dabei darum gebeten eine angemessene Anstrengungen zu unternehmen, um die Reihenfolge der Zusammenführungspatches mit dem Original konsistent zu halten, damit mögliche Probleme wie Zusammenführungskonflikte usw. vermieden werden. Dies ist allerdings keine strenge Voraussetzung.


## Änderungsvorschläge

Der oben genannte Prozess wird erleichtert, indem unnötige Unterschiede im Repository vermieden werden. Dies bedeutet, **dass alle Änderungsvorschläge, die auch für Monero gelten, Monero vorgelegt werden sollten**. Insbesondere wird darum gebeten zuerst eine Pull-Anfrage an Monero und dann eine entsprechende PR an AEON durch Cherry-Picking zu senden, wie oben beschrieben. Wenn der Monero PR fusioniert wird, wird der entsprechende AEON PR anschließend auch eingefügt.

Wenn Änderungen vorschlagen werden, die spezifisch für AEON sind und sich von Monero unterscheiden, sollte ein PR nur direkt an AEON geschickt werden. Die Änderungen sollten begründet werden, indem dargelegt wird, wie diese *mehr* oder *einzigartig* auf Aeon anwendbar sind. Mit einer guten Begründung kann die oben beschriebene erhöhte Belastung durch zusätzliche Wartungsarbeit vermieden werden.


# Mitwirken bei Monero

Eine gute Möglichkeit zu helfen, ist das Testen und Melden von Fehlern. Siehe *Wie man Fehler effektiv meldet* [(von Simon Tatham)](https://www.chiark.greenend.org.uk/~sgtatham/bugs.html).
Das Testen ist von unschätzbarem Wert, um die Software solide und nutzbar zu machen.


## Allgemeine Richtlinien

* Kommentare sind erwünscht.
* Wenn Code modifiziert wird, für den ein Doxygen-Header existiert, muss dieser Header angepasst werden.
* Tests sind erwünscht wenn neue Funktionen eingefügt werden.

Patches sind vorzugsweise über eine Github-Pull-Anforderung zu versenden. Wenn das nicht möglich ist, können Patches auch im Format `git format-patch` gesendet werden (z.B. auf fpaste.org mit einem ausreichend langen Timeout und einem Link, der unter #monero-dev auf irc.freenode.net eingetragen wird).

Patches sollten in sich geschlossen sein. Eine gute Faustregel ist, einen Patch pro Problem, Funktion oder logischer Änderung zu haben. Desweiteren sollten Patches keine weiteren Änderungen, wie z.B. zufällige Leerzeichenänderungen oder Neueinrückungen enthalten. Es wird empfohlen, dem Codestil des jeweiligen Codeabschnitts zu folgen, der geändert wird. Richtiges Squashing sollte durchgeführt werden (z.B. wenn zuerst ein fehlerhafter Patch erstellt wird und dann ein zweiter Patch, um den Fehler zu beheben, sollten beide Patches zusammengeführt werden).

Wenn zufällige Änderungen ohne Bezug vorgenommen werden (entweder weil das Editorprogramm lästig ist oder die Änderungen aus anderen Gründen vorgenommen wurden), kann mit `git add -p` ausgewählt werden, welche Änderungen in den kommenden Commit einfließen sollen, indem  alle Änderungen durchlaufen werden und abgefragt wird, ob diese bestimmte Änderung aufgenommen werden soll oder nicht. Dies hilft, saubere Patches ohne irrelevante Änderungen zu erstellen. `git diff` zeigt die Änderungen im aktuellen Baum an. `git diff --cached` zeigt an, was gerade für den Commit vorgesehen ist. Wenn Teile mit `git add -p` hinzugefügt werden, werden diese von der `git diff`-Ausgabe zur `git diff --cached`-Ausgabe hinzugefügt, so dass deutlich wird, wie der Commit aussehen wird.


## Commits und pull requests

Commit-Meldungen sollten sinnvoll sein. Das bedeutet eine Betreffzeile, die den Patch beschreibt, mit einer optionalen längeren Beschreibung der Details, Dokumentation usw..

Wenn eine Pull-Anfrage auf Github gesendet wird, muss sicher gestellt werden, dass diese auf der letzten Version basiert. Bitte keine Merge-Commits oder Streu-Commits von anderen Personen im eingereichten PR. Möglicherweise muss ein Rebase durchgeführt werden, wenn es Konflikte gibt (auch wenn sie einfach zu lösen sind).

Das Signieren von Commits mit PGP wird dringend empfohlen. Das sollte erklären, warum der vorherige Absatz hier steht.

# [Verhaltensregeln (22/C4.1)](http://rfc.zeromq.org/spec:22)

## Lizenz

Copyright (c) 2009-2015 Pieter Hintjens.
Copyright (c) 2017-2018 The Monero Project.

Diese Spezifikation ist freie Software; Sie kann weitergereicht und/oder geändert werden unter den Bedingungen der GNU General Public License, wie diese von der Free Software Foundation veröffentlicht wurde; entweder Version 3 der Lizenz oder jede spätere Version.

Diese Spezifikation wird in der Hoffnung verteilt, dass sie nützlich ist, aber OHNE JEGLICHE GEWÄHRLEISTUNG; auch ohne die stillschweigende Gewährleistung der MARKTREIFE oder TAUGLICHKEIT FÜR EINEN BESTIMMTEN ZWECK. Weitere Informationen finden Sie in der GNU General Public License.

Sie sollten eine Kopie der GNU General Public License zusammen mit diesem Programm erhalten haben; falls nicht, siehe <http://www.gnu.org/licenses>.


## Sprachliche Regelungen

Die Schluesselwoerter "MÜSSEN", "NICHT MÜSSEN", "SOLL", "SOLL NICHT", "SOLLTE", "SOLLTE NICHT", "VORGESCHLAGEN", "KANN" und "OPTIONAL", die in diesem Dokument enthalten sind, sollen wie in RFC 2119 beschrieben verstanden werden.

Die folgenden Benutzer sind in diesem Dokument als das "Monero Betreuer Team" (Monero Maintainer Team) definiert:
* fluffypony
* moneromooo
* hyc


## Ziele

C4 ist gedacht als ein wiederverwendbares optimales Kooperationsmodell für Open-Source-Softwareprojekte. Es hat die folgenden spezifischen Ziele:

* Maximierung der Größe und Vielfalt der Gemeinschaft um ein Projekt herum, indem die Hürden für neue Mitwirkende verringert und ein skaliertes Beteiligungsmodell mit starken positiven Rückmeldungen geschaffen wird;
* Veringerung von der Abhängigkeit von Schlüsselpersonen durch die Trennung verschiedener Fähigkeiten, so dass ein größerer Kompetenzpool in jedem erforderlichen Bereich vorhanden ist;
* Indem die Vielfalt des Entscheidungsprozesses erhöht wird, soll sich das Projekt schneller und zielgerichteter entwickeln;
* Unterstützung des natürlichen Lebenszyklus von Projektversionen von *experimentell* bis *stabil*, indem sichere Experimente, schnelles Scheitern und die Identifikation von stabilem Code ermöglicht werden;
* Reduzierung der internen Komplexität von Projekten, wodurch die Teilnahme für alle Mitwirkenden erleichtert und der Fehlerumfang reduziert wird;
* Durchsetzung des kollektiven Eigentums am Projekt, was den wirtschaftlichen Anreiz für die Mitwirkenden erhöht und das Risiko von Übernahmen durch feindliche Unternehmen verringert.


## Design

### Vorwort

* Das Projekt SOLL das git Versionskontrollsystem verwenden.
* Das Projekt SOLL auf github.com (oder Ähnlichem) gehostet werden, im nachfolgenden wird dies als Plattform bezeichnet.
* Das Projekt SOLL die Problemverfolgung der Plattform verwenden.
    * Beispiel an Hand einer Anderen Plattform (nicht github)
        - Die *Plattform* könnte ein grundlegendes git mit Trac sein, welches im gleichen Netzwerk gehostet wird.
        - Die Problemnachverfolgung wäre in diesem Fall Trac.
* Das Projekt SOLLTE klar dokumentierte Richtlinien für den verwendeten Code-Stil haben.
* Ein "Mitwirkender" ist eine Person, welche Patches bereitstellen möchte. Ein Patch bezeichnet einen Commit, der ein klar identifiziertes Problem löst.
* Ein "Betreuer" ist eine Person, die Patches mit dem Projekt zusammen führt. Betreuer sind keine Entwickler; Ihre Aufgabe ist es den Prozess zu leiten.
* Mitwirkende SOLLTEN NICHT Zugang zum Projekt haben um Commits zusammenzuführen. Es sei denn, sie sind auch Betreuer.
* Betreuer SOLLTEN Zugang zum Projekt haben um Commits zusammenzuführen.
* Jeder, ohne Unterscheidung oder Diskriminierung, SOLLTE das gleiche Recht haben eine Mitwirkender nach den zuvor angesprochenen Verhaltensregeln zu werden.

### Lizensierung und Eigentum

- Das Projekt SOLL eine Share-A-like-Lizenz verwenden, wie beispielsweise BSD-3, die GPLv3 oder eine Variante davon (LGPL, AGPL) oder die MPLv2.
- Alle Beiträge zum Projekt-Quellcode ("Patches") SOLLEN die gleiche Lizenz wie das Projekt verwenden.
- Alle Patches sind Eigentum ihrer Autoren. Es SOLL KEIN Prozess der Urheberrechtsübertragung stattfinden.
- Die Urheberrechte an dem Projekt SOLLTEN kollektiv von allen seinen Mitwirkenden gehalten werden.
- Jeder Mitwirkende SOLL dafür verantwortlich sein, sich in der Projektmitarbeiterliste zu identifizieren.


### Patch-Anforderungen

- Die Betreuer MÜSSEN über ein Plattform-Konto verfügen und SOLLTEN ihren echten Namen oder einen bekannten Alias verwenden.
- Die Mitwirkenden SOLLEN ein Plattform-Konto haben und KÖNNEN ihren echten Namen oder einen bekannten Alias verwenden.
- Ein Patch sollte eine minimale und genaue Antwort auf ein identifiziertes und vereinbartes Problem sein.
- Ein Patch MUSS sich an die Codestilrichtlinien des Projekts halten, wenn diese definiert sind.
- Ein Patch MUSS sich an die unten definierten Richtlinien "Entwicklung öffentlicher Aufträge" halten.
- Ein Patch darf keinen nicht-trivialen Code aus anderen Projekten enthalten, es sei denn, der Mitwirkende ist der ursprüngliche Autor dieses Codes.
- Ein Patch MUSS sauber kompiliert werden und die Projektselbsttests mindestens auf der Hauptzielplattform bestehen.
- Eine Patch-Commit-Nachricht SOLLTE aus einer einzigen kurzen (weniger als 50 Zeichen langen) Zeile bestehen, in der die Änderung zusammengefasst ist, optional gefolgt von einer Leerzeile und einer ausführlicheren Beschreibung.
- Ein "Korrekter Patch" ist einer, der die oben genannten Anforderungen erfüllt.


### Entwicklungsprozess

- Änderungen am Projekt SOLLEN nach dem Muster der genauen Identifizierung von Problemen und der Anwendung minimaler, genauer Lösungen für diese Probleme geregelt werden.
- Um Änderungen anzufordern, SOLLTE ein Benutzer ein Problem in der Problemnachverfolgung der Platform protokollieren.
- Der Benutzer oder Mitwirkende SOLLTE in der Problemnachverfolgung das Problem beschreiben, mit dem er konfrontiert ist oder das er festgestellt hat.
- Der Benutzer oder Mitwirkende SOLLTE einen Konsens über die Genauigkeit seiner Beobachtung suchen und den Wert der Problemlösung darstellen.
- Benutzer SOLLEN KEINE Feature-Anfragen, Ideen oder Vorschläge protokollieren, die nichts mit dem Monero-Code oder dem Monero-Abhängigkeitscode oder dem potenziellen/künftigen Monero-Abhängigkeitscode oder der Forschung, die Monero erfolgreich implementiert, zu tun haben.
- Benutzer SOLLEN KEINE Lösungen für Probleme (überprüfbar oder hypothetisch) protokollieren, die nicht explizit dokumentiert und/oder nicht beweisbar sind und/oder nicht vernünftig nachgewiesen werden können.
- Ddie Release-Historie des Projekts SOLL eine Liste von Problemen sein, die protokolliert und gelöst wurden.
- Um an einem Problem zu arbeiten, SOLL ein Mitwirkender das Projekt-Repository teilen und dann an seinem abgespaltenen Repository arbeiten.
- Um einen Patch einzureichen, SOLL ein Mitwirkender eine Plattform-Pull-Anfrage zurück zum Projekt erstellen.
- Ein Mitwirkender SOLL KEINE Änderungen direkt in das Projekt übernehmen.
- Um einen Patch zu diskutieren, dürfen Leute die Platform Pull-Anfrage, den Commit oder anderswo kommentieren.
- Um einen Patch anzunehmen oder abzulehnen, SOLL ein Betreuer die Plattform-Schnittstelle verwenden.
- Betreuer SOLLEN ihre eigenen Patches NICHT zusammenführen, außer in Ausnahmefällen, wie z.B. Nicht-Verügbarkeit von anderen Betreuern für einen längeren Zeitraum (mehr als 30 Tage) oder wenn die Patches nicht dringend sind, wie vom Monero Maintainers Team definiert.
- Betreuer sollten KEINE Werturteile über korrekte Patches abgeben, es sei denn, der Betreuer (wie es in seltenen Fällen der Fall sein kann) ist ein Kern-Entwickler.
- Betreuer DÜRFEN Pull-Anfragen in NICHT weniger als 168 Stunden (1 Woche) zusammenführen, es sei denn, sie werden von mindestens 2 Personen des Monero Maintainer Teams als dringend erachtet.
- Der Mitwirkende KANN ein Problem als "Bereit" kennzeichnen, nachdem er eine Pull-Anfrage für das Problem gestellt hat.
- Der Benutzer, der ein Problem erstellt hat, SOLLTE das Problem schließen, nachdem er den Patch erfolgreich überprüft hat.
- Betreuer SOLLTEN um Verbesserungen an fehlerhaften Patches bitten und fehlerhafte Patches ablehnen, wenn der Mitwirkende nicht konstruktiv reagiert.
- Jeder Mitwirkende, der Werturteile über einen korrekten Patch hat, SOLLTE diese über seine eigenen Patches ausdrücken.
- Betreuer KÖNNEN Änderungen an der Nicht-Quelldokumentation direkt in das Projekt übertragen.


### Herstellung von stabilen Versionen

- Das Projekt SOLLTE einen Zweig ("Master") haben, der immer die neueste in Bearbeitung befindliche Version enthält. Diese Version SOLL hergestellt werden.
- Das Projekt SOLL aus KEINEM Grund Themenzweige verwenden. Persönliche Abspaltungen dürfen Themenzweige verwenden.
- Um eine stabiles Version zu erstellen, SOLL jemand das Projekt durch Kopieren abspalten und so Betreuer dieses neuen Zweigs werden.
- Das Abspalten eines Projekts zur Stabilisierung KANN einseitig und ohne Zustimmung der Projektbetreuer erfolgen.
- Ein Patch für ein als "stabil" erklärtes Projekt sollte von einem reproduzierbaren Testfall begleitet werden.

### Entwicklung öffentlicher Aufträge

- Alle öffentlichen Aufträge (APIs oder Protokolle) SOLLEN dokumentiert werden.
- Alle öffentlichen Aufträge SOLLTEN Raum für Erweiterbarkeit und Experimente bieten.
- Ein Patch, der einen stabilen öffentlichen Auftrag ändert, sollte bestehende Anwendungen nicht brechen, es sei denn, es besteht ein überwiegender Konsens über den Wert dieser Maßnahme.
- Ein Patch, der neue Funktionen in einen öffentlichen Auftrag einführt, sollte dies unter Verwendung neuer Namen tun.
- Alte Namen SOLLTEN systematisch abgeschafft werden, indem neue Namen als "experimentell" markiert werden, bis sie stabil sind, und dann die alten Namen als *veraltet* markiert werden.
- Wenn genügend Zeit vergangen ist, SOLLTEN veraltete Namen als "Legacy" markiert und schließlich entfernt werden.
- Alte Namen SOLLEN NICHT von neuen Funktionen wiederverwendet werden.
- Wenn alte Namen entfernt werden, MÜSSEN ihre Implementierungen eine Ausnahme (Assertion) hervorrufen, wenn sie von Anwendungen verwendet werden.

### Projektadministration

- Die Projektgründer SOLLEN als Administratoren fungieren, um die Betreuer zu verwalten.
- Die Administratoren MÜSSEN ihre eigene Nachfolge im Laufe der Zeit sicherstellen, indem sie die effektivsten Betreuer befördern.
- Ein neuer Mitwirkender, der einen korrekten Patch erstellt, SOLL eingeladen werden, Betreuer zu werden.
- Administratoren KÖNNEN Maintainer entfernen, die über einen längeren Zeitraum inaktiv sind oder diese Regeln wiederholt nicht korrekt anwenden.
- Administratoren SOLLTEN *schlechte Akteure*, die anderen im Projekt Stress und Schmerzen bereiten, blockieren oder aussperren. Dies SOLLTE nach einer öffentlichen Diskussion geschehen, mit der Möglichkeit, dass alle Parteien dazu Stellung nehmen. Ein schlechter Akteur ist jemand, der die Regeln und die Kultur des Projekts immer wieder ignoriert, der unnötig argumentiert oder feindselig ist. Ausserdem jemand, der beleidigend ist, und der nicht in der Lage ist, sein Verhalten selbst zu korrigieren, wenn er von anderen dazu aufgefordert wird.
