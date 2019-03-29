# Przyczynianie się do Aeon

Będąc forkiem Monero, Aeon dzieli większość kodu źródłowego z Monero, dokonując przy tym kilku krytycznych modyfikacji
że może zaoferować unikalną alternatywę dla Monero. Baza kodowa jest celowo trzymana w pobliżu Monero,
korzysta z wyższej niezawodności kodu dzięki większemu źródłu recenzji osób dostępnych w Monero.

## Łączenie poprawek upstream

Powyższy cel został osiągnięty dzięki ciągłemu łączeniu ulepszeń w górę. Każdy z wystarczającą ilością
wiedzy jest zachęcany do wkładu w ten wysiłek. W celu zapewnienia spójności zmian (co bardzo
pomaga także nowym programistom w łatwym przechodzeniu przez dziennik zatwierdzania i odsyłacze między dwoma repozytoriami)
aby poprawnie przypisać oryginalnego autora, użyj polecenia `git cherry-pick`.

Zdecydowanie zaleca się również poprawienie pierwszej linii komunikatu zatwierdzenia za pomocą odpowiedniego żądania ściągnięcia
numeru, dzięki czemu można łatwo odnieść się do oryginalnego PR Monero. Na przykład, jeśli chcesz połączyć upstream PR 4356
który ma dwa zatwierdzenia z następującymi komunikatami zatwierdzenia:

    Docker android: użyj wspólnego przedrostka
    Docker android: dodaj libsodium

następnie wykonaj odpowiednie komunikaty zatwierdzenia w następujący sposób:

    Docker android: użyj wspólnego przedrostka / monero # 4356
    Docker android: dodaj libsodium / monero # 4356

Zauważ, że postfix jest dodawany do pierwszego wiersza każdego komunikatu zatwierdzenia. Ponadto, proszę, podejmij rozsądny wysiłek i
utrzymuj kolejność łączenia poprawek zgodnie z oryginałem, aby pominąć potencjalne problemy takie jak scalanie konfliktów itp.
Takie czynności są zabronione, chociaż nie jest to ścisły wymóg.

## Proponowanie zmian

Powyższy wysiłek jest ułatwiony dzięki uniknięciu tworzenia niepotrzebnych różnic w repozytorium. To daje do zrozumienia ze
**wszelkie proponowane zmiany, które odnoszą się również do Monero, należy przesyłać do Monero.** W szczególności prosimy o przesłanie wyciągu
najpierw zwróć się do Monero, a następnie wyślij odpowiedni PR do Aeon przez cherry pick, jak opisano powyżej. Jeśli twój PR Monero
zostanie scalony, odpowiadający ci Aeon PR zostanie następnie scalony.

Jeśli chcesz zaproponować zmiany specyficzne dla Aeon i inne niż Monero, prześlij bezpośrednio żądanie ściągnięcia
Aeon i uzasadnij swoje zmiany, określając, w jaki sposób są *bardziej* lub *wyjątkowo* obowiązujące dla Aeon. Z dobrym
uzasadnieniem, opisane powyżej, obciążenie zwiększonymi kosztami utrzymania można przezwyciężyć.

# Przyczynianie się do Monero

