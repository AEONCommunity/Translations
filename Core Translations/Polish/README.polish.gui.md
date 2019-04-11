# Aeon GUI

Copyright (c) 2014-2018, AEON, The Monero Project

## Zasoby rozwojowe

- Web: [aeon.cash](http://aeon.cash)
- Bitcointalk: https://bitcointalk.org/index.php?topic=641696.0
- Reddit: https://www.reddit.com/r/Aeon
- Github: [https://github.com/aeonix/aeon-gui](https://github.com/aeonix/aeon-gui)
- IRC: [#aeon on Freenode](irc://chat.freenode.net/#aeon)

## Odpowiedź na lukę

- Odpowiedź na luki w zabezpieczeniach powinna zostać przekierowana na Monero, ponieważ znaczna część zaplecza technicznego Aeon jest współdzielona
- Nasz [Proces odpowiedzi na luki](https://github.com/monero-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) zachęca do odpowiedzialnego ujawniania informacji
- Jesteśmy również dostępni na [HackerOne](https://hackerone.com/monero)

## Wprowadzenie

Aeon to prywatna, bezpieczna, niewykrywalna, zdecentralizowana waluta cyfrowa. Jesteś swoim bankiem, kontrolujesz swoje fundusze i nikt nie może śledzić Twoich transferów, chyba że na to pozwolisz.

**Prywatność:** Aeon używa kryptograficznie silnego systemu, aby umożliwić wysyłanie i odbieranie funduszy bez łatwego ujawniania transakcji w łańcuchu bloków (księga transakcji, którą każdy ma). Zapewnia to, że twoje zakupy, pokwitowania i wszystkie przelewy pozostają domyślnie prywatne.

**Bezpieczeństwo:** Wykorzystując moc rozproszonej sieci konsensusowej peer-to-peer, każda transakcja w sieci jest zabezpieczona kryptograficznie. Poszczególne portfele mają 25-wyrazowe frazy mnemoniczne, które są wyświetlane tylko raz i można je zapisać, aby wykonać kopię zapasową portfela. Pliki portfela są szyfrowane hasłem, aby zapewnić ich bezużyteczność w przypadku kradzieży.

**Niewykrywalność:** Korzystając z sygnatur pierścieniowych, specjalnej właściwości pewnego rodzaju kryptografii, Aeon jest w stanie zapewnić, że transakcje są nie tylko niemożliwe do wykrycia, ale mają opcjonalną miarę niejednoznaczności, która zapewnia, że transakcje nie mogą być łatwo powiązane z indywidualnym użytkownikiem lub komputerem.

## O projekcie

Jest to GUI dla [implementacji core Aeon] (https://github.com/aeonix/aeon). Jest otwarte i całkowicie darmowe do użycia bez ograniczeń, z wyjątkiem tych określonych w poniższej umowie licencyjnej. Nie ma żadnych ograniczeń dla nikogo tworzącego alternatywną implementację Aeon, która używa protokołu i sieci w sposób zgodny.

Podobnie jak w przypadku wielu projektów deweloperskich, repozytorium w Github jest uważane za obszar „staging” dla najnowszych zmian. Zanim zmiany zostaną włączone do tego oddziału w głównym repozytorium, są testowane przez poszczególnych programistów we własnych oddziałach, przesyłane jako żądanie ściągnięcia, a następnie testowane przez autorów, którzy koncentrują się na testowaniu i recenzjach kodu. Mimo to repozytorium powinno być starannie rozważone przed użyciem go w środowisku produkcyjnym, chyba że w repozytorium znajduje się łatka dla konkretnego problemu z zatrzymywaniem programu. Zazwyczaj lepszym pomysłem jest użycie oznaczonego wydania dla stabilności.

## Wspieranie projektu

Aeon jest przedsięwzięciem sponsorowanym przez społeczność w 100%. Jeśli chcesz dołączyć do naszych wysiłków, najłatwiej jest wesprzeć projekt finansowo. Zarówno darowizny Aeon, jak i Bitcoin można przekazać do **donate.aeon.cash**, jeśli używasz klienta obsługującego standard [OpenAlias] (https://openalias.org). Alternatywnie możesz wysłać AEON na adres darowizny Aeon za pomocą polecenia `donate` (wpisz` help` w portfelu wiersza poleceń, aby uzyskać szczegółowe informacje).

Adres dotacji Aeon to: `WmsSWgtT1JPg5e3cK41hKXSHVpKW7e47bjgiKmWZkYrhSS5LhRemNyqayaSBtAQ6517eo5PtH9wxHVmM78JDZSUu2W8PqRiNs` (viewkey: `71bf19a7348ede17fa487167710dac401ef1556851bfd36b76040facf051630b`)

Adres dotacji Bitcoin to: `12Cyjf3qV6qLyXdzpLSLPdRFPUVidvnzFM`

Główne fundusze na rozwój i / lub niektóre usługi wspierające są również łaskawie zapewniane przez sponsorów:

[<img width="80" src="https://static.getmonero.org/images/sponsors/mymonero.png"/>](https://mymonero.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/kitware.png?1"/>](http://kitware.com)
[<img width="100" src="https://static.getmonero.org/images/sponsors/dome9.png"/>](http://dome9.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/araxis.png"/>](http://araxis.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/jetbrains.png"/>](http://www.jetbrains.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/navicat.png"/>](http://www.navicat.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/symas.png"/>](http://www.symas.com/)

Istnieje również kilka kopalni, które uprzejmie przekazują część swoich zysków, [ich lista znajduje się w naszym poście Bitcointalk](https://bitcointalk.org/index.php?topic=641696.0).

## Licencja

Zobacz [Licencja](LICENCJA).

## Instalacja Aeon GUI z pakietu

(**DO ZROBIENIA**) ~Pakiety są dostępne dla~

* ~Arch Linux z AUR: [aeon-wallet-qt](https://aur.archlinux.org/packages/aeon-wallet-qt/)~
* ~Void Linux: xbps-install -S aeon-core~
* ~GuixSD: guix package -i aeon-core~

Opakowanie dla Twojej ulubionej dystrybucji byłoby mile widzianym wkładem!

## Kompilowanie Aeon GUI ze źródła

### Na Linux:

(Przetestowane na Ubuntu 17.10 x64, Ubuntu 18.04 x64 i Gentoo x64)

1. Zainstaluj zależności Aeon

   - Dla dystrybucji Debiana (Debian, Ubuntu, Mint, Tails ...)

	`sudo apt install build-essential cmake libboost-all-dev miniupnpc libunbound-dev graphviz doxygen libunwind8-dev pkg-config libssl-dev libzmq3-dev libsodium-dev libhidapi-dev`

  - Dla Gentoo

	`sudo emerge app-arch/xz-utils app-doc/doxygen dev-cpp/gtest dev-libs/boost dev-libs/expat dev-libs/openssl dev-util/cmake media-gfx/graphviz net-dns/unbound net-libs/ldns net-libs/miniupnpc net-libs/zeromq sys-libs/libunwind dev-libs/libsodium dev-libs/hidapi`

2. Zainstaluj Qt:

  * Uwaga*: Qt 5.7 to minimalna wersja wymagana do zbudowania GUI. To sprawia, że **niektóre** dystrybucje (głównie oparte na debianie, jak Ubuntu 16.x lub Linux Mint 18.x) są przestarzałe. Nadal możesz zbudować GUI, jeśli zainstalujesz [oficjalne wydanie Qt] (https://wiki.qt.io/Install_Qt_5_on_Ubuntu), ale nie jest to oficjalnie obsługiwane.

  - Dla Ubuntu 17.10+

    `sudo apt install qtbase5-dev qt5-default qtdeclarative5-dev qml-module-qtquick-controls qml-module-qtquick-controls2 qml-module-qtquick-dialogs qml-module-qtquick-xmllistmodel qml-module-qt-labs-settings qml-module-qt-labs-folderlistmodel qttools5-dev-tools qml-module-qtquick-templates2`

  - Dla Gentoo

    `sudo emerge dev-qt/qtcore:5 dev-qt/qtdeclarative:5 dev-qt/qtquickcontrols:5 dev-qt/qtquickcontrols2:5 dev-qt/qtgraphicaleffects:5`

  - Opcjonalne: Aby zbudować użyj flagę `WITH_SCANNER`

    - Dla Ubuntu

      `sudo apt install qtmultimedia5-dev qml-module-qtmultimedia libzbar-dev`

    - Dla Gentoo

      Flage *qml* USE musi być włączona.

      `emerge dev-qt/qtmultimedia:5 media-gfx/zbar`


3. Sklonuj repozytorium

    `git clone https://github.com/aeonix/aeon-gui.git`

4. Zbuduj

    ```
    cd aeon-gui
    QT_SELECT=5 ./build.sh
    ```

Plik wykonywalny można znaleźć w folderze build / release / bin.

### Na OS X:

1. Zainstaluj Xcode z AppStore

2. Zainstaluj [homebrew](http://brew.sh/)

3. Zainstaluj [Aeon](https://github.com/aeonix/aeon) zależności:

  `brew install boost --c++11`

  `brew install openssl` - aby zainstalowac nagłowki openssl

  `brew install pkgconfig`

  `brew install cmake`

  `brew install zeromq`

*Uwaga*: Jeśli cmake nie może znaleźć pliku zmq.hpp na OS X, zainstalowanie `zmq.hpp` z https://github.com/zeromq/cppzmq do` /usr/local/include` powinno naprawić ten błąd.

4. Zainstaluj Qt:

  `brew install qt5`  (lub pobierz QT 5.8+ z [qt.io](https://www.qt.io/download-open-source/))

  Jeśli masz starszą wersję Qt zainstalowaną przez homebrew, możesz zmusić ją do używania 5.x w ten sposób:

  `brew link --force --overwrite qt5`

5. Dodaj katalog bin Qt do swojej ścieżki

    Na przykład: `export PATH=$PATH:$HOME/Qt/5.8/clang_64/bin`

    Jest to katalog, w którym Qt 5.x jest zainstalowany w **twoim** systemie

6. Chwyć aktualną kopię repozytorium aeon-gui

  `git clone https://github.com/aeonix/aeon-gui.git`

7. Wejdź do repozytorium

  `cd aeon-gui`

8. Zacznij budować

  `./build.sh`

  Plik wykonywalny można znaleźć w folderze `build / release / bin`.

  **Uwaga:** Obejście problemu „BŁĄD: Xcode nie jest poprawnie skonfigurowany”

Edytuj `$HOME/Qt/5.8/clang_64/mkspecs/features/mac/default_pre.prf`

zamień
`isEmpty($$list($$system("/usr/bin/xcrun -find xcrun 2>/dev/null")))`

tym
`isEmpty($$list($$system("/usr/bin/xcrun -find xcodebuild 2>/dev/null")))`

Więcej informacji: http://stackoverflow.com/a/35098040/1683164


### Na Windows:

GUI Aeon w systemie Windows ma tylko 64 bity; 32-bitowe wersje GUI systemu Windows nie są już oficjalnie obsługiwane.

1. Zainstaluj [MSYS2] (https://www.msys2.org/), postępuj zgodnie z instrukcjami na tej stronie, w jaki sposób zaktualizować system i pakiety do najnowszych wersji

2. Otwórz 64-bitową powłokę MSYS2: użyj skrótu * MSYS2 MinGW 64-bit * lub użyj pliku wsadowego `msys2_shell.cmd` z parametrem` -mingw64`

3. Zainstaluj pakiety MSYS2 dla zależności Aeon; potrzebne pakiety 64-bitowe mają nazwy `x86_64`

    ```
    pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium mingw-w64-x86_64-hidapi
    ```

    Więcej informacji na temat tych zależności można znaleźć w dokumentacji [Aeon] (https://github.com/aeonix/aeon). Zauważ, że nie ma już potrzeby kompilowania Boost ze źródła; jak wszystko inne, możesz zainstalować go teraz z pakietem MSYS2.

4. Zainstaluj Qt5

    ```
    pacman -S mingw-w64-x86_64-qt5
    ```

    Nie ma potrzeby pobierania specjalnego instalatora ze strony Qt, standardowy pakiet MSYS2 dla Qt będzie działał w prawie wszystkich okolicznościach.

5. Zainstaluj git

    ```
    pacman -S git
    ```

6. Sklonuj repozytorium

    ```
    git clone https://github.com/aeonix/aeon-gui.git
    ```

7. Zbuduj

    ```
    cd aeon-gui
    source ./build.sh release-static
    cd build
    make deploy
    ```

    **Uwaga:** Użycie powyższego `source` jest obejściem dla podejrzanego błędu w obecnej wersji QT 5.11.2-3 dostępnej w systemie pakowania MSYS2, patrz https://github.com/monero-project/monero-gui/issues/1559, aby uzyskać więcej informacji.

Plik wykonywalny można znaleźć w katalogu `.\release\bin`