Dobrym sposobem na pomoc jest testowanie i zgłaszanie błędów. Widz
[Jak skutecznie zgłaszać błędy (Simon Tatham)] (https://www.chiark.greenend.org.uk/~sgtatham/bugs.html)
jeśli chcesz pomóc w ten sposób. Testowanie jest nieocenione w tworzeniu dzieła
oprogramowania solidnego i użytecznego.


## Ogólne wytyczne

* Zachęca się do komentarzy.
* Jeśli modyfikujesz kod, dla którego istnieją nagłówki Doxygen, nagłówek musi zostać zmodyfikowany, aby pasował.
* Testy byłyby miłe, gdybyś dodał funkcjonalność.

Poprawki najlepiej wysyłać za pomocą żądania ściągnięcia Github. Jeśli to
nie można tego zrobić, można wysłać łatki w formacie „git-format-patch”
(np. wysłane do fpaste.org z wystarczająco długim czasem oczekiwania i linkiem
opublikowano na # monero-dev na irc.freenode.net).

Poprawki powinny być samodzielne. Dobrą zasadą jest posiadanie
jedna łata na oddzielne wydanie, funkcję lub zmianę logiczną. Również na
inne zmiany, takie jak losowe zmiany białych znaków lub reindentacja.
Podążając za stylem kodu określonego fragmentem kodu, łatwiej
zachęcic do modyfikacji. Właściwe zgniatanie powinno być wykonane (np. Jeśli
robisz buggy patch, potem późniejszą poprawkę, by naprawić błąd,
obie poprawki powinny zostać połączone).

Jeśli dokonałeś losowych, niepowiązanych zmian (albo z powodu twojego edytora)
jest denerwujące lub zrobiłeś je z innych powodów), możesz wybrać
jakie zmiany przechodzą do nadchodzącego zatwierdzenia za pomocą git add -p, który
przeprowadza cię przez wszystkie zmiany i pyta, czy nie
włącz tę konkretną zmianę. Pomaga to tworzyć czyste poprawki
bez żadnych nieistotnych zmian. git diff pokaże zmiany
w twoim drzewie. git diff --cached pokaże, co jest aktualnie przemieszczane
do zatwierdzenia. Gdy dodasz porcje z git add -p, te porcje będą
„przenieś” z wyjścia git diff do wyjścia git diff --cached,
dzięki czemu możesz wyraźnie zobaczyć, jak będzie wyglądać Twoje zatwierdzenie.

## Zatwierdzenia i żądania ściągania

Komunikaty zatwierdzające powinny być rozsądne. To oznacza temat
opisuje łatę, z opcjonalnym dłuższym opisem, które podaje szczegóły,
dokumentacje itp.

Wysyłając żądanie ściągnięcia na Github, upewnij się, że twoja gałąź jest
rebased. Żadne scalenie nie zatwierdza ani nie dopuszcza innych osób
proszę o przesłanie branchu. Możesz zostać poproszony o ponowny rebase, jeśli istnieją
konflikty (nawet trywialnie rozwiązywalne).

Zachęca się do podpisywania podpisem PGP. To powinno wyjaśniać dlaczego
poprzedni akapit jest tutaj.

# [Code of Conduct (22/C4.1)](http://rfc.zeromq.org/spec:22)

## Licencja

Copyright (c) 2009-2015 Pieter Hintjens.
Prawa autorskie (c) 2017-2018 Projekt Monero.

Ta specyfikacja jest wolnym oprogramowaniem; możesz go rozpowszechniać i/lub modyfikować zgodnie z warunkami GNU General Public License opublikowanej przez Free Software Foundation; albo wersja 3 licencji, albo (według własnego uznania) dowolna późniejsza wersja.

Niniejsza specyfikacja jest rozpowszechniana w nadziei, że będzie przydatna, ale BEZ ŻADNEJ GWARANCJI; bez dorozumianej gwarancji PRZYDATNOŚCI HANDLOWEJ lub PRZYDATNOŚCI DO OKREŚLONEGO CELU. Więcej informacji można znaleźć w Powszechnej Licencji Publicznej GNU.

Powinieneś otrzymać kopię GNU General Public License wraz z tym programem; jeśli nie, zobacz <http://www.gnu.org/licenses>.

## Język

Słowa kluczowe „MUSZĄ”, „NIE MUSZĄ”, „WYMAGANE”, „MUSZĄ”, „NIE POWINNY”, „POWINNY”, „POWINNY NIE”, „ZALECANE”, „MOŻE” i „OPCJONALNE” w tym dokumencie są interpretować zgodnie z opisem w RFC 2119.

Zespół „Monero Maintainer” jest zdefiniowany w tym dokumencie jako następujący użytkownicy:
- fluffypony
- moneromooo
- hyc

## Cele

C4 ma zapewnić optymalny model współpracy wielokrotnego użytku dla projektów oprogramowania open source. Ma te konkretne cele:

- Aby zmaksymalizować skalę i różnorodność społeczności wokół projektu, zmniejszając trudność dla nowych Współtwórców i tworząc skalowany model uczestnictwa z silnymi pozytywnymi sprzężeniami zwrotnymi;
- Uwolnienie zależności od kluczowych osób poprzez oddzielenie różnych zestawów umiejętności, tak aby istniała większa pula kompetencji w każdej wymaganej domenie;
- Umożliwić szybszy i dokładniejszy rozwój projektu poprzez zwiększenie różnorodności procesu podejmowania decyzji;
- Wspieranie naturalnego cyklu życia wersji projektu od eksperymentalnej do stabilnej, poprzez umożliwienie bezpiecznego eksperymentowania, szybkiej awarii i izolacji stabilnego kodu;
- Zmniejszenie wewnętrznej złożoności repozytoriów projektów, co ułatwi uczestnikom uczestnictwo i zmniejszy zakres błędu;
- Egzekwowanie zbiorowej własności projektu, co zwiększa zachętę ekonomiczną dla Uczestników i zmniejsza ryzyko porwania przez wrogie podmioty.

## Design

### Eliminacje

- Projekt MUSI używać rozproszonego systemu kontroli wersji git.
- Projekt MUSI być hostowany na github.com lub jego odpowiedniku, zwanym tutaj „Platformą”.
- Projekt MUSI używać trackera problemów z platformą.
  - Przykład bez GitHub:
    - „Platforma” może być waniliowym repozytorium git i Tracem hostowanym na tej samej maszynie / sieci.
    - Tracker problemów z platformą to Trac.
- Projekt POWINIEN mieć jasno udokumentowane wytyczne dotyczące stylu kodu.
- „Współtwórca” to osoba, która chce dostarczyć łatę, będącą zbiorem zatwierdzeń, które rozwiązują pewien wyraźnie zidentyfikowany problem.
- „Opiekun” to osoba, która łączy łatki z projektem. Opiekunowie nie są programistami; ich zadaniem jest egzekwowanie procesu.
- Współpracownicy NIE MOGĄ mieć dostępu do repozytorium, chyba że są także Opiekunami.
- Opiekunowie MUSZĄ mieć dostęp do repozytorium.
- Każdy, bez rozróżnienia lub dyskryminacji, MUSI mieć równe prawo do zostania Współtwórcą zgodnie z warunkami niniejszej umowy.

### Licencjonowanie i własność

- Projekt MUSI używać licencji podobnej do akcji, takiej jak BSD-3, GPLv3 lub jej wariant (LGPL, AGPL) lub MPLv2.
- Cały wkład do kodu źródłowego projektu („łatki”) MUSI używać tej samej licencji co projekt.
- Wszystkie poprawki są własnością ich autorów. NIE MUSI być żadnego procesu przypisywania praw autorskich.
- Prawa autorskie do projektu MUSZĄ być własnością zbiorową wszystkich jego Współtwórców.
- Każdy współtwórca MUSI być odpowiedzialny za identyfikację siebie na liście Współtwórców projektu.

### Wymagania dotyczące poprawki

- Opiekunowie MUSZĄ posiadać konto Platformowe i POWINNI używać ich prawdziwych nazwisk lub dobrze znanego aliasu.
- Współpracownicy POWINNI mieć konto Platformowe i MOGĄ używać ich prawdziwych nazwisk lub dobrze znanego aliasu.
- Poprawka powinna być minimalną i dokładną odpowiedzią na dokładnie jeden zidentyfikowany i uzgodniony problem.
- Łatka MUSI stosować się do wytycznych stylu kodu projektu, jeśli są one zdefiniowane.
- Łata MUSI być zgodna z wytycznymi „Ewolucja zamówień publicznych” zdefiniowanymi poniżej.
- Łatka NIE POWINNA zawierać nietrywialnego kodu z innych projektów, chyba że Dostawca jest oryginalnym autorem tego kodu.
- Łatka MUSI kompilować czysto i przekazywać autotesty projektu przynajmniej na podstawowej platformie docelowej.
- Komunikat zatwierdzenia poprawki POWINNY składać się z pojedynczej krótkiej (mniej niż 50 znaków) linii podsumowującej zmianę, po której opcjonalnie następuje pusty wiersz, a następnie bardziej szczegółowy opis.
- „Poprawna poprawka” to taka, która spełnia powyższe wymagania.

### Proces rozwoju

- Zmiana projektu MUSI być regulowana przez precyzyjne identyfikowanie problemów i stosowanie minimalnych, dokładnych rozwiązań tych problemów.
- Aby zażądać zmian, użytkownik POWINIEN zarejestrować problem w programie śledzącym problemy z platformą.
- Użytkownik lub współtwórca POWINIEN napisać problem, opisując problem, który napotykają lub obserwują.
- Użytkownik lub współtwórca POWINIEN dążyć do porozumienia co do dokładności ich obserwacji oraz wartości rozwiązania problemu.
- Użytkownicy NIE MUSZĄ rejestrować żądań funkcji, pomysłów lub sugestii niezwiązanych z kodem Monero lub kodem zależności Monero lub potencjalnym / przyszłym kodem zależności Monero lub badaniami, które z powodzeniem implementują Monero.
- Użytkownicy MUSZĄ NIE logować żadnych rozwiązań problemów (weryfikowalnych lub hipotetycznych), które nie są wyraźnie udokumentowane i / lub nie można ich udowodnić i / lub nie można ich w uzasadniony sposób udowodnić.
- Tak więc historia wydania projektu MUSI być listą znaczących zagadnień rejestrowanych i rozwiązywanych.
- Aby pracować nad problemem, dostawca SHALL rozwidla repozytorium projektu, a następnie pracuje nad ich rozwidlonym repozytorium.
- Aby przesłać poprawkę, Współtwórca MUSI utworzyć żądanie wycofania platformy z powrotem do projektu.
- Współtwórca NIE MUSI zatwierdzać zmian bezpośrednio w projekcie.
- Aby przedyskutować poprawkę, ludzie MOGĄ komentować żądanie ściągnięcia platformy, zatwierdzenie lub gdziekolwiek indziej.
- Aby zaakceptować lub odrzucić poprawkę, Opiekun MUSI korzystać z interfejsu Platformy.
- Opiekunowie NIE POWINNI łączyć swoich własnych poprawek z wyjątkiem wyjątkowych przypadków, takich jak brak reakcji ze strony innych Opiekunów przez dłuższy okres (ponad 30 dni) lub, chyba że pilne, jak określił Zespół Opiekunów Monero.
- Opiekunowie NIE MOGĄ dokonywać oceny wartości poprawnych poprawek, chyba że Opiekun (jak może się zdarzyć w rzadkich przypadkach) jest głównym twórcą kodu.
- Opiekunowie NIE MOGĄ łączyć żądań ściągania w czasie krótszym niż 168 godzin (1 tydzień), chyba że co najmniej 2 osoby z Zespołu Opiekuna Monero uznają to za pilne.
- Dostawca może oznaczyć problem jako „Gotowy” po złożeniu żądania pobrania problemu.
- Użytkownik, który stworzył problem POWINIEN zamknąć problem po sprawdzeniu, że poprawka się powiodła.
- Opiekunowie POWINNI prosić o ulepszenia nieprawidłowych poprawek i POWINIEN odrzucać nieprawidłowe poprawki, jeśli współtwórca nie odpowiada konstruktywnie.
- Każdy Współtwórca, który ma osądy wartościowe na poprawnej poprawce POWINIEN je wyrazić za pomocą własnych poprawek.
- Opiekunowie MOGĄ zatwierdzać zmiany w dokumentacji nie źródłowej bezpośrednio do projektu.

### Tworzenie stabilnych wersji

- Projekt MUSI mieć jedną gałąź („master”), która zawsze posiada najnowszą wersję w toku i POWINIEN zawsze budować.
- Projekt NIE MUSI używać gałęzi tematów z jakiegokolwiek powodu. Osobiste forki MOGĄ używać gałęzi tematycznych.
- Aby uczynić stabilną wersję, ktoś MUSI rozwidlić repozytorium, kopiując je i tym samym zostać opiekunem tego repozytorium.
- Rozwijanie projektu do stabilizacji MOŻE być wykonywane jednostronnie i bez zgody opiekunów projektów.
- Poprawka do projektu stabilizacyjnego, która została ogłoszona jako „stabilna”, MUSI towarzyszyć powtarzalny przypadek testowy.

### Ewolucja zamówień publicznych

- Wszystkie zamówienia publiczne (API lub protokoły) MUSZĄ być udokumentowane.
- Wszystkie zamówienia publiczne POWINNY mieć miejsce na rozszerzalność i eksperymentowanie.
- Łata, która modyfikuje stabilny kontrakt publiczny POWINNA NIE łamać istniejących aplikacji, chyba że istnieje nadrzędny konsensus co do wartości takiego działania.
- Łata wprowadzająca nowe funkcje do kontraktu publicznego POWINNA to robić przy użyciu nowych nazw.
- Stare nazwy POWINNY być przestarzałe w sposób systematyczny, oznaczając nowe nazwy jako „eksperymentalne”, dopóki nie będą stabilne, a następnie oznaczając stare nazwy jako „przestarzałe”.
- Kiedy minie wystarczająca ilość czasu, stare przestarzałe nazwy POWINNY być oznaczone jako „legacy” i ostatecznie usunięte.
- Stare nazwy NIE MOGĄ być ponownie użyte przez nowe funkcje.
- Kiedy stare nazwy są usuwane, ich implementacje MUSZĄ prowokować wyjątek (asercję), jeśli są używane przez aplikacje.

### Administracja projektem

- Założyciele projektu MUSZĄ działać jako Administratorzy do zarządzania zestawem opiekunów projektów.
- Administratorzy MUSZĄ zapewniać własną sukcesję w czasie, promując najskuteczniejszych opiekunów.
- Nowy Współtwórca, który poprawi poprawkę MUSI zostać zaproszony do zostania Opiekunem.
- Administratorzy MOGĄ usunąć opiekunów, którzy są nieaktywni przez dłuższy czas, lub którzy wielokrotnie nie stosują dokładnie tego procesu.
- Administratorzy POWINNI blokować lub blokować „złych aktorów”, którzy powodują stres i ból innym w projekcie. Powinno to być zrobione po publicznej dyskusji, z szansą dla wszystkich stron na zabranie głosu. Zły aktor to ktoś, kto wielokrotnie ignoruje zasady i kulturę projektu, który jest niepotrzebnie kłótliwy lub wrogi, lub który jest obraźliwy, i który nie jest w stanie samodzielnie poprawić swojego zachowania, gdy zostanie poproszony przez innych.
