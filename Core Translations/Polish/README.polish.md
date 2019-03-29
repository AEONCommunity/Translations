# Aeon

[![Github All Releases](https://img.shields.io/github/downloads/aeonix/aeon/total.svg)](../../releases)
[![GitHub release](https://img.shields.io/github/release/aeonix/aeon/all.svg)](../../releases/latest)
[![GitHub Release Date](https://img.shields.io/github/release-date-pre/aeonix/aeon.svg)](../../releases/latest)
[![GitHub top language](https://img.shields.io/github/languages/top/aeonix/aeon.svg)](../../)
[![GitHub language count](https://img.shields.io/github/languages/count/aeonix/aeon.svg)](../../)
[![GitHub repo size in bytes](https://img.shields.io/github/repo-size/aeonix/aeon.svg)](../../)

[![GitHub last commit](https://img.shields.io/github/last-commit/aeonix/aeon.svg)](../../)
[![Github commits (since latest release)](https://img.shields.io/github/commits-since/aeonix/aeon/latest.svg)](../../)
[![GitHub stars](https://img.shields.io/github/stars/aeonix/aeon.svg)](../../stargazers)
[![GitHub forks](https://img.shields.io/github/forks/aeonix/aeon.svg)](../../network)
[![GitHub issues](https://img.shields.io/github/issues/aeonix/aeon.svg)](../../issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/aeonix/aeon.svg)](../../issues)

Copyright (c) 2014-2018, AEON, The Monero Project.   
Portions Copyright (c) 2012-2013 The Cryptonote developers.

## Zasoby rozwojowe

- Web: [aeon.cash](https://aeon.cash)
- Bitcointalk: https://bitcointalk.org/index.php?topic=641696.0
- Reddit: https://www.reddit.com/r/Aeon
- GitHub: [https://github.com/aeonix/aeon](https://github.com/aeonix/aeon)
- IRC: [#aeon on Freenode](https://webchat.freenode.net/?randomnick=1&channels=%23aeon&prompt=1&uio=d4)
- Discord: https://discord.gg/TM8mEsx

## Odpowiedź na lukę

- Odpowiedź na luki w zabezpieczeniach powinna zostać przekierowana na Monero, ponieważ znaczna część zaplecza technicznego Aeon jest współdzielona
- Nasz [Proces odpowiedzi na luki](https://github.com/monero-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) zachęca do odpowiedzialnego ujawniania informacji
- Jesteśmy również dostępni na [HackerOne](https://hackerone.com/monero)

## Ogłoszenia

- Możesz zapisać się na  [listę ogłoszeń](https://docs.google.com/forms/d/e/1FAIpQLSci2UitA67N0W_xgSPLlGj6acGnTOtTdDR_ODZwXTHXZsWnCQ/viewform) aby uzyskać krytyczne komunikaty od głównego zespołu Aeon. Lista ogłoszeń może być bardzo pomocna przy ustalaniu, kiedy potrzebne są aktualizacje oprogramowania.

## Pokrycie

| Typ       | Status |
|-----------|--------|
| Licencja  | [![License](https://img.shields.io/badge/license-BSD3-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Wprowadzenie

Aeon to prywatna, bezpieczna, niewykrywalna, zdecentralizowana waluta cyfrowa. Jesteś swoim bankiem, kontrolujesz swoje fundusze i nikt nie może śledzić Twoich transferów, chyba że na to pozwolisz.

**Prywatność:** Aeon używa kryptograficznie silnego systemu, aby umożliwić wysyłanie i odbieranie funduszy bez łatwego ujawniania transakcji w łańcuchu bloków (księga transakcji, którą każdy ma). Zapewnia to, że twoje zakupy, pokwitowania i wszystkie przelewy pozostają domyślnie prywatne.

**Bezpieczeństwo:** Wykorzystując moc rozproszonej sieci konsensusowej peer-to-peer, każda transakcja w sieci jest zabezpieczona kryptograficznie. Poszczególne portfele mają 25-wyrazowe frazy mnemoniczne, które są wyświetlane tylko raz i można je zapisać, aby wykonać kopię zapasową portfela. Pliki portfela są szyfrowane hasłem, aby zapewnić ich bezużyteczność w przypadku kradzieży.

**Niewykrywalność:** Korzystając z sygnatur pierścieniowych, specjalnej właściwości pewnego rodzaju kryptografii, Aeon jest w stanie zapewnić, że transakcje są nie tylko niemożliwe do wykrycia, ale mają opcjonalną miarę niejednoznaczności, która zapewnia, że transakcje nie mogą być łatwo powiązane z indywidualnym użytkownikiem lub komputerem.

## O projekcie

To jest podstawowa implementacja Aeon. Jest otwarty i całkowicie darmowy do użycia bez ograniczeń, z wyjątkiem tych określonych w poniższej umowie licencyjnej. Nie ma żadnych ograniczeń dla nikogo tworzącego alternatywną implementację Aeon, która używa protokołu i sieci w sposób zgodny.

Podobnie jak w przypadku wielu projektów deweloperskich, repozytorium w Github jest uważane za obszar „staging” dla najnowszych zmian. Zanim zmiany zostaną włączone do tego oddziału w głównym repozytorium, są testowane przez poszczególnych programistów we własnych oddziałach, przesyłane jako żądanie ściągnięcia, a następnie testowane przez autorów, którzy koncentrują się na testowaniu i recenzjach kodu. Mimo to repozytorium powinno być starannie rozważone przed użyciem go w środowisku produkcyjnym, chyba że w repozytorium znajduje się łatka dla konkretnego problemu z zatrzymywaniem programu. Zazwyczaj lepszym pomysłem jest użycie oznaczonego stabilnego wydania.

**Każdy może wnieść swój wkład w bazę kodu Aeona!** Jeśli masz poprawkę lub zmianę kodu, prześlij ją jako żądanie ściągnięcia bezpośrednio do gałęzi „master”. W przypadkach, gdy zmiana jest stosunkowo niewielka lub nie wpływa na inne części bazy kodu, może zostać natychmiast połączona przez dowolnego ze współpracowników. Z drugiej strony, jeśli zmiana jest szczególnie duża lub złożona, oczekuje się, że zostanie ona szczegółowo omówiona albo z dużym wyprzedzeniem przed przesłaniem żądania ściągnięcia, albo nawet bezpośrednio na żądanie ściągnięcia.

## Wspieranie projektu

Aeon jest przedsięwzięciem sponsorowanym przez społeczność w 100%. Jeśli chcesz dołączyć do naszych wysiłków, najłatwiej jest wesprzeć projekt finansowo. Zarówno darowizny Aeon, jak i Bitcoin można przekazać do **donate.aeon.cash**, jeśli używasz klienta obsługującego standard [OpenAlias] (https://openalias.org). Alternatywnie możesz wysłać AEON na adres darowizny Aeon za pomocą polecenia `donate` (wpisz` help` w portfelu wiersza poleceń, aby uzyskać szczegółowe informacje).

Adres dotacji Aeon to: `WmsSWgtT1JPg5e3cK41hKXSHVpKW7e47bjgiKmWZkYrhSS5LhRemNyqayaSBtAQ6517eo5PtH9wxHVmM78JDZSUu2W8PqRiNs` (viewkey: `71bf19a7348ede17fa487167710dac401ef1556851bfd36b76040facf051630b`)

Adres dotacji Bitcoin to: `12Cyjf3qV6qLyXdzpLSLPdRFPUVidvnzFM`

Główne fundusze na rozwój i / lub niektóre usługi wspierające są również łaskawie zapewniane przez sponsorów:

[<img width="80" src="https://static.getmonero.org/images/sponsors/mymonero.png"/>](https://mymonero.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/kitware.png?1"/>](https://kitware.com)
[<img width="100" src="https://static.getmonero.org/images/sponsors/dome9.png"/>](https://dome9.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/araxis.png"/>](https://araxis.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/jetbrains.png"/>](https://www.jetbrains.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/navicat.png"/>](https://www.navicat.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/symas.png"/>](https://www.symas.com/)

Istnieje również kilka kopalni, które uprzejmie przekazują część swoich zysków, [ich lista znajduje się w naszym poście Bitcointalk](https://bitcointalk.org/index.php?topic=641696.0).

## Licencja

Zobacz [Licencja](LICENCJA).

## Wsparcie

Jeśli chcesz pomóc zobacz sekcję [Wsparcie](CONTRIBUTING.polish.md) gdzie znajdziesz zestaw poradników.

## Aktualizacje oprogramowania

Aeon używa mechanizmu aktualizacji oprogramowania (hard fork) do implementacji nowych funkcji. Oznacza to, że użytkownicy Aeon (użytkownicy końcowi i dostawcy usług) powinni uruchamiać bieżące wersje i aktualizować oprogramowanie w razie potrzeby. **W przeciwieństwie do Monero, nie ma ustalonego harmonogramu dla hard forków, a harmonogram następnego forku zostanie określony organicznie poprzez dyskusję społeczności.** Wymagane oprogramowanie do tych aktualizacji będzie dostępne przed zaplanowaną datą. Proszę sprawdzić repozytorium przed tą datą, aby uzyskać właściwą wersję oprogramowania Aeon. Poniżej znajduje się harmonogram historyczny i przewidywany harmonogram następnej aktualizacji.
DData przedstawiona jest w formacie RRRR-MM-DD. 



| Software upgrade block height | Date       | Fork version | Minimum Aeon version | Recommended Aeon version | Details                                                                            |  
| ------------------------------ | -----------| ----------------- | ---------------------- | -------------------------- | ---------------------------------------------------------------------------------- |
| 592000                        | 2015-08-04 | v1 (exceptional, version not bumped)      | v0.9.0.0                 | v0.9.14.0                     | blocktime = 240 seconds, CryptoNight-Lite, lower mining priority for ringsize < 3       |
| 963500                        | 2018-06-03 | v7                | v0.12.0.0                 | v0.12.9.0-aeon                    | Rebase to Monero's latest codebase with RingCT disabled, CryptoNight-Lite variant 1, limited use of ringsize 1, ban ringsize 2   |

## Kompilacja Aeon ze źródeł

### Zależności

Poniższa tabela podsumowuje narzędzia i biblioteki wymagane do zbudowania.
Kilka bibliotek jest również zawartych w tym repozytorium (oznaczone jako
„Vendored”). Domyślnie kompilacja używa biblioteki zainstalowanej w systemie,
i ignoruje źródła zewnętrzne. Jeśli jednak nie zostanie znaleziona żadna biblioteka zainstalowana w
systemie, źródło zewnętrzne zostanie zbudowane i użyte. Zewnętrzne
źródła są również używane do kompilacji statycznej, ponieważ dystrybuowane
pakiety często zawierają tylko pliki binarne biblioteki współdzielonej (`.so`), ale nie są statyczne
archiwa biblioteczne (`.a`).
| Dep          | Min. version  | Vendored | Debian/Ubuntu pkg  | Arch pkg     | Fedora            | Optional | Purpose        |
| ------------ | ------------- | -------- | ------------------ | ------------ | ----------------- | -------- | -------------- |
| GCC          | 4.7.3         | NO       | `build-essential`  | `base-devel` | `gcc`             | NO       |                |
| CMake        | 3.5           | NO       | `cmake`            | `cmake`      | `cmake`           | NO       |                |
| pkg-config   | any           | NO       | `pkg-config`       | `base-devel` | `pkgconf`         | NO       |                |
| Boost        | 1.58          | NO       | `libboost-all-dev` | `boost`      | `boost-devel`     | NO       | C++ libraries  |
| OpenSSL      | basically any | NO       | `libssl-dev`       | `openssl`    | `openssl-devel`   | NO       | sha256 sum     |
| libzmq       | 3.0.0         | NO       | `libzmq3-dev`      | `zeromq`     | `cppzmq-devel`    | NO       | ZeroMQ library |
| OpenPGM      | ?             | NO       | `libpgm-dev`       | `libpgm`     | `openpgm-devel`   | NO       | For ZeroMQ     |
| libnorm[2]   | ?             | NO       | `libnorm-dev`      |              |               `   | YES      | For ZeroMQ     |
| libunbound   | 1.4.16        | YES      | `libunbound-dev`   | `unbound`    | `unbound-devel`   | NO       | DNS resolver   |
| libsodium    | ?             | NO       | `libsodium-dev`    | `libsodium`  | `libsodium-devel` | NO       | cryptography   |
| libunwind    | any           | NO       | `libunwind8-dev`   | `libunwind`  | `libunwind-devel` | YES      | Stack traces   |
| liblzma      | any           | NO       | `liblzma-dev`      | `xz`         | `xz-devel`        | YES      | For libunwind  |
| libreadline  | 6.3.0         | NO       | `libreadline6-dev` | `readline`   | `readline-devel`  | YES      | Input editing  |
| ldns         | 1.6.17        | NO       | `libldns-dev`      | `ldns`       | `ldns-devel`      | YES      | SSL toolkit    |
| expat        | 1.1           | NO       | `libexpat1-dev`    | `expat`      | `expat-devel`     | YES      | XML parsing    |
| GTest        | 1.5           | YES      | `libgtest-dev`[1]  | `gtest`      | `gtest-devel`     | YES      | Test suite     |
| Doxygen      | any           | NO       | `doxygen`          | `doxygen`    | `doxygen`         | YES      | Documentation  |
| Graphviz     | any           | NO       | `graphviz`         | `graphviz`   | `graphviz`        | YES      | Documentation  |
| pcsclite     | ?             | NO       | `libpcsclite-dev`  | ?            | `pcsc-lite pcsc-lite-devel` | NO | Ledger     |          


[1] na Debian/Ubuntu `libgtest-dev` zawiera jedynie źrodła i nagłówki. Musisz
zbudować ta bibliotekę binarną ręcznie. Umożliwi ci to wykonanie komendy ```sudo apt-get install libgtest-dev && cd /usr/src/gtest && sudo cmake . && sudo make && sudo mv libg* /usr/lib/ ```
[2] libnorm-dev jest potrzebny jeśli twoja biblioteka zmq została zbudowana z libnorm, inaczej nie jest potrzebna

Zainstaluj wszystkie zależności za pomocą jednego wiersza poleceń dla systemu Debian/Ubuntu:
``` sudo apt update && sudo apt install build-essential cmake git pkg-config libboost-all-dev libssl-dev libzmq3-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libreadline6-dev libldns-dev libexpat1-dev doxygen graphviz libpcsclite-dev libpgm-dev```
### Klonowanie reposzytorium

Klonuj rekurencyjnie, aby wciągnąć potrzebne moduły:

`$ git clone --recursive https://github.com/aeonix/aeon`

Jeśli już masz repo sklonowane, zainicjuj i zaktualizuj:

`$ cd aeon && git submodule init && git submodule update`

### Instrukcje budowania

Aeon używa systemu budowania CMake i [Makefile] najwyższego poziomu (Makefile)
w razie potrzeby wywołuje polecenia cmake.

#### Na Linux i OS X

* Zainstaluj zależności
* Przejdź do katalogu głównego kodu źródłowego, zmień na najnowszy tag wydania i zbuduj:

        cd aeon
        git checkout v0.12.9.0-aeon
        make

    *OOpcjonalnie*: Jeśli twoja maszyna ma kilka rdzeni i wystarczającą ilość pamięci,
     włącz budowanie równoległe przez uruchomienie `make -j <liczba wątków>` zamiast `make`.
     Aby było to opłacalne, maszyna powinna mieć jeden rdzeń i około 2 GB pamięci RAM dostępnej na wątek.

    *Uwaga*: Jesli cmake nie znajdzie zmq.hpp pliku na OS X, zainstalowanie `zmq.hpp` z
    https://github.com/zeromq/cppzmq do `/usr/local/include` powinno rozwiąć problem.

    *Uwaga*: Powyższe instrucje skompilują najbardziej stabilną wersję oprogramowania
    Aeon. Jeśli chcesz użyć i przetestować najowsze zmiany oprogramowania,
    użyj ```git checkout master```. Branch master może zawierać aktualizacje które mągą być
    niestabilne i nie kompatybilne z wersją release, testowanie zawsze mile widziane.

* Wynikowe pliki wykonywalne można znaleźć w `build/release/bin`

* Dodaj `PATH="$PATH:$HOME/aeon/build/release/bin"` do `.profile`

* Uruchom Aeon komendą `aeond --detach`

* **Opcjonalnie**: zbuduj i uruchom release-test , aby zweryfikować pliki binarne:

        make release-test

    *UWAGA*: `core_tests` test może potrwać kilka godzin.

* **Opcjonalnie**: aby zbudować pliki binarne odpowiednie do debugowania:

         make debug

* **Opcjonalnie**: aby zbudować statczne pliki binarne:

         make release-static

Zależności należy budować za pomocą -fPIC. Biblioteki statyczne zwykle nie są, więc być może będziesz musiał sam je zbudować za pomocą -fPIC. Informacje na temat ich tworzenia można znaleźć w ich dokumentacji.

* **Opcjonalnie**: zbuduj dokumentację w `doc / html` (pomiń` HAVE_DOT = YES` jeśli `graphviz` nie jest zainstalowany):

        HAVE_DOT=YES doxygen Doxyfile

#### Na Raspberry Pi

Przetestowany na Raspberry Pi Zero z czystą instalacją minimalnego Raspbian Stretch (2017-09-07 lub później) z https://www.raspberrypi.org/downloads/raspbian/. Jeśli używasz Raspian Jessie, [patrz uwaga w następnej sekcji] (# note-for-raspbian-jessie-users).

* `apt-get update && apt-get upgrade` aby zainstalować wszystkie najnowsze pakiety.

* Zainstaluj zależności dla Aeon z kolumny „Debian” w powyższej tabeli.

* Zwiększ rozmiar systemowego swap:
```
	sudo /etc/init.d/dphys-swapfile stop  
	sudo nano /etc/dphys-swapfile  
	CONF_SWAPSIZE=2048
	sudo /etc/init.d/dphys-swapfile start  
```
* Jeśli używasz zewnętrznego dysku twardego bez zewnętrznego źródła zasilania, upewnij się, że ma wystarczającą moc, aby uniknąć problemów sprzętowych podczas synchronizacji, dodając wiersz „max_usb_current = 1” do /boot/config.txt

* Sklonuj Aeon i sprawdź najnowszą wersję wydania:
```
        git clone https://github.com/aeonix/aeon.git
	cd aeon
	git checkout tags/v0.12.9.0-aeon
```
* Zbuduj:
```
        make release
```
* Poczekaj 4-6 godzin

* Wynikowe pliki wykonywalne można znaleźć w `build/release/bin`

* Dodaj `PATH="$PATH:$HOME/aeon/build/release/bin"` do `.profile`

* Uruchom z komendą  `aeond --detach`

* Możesz zmniejszyć rozmiar pliku wymiany(swap) po zakończeniu kompilacji i usunąć katalog boost z katalogu domowego

#### *Uwaga dla użytkowników Raspbian Jessie:*

Jeśli używasz starszego obrazu Raspbian Jessie, kompilacja Aeon jest nieco bardziej skomplikowana. Wersja Boost dostępna w repozytoriach Jessie Debiana jest zbyt stara, by używać jej z Aeonem, dlatego musisz skompilować nowszą wersję. Poniżej wyjaśniono dodatkowe kroki i został przetestowany na Raspberry Pi 2 z czystą instalacją minimalnego Raspbian Jessie.

* Jak wczesniej, `apt-get update && apt-get upgrade` aby zainstalować najnowsze oprogramowanie, i zwiększyć rozmiar pliku wymiany(swap)

```
	sudo /etc/init.d/dphys-swapfile stop  
	sudo nano /etc/dphys-swapfile  
	CONF_SWAPSIZE=2048  
	sudo /etc/init.d/dphys-swapfile start  
```

* Następnie zainstaluj zależności dla Aeon z wyjątkiem `libunwind` i `libboost-all-dev`

* Zainstaluj najnowszą wersję boost (może to wymagać najpierw wywołania `apt-get remove - purge libboost *`, aby usunąć poprzednią wersję, jeśli nie używasz czystej instalacji):
```
	cd  
	wget https://sourceforge.net/projects/boost/files/boost/1.64.0/boost_1_64_0.tar.bz2  
	tar xvfo boost_1_64_0.tar.bz2  
	cd boost_1_64_0  
	./bootstrap.sh  
	sudo ./b2  
```
* Poczekaj ~8 godzin
```
	sudo ./bjam cxxflags=-fPIC cflags=-fPIC -a install
```
* Poczekaj ~4 godzin

* Z tego miejsca postępuj zgodnie z [ogólnymi instrukcjami Raspberry Pi] (# on-the-raspberry-pi) z kroku „Sklonuj Aeon i checkout najnowszej wersji”.

#### Na Windows:

Pliki binarne dla systemu Windows są budowane w systemie Windows za pomocą zestawu narzędzi MinGW[Środowisko MSYS2] (https://www.msys2.org). Środowisko MSYS2 emuluje System POSIX. Toolchain działa w środowisku i *kompiluje krzyżowo* pliki binarne, które mogą działać poza środowiskiem jako zwykły aplikacja Windows

**Przygotowanie środowiska kompilacji**

* Pobierz i zainstaluj [instalator MSYS2] (https://www.msys2.org), pakiet 64-bitowy lub 32-bitowy, w zależności od systemu.
* Otwórz powłokę MSYS za pomocą skrótu `MSYS2 Shell`
* Aktualizuj pakiety za pomocą pacmana:  

        pacman -Syu  

* Wyjdź z powłoki MSYS używając Alt+F4  
* Edytuj właściwości skrótu `MSYS2 Shell` zmieniając" msys2_shell.bat "na" msys2_shell.cmd -mingw64 "dla 64-bitowych kompilacji lub" msys2_shell.cmd -mingw32 "dla kompilacji 32-bitowych
* Uruchom ponownie powłokę MSYS za pomocą zmodyfikowanego skrótu i zaktualizuj pakiety ponownie za pomocą pacmana:  

        pacman -Syu  


* Zainstaluj zależności:

    Aby zbudowac dla 64-bit Windows:

        pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium

    Aby zbudowac dla 32-bit Windows:

        pacman -S mingw-w64-i686-toolchain make mingw-w64-i686-cmake mingw-w64-i686-boost mingw-w64-i686-openssl mingw-w64-i686-zeromq mingw-w64-i686-libsodium

* Otwórz powłokę MingW za pomocą skrótu `MinGW-w64-Win64 Shell` w 64-bitowym systemie Windows
   lub skrót „MinGW-w64-Win64 Shell” w 32-bitowym systemie Windows. Zauważ, że jeśli jesteś
   z 64-bitowym systemem Windows będziesz mieć zarówno 64-bitowe, jak i 32-bitowe powłoki MinGW.

**Kolnowanie**

* Do konowania repozytorium, uruchom:

        git clone --recursive https://github.com/aeonix/aeon.git

**Budowanie**

* Wejdź do sklonowanego katalogu, uruchom:

        cd aeon

* Jeśli chcesz konkretnej [wersji / tagu] (https://github.com/aeonix/aeon/tags), zrób wersję git dla tej wersji na przykład. „v0.12.9.0-aeon”. Jeśli nie zależy Ci na wersji i chcesz po prostu plików binarnych z master, pomiń ten krok:

        git checkout v0.12.9.0-aeon

* Jeśli korzystasz z systemu 64-bitowego, uruchom:

        make release-static-win64

* Jeśli korzystasz z systemu 32-bitowego, uruchom:

        make release-static-win32

* Wynikowe pliki wykonywalne można znaleźć w `build/release/bin`

* **Opcjonalnie**: aby zbudować pliki binarne Windows odpowiednie do debugowania w systemie 64-bitowym, uruchom:

        make debug-static-win64

* **Opcjonalnie**: aby zbudować binaria systemu Windows odpowiednie do debugowania w systemie 32-bitowym, uruchom:

        make debug-static-win32

* Wynikowe pliki wykonywalne można znaleźć w `build/debug/bin`

### Na FreeBSD:

Projekt można zbudować od podstaw, postępując zgodnie z instrukcjami dla Linuksa powyżej. Jeśli uruchamiasz Aeon w jail, musisz dodać flagę: `allow.sysvipc = 1` do konfiguracji jail, w przeciwnym razie lmdb wyśle komunikat o błędzie:` Nie udało się otworzyć środowiska lmdb: funkcja nie została zaimplementowana`.

Oczekujemy, że w niedalekiej przyszłości dodamy Aeon do drzewa portów, co pomoże w zarządzaniu instalacjami przy użyciu portów lub pakietów.

### Na OpenBSD:

#### OpenBSD < 6.2

To zostało przetestowane na OpenBSD 5.8.

Musisz dodać kilka pakietów do swojego systemu. `pkg_add db cmake gcc gcc-libs g++ gtest`.

Pakiet doxygen i graphviz są opcjonalne i wymagają xbase.

Pakiet Boost zawiera błąd, który uniemożliwia poprawne budowanie librpc.a. Aby to naprawić, musisz zbudować wzmocnienie od podstaw. Postępuj zgodnie ze wskazówkami tutaj (w „Budowanie Boost”):
https://github.com/bitcoin/bitcoin/blob/master/doc/build-openbsd.md

Będziesz musiał dodać moduły serializacji, date_time i regex, aby zwiększyć, gdy budujesz tak, jak są potrzebne dla Aeon.

Do zbudowania: `env CC=egcc CXX=eg++ CPP=ecpp DEVELOPER_LOCAL_TOOLS=1 BOOST_ROOT=/path/to/the/boost/you/built make release-static-64`

#### OpenBSD >= 6.2

Musisz dodać kilka pakietów do swojego systemu. `pkg_add cmake zeromq libiconv`.

Pakiety doxygen i graphviz są opcjonalne i wymagają zestawu xbase.


Zbuduj bibliotekę Boost używając clang. Ten przewodnik pochodzi z: https://github.com/bitcoin/bitcoin/blob/master/doc/build-openbsd.md

Zakładamy, że kompilujesz z użytkownikiem innym niż root i masz włączone `doas`.

Uwaga: nie używaj pakietu boost dostarczonego przez OpenBSD, ponieważ instalujemy boost do `/ usr / local`.

```
# Tworzenie katalogu boost
mkdir ~/boost
cd ~/boost

# Pobierz źrodła boost
ftp -o boost_1_64_0.tar.bz2 https://netcologne.dl.sourceforge.net/project/boost/boost/1.64.0/boost_1_64_0.tar.bz2

# MUSI wyjść: (SHA256) boost_1_64_0.tar.bz2: OK
echo "7bcc5caace97baa948931d712ea5f37038dbb1c5d89b43ad4def4ed7cb683332 boost_1_64_0.tar.bz2" | sha256 -c
tar xfj boost_1_64_0.tar.bz2

# Pobierz i zastosuj poprawki poprawiające wymagane przez OpenBSD
ftp -o boost_test_impl_execution_monitor_ipp.patch https://raw.githubusercontent.com/openbsd/ports/bee9e6df517077a7269ff0dfd57995f5c6a10379/devel/boost/patches/patch-boost_test_impl_execution_monitor_ipp
ftp -o boost_config_platform_bsd_hpp.patch https://raw.githubusercontent.com/openbsd/ports/90658284fb786f5a60dd9d6e8d14500c167bdaa0/devel/boost/patches/patch-boost_config_platform_bsd_hpp

# MUSI wyjść: (SHA256) boost_config_platform_bsd_hpp.patch: OK
echo "1f5e59d1154f16ee1e0cc169395f30d5e7d22a5bd9f86358f738b0ccaea5e51d boost_config_platform_bsd_hpp.patch" | sha256 -c
# MUSI wyjść: (SHA256) boost_test_impl_execution_monitor_ipp.patch: OK
echo "30cec182a1437d40c3e0bd9a866ab5ddc1400a56185b7e671bb3782634ed0206 boost_test_impl_execution_monitor_ipp.patch" | sha256 -c

cd boost_1_64_0
patch -p0 < ../boost_test_impl_execution_monitor_ipp.patch
patch -p0 < ../boost_config_platform_bsd_hpp.patch

# Zacznij kompilacje boost
echo 'using clang : : c++ : <cxxflags>"-fvisibility=hidden -fPIC" <linkflags>"" <archiver>"ar" <striper>"strip"  <ranlib>"ranlib" <rc>"" : ;' > user-config.jam
./bootstrap.sh --without-icu --with-libraries=chrono,filesystem,program_options,system,thread,test,date_time,regex,serialization,locale --with-toolset=clang
./b2 toolset=clang cxxflags="-stdlib=libc++" linkflags="-stdlib=libc++" -sICONV_PATH=/usr/local
doas ./b2 -d0 runtime-link=shared threadapi=pthread threading=multi link=static variant=release --layout=tagged --build-type=complete --user-config=user-config.jam -sNO_BZIP2=1 -sICONV_PATH=/usr/local --prefix=/usr/local install
```

Zbuduj cppzmq

Zbuduj wiązania cppzmq.

Zakładamy, że kompilujesz z użytkownikiem innym niż root i masz włączone `doas`.

```
# Utwórz katalog komiplacji cppzmq
mkdir ~/cppzmq
cd ~/cppzmq

# Pobierz źródło cppzmq
ftp -o cppzmq-4.2.3.tar.gz https://github.com/zeromq/cppzmq/archive/v4.2.3.tar.gz

# MUSI wyjść: (SHA256) cppzmq-4.2.3.tar.gz: OK
echo "3e6b57bf49115f4ae893b1ff7848ead7267013087dc7be1ab27636a97144d373 cppzmq-4.2.3.tar.gz" | sha256 -c
tar xfz cppzmq-4.2.3.tar.gz

# Zacznij budować cppzmq
cd cppzmq-4.2.3
mkdir build
cd build
cmake ..
doas make install
```

Zbuduj Aeon: `env DEVELOPER_LOCAL_TOOLS=1 BOOST_ROOT=/usr/local make release-static`

### Na Solaris:

Nie można użyć domyślnego linkera Solaris, musisz zainstalować GNU ld, a następnie ręcznie uruchomić cmake ścieżką do swojej kopii GNU ld:

        mkdir -p build/release
        cd build/release
        cmake -DCMAKE_LINKER=/path/to/ld -D CMAKE_BUILD_TYPE=Release ../..
        cd ../..

Następnie możesz uruchomić jak zwykle.

### W systemie Linux dla Androida (za pomocą dockera):

        # Zbuduj obraz (dla ARM 32-bit)
        docker build -f utils/build_scripts/android32.Dockerfile -t aeon-android .
        # Zbuduj obraz (dla ARM 64-bit)
        docker build -f utils/build_scripts/android64.Dockerfile -t aeon-android .
        # Utwórz kontener
        docker create -it --name aeon-android aeon-android bash
        # Pobierz pliki binarne
        docker cp aeon-android:/src/build/release/bin .

### Budowanie przenośnych statycznie połączonych plików binarnych

Domyślnie, w dynamicznie lub statycznie połączonych kompilacjach, pliki binarne są ukierunkowane na określony procesor hosta, na którym kompilacja ma miejsce i nie są przenośne dla innych procesorów. Przenośne pliki binarne można budować przy użyciu następujących celów:

* ```make release-static-linux-x86_64``` zbuduj pliki binarne na Linux on x86_64 przenośny POSIX na system x86_64 procesorów
* ```make release-static-linux-i686``` zbuduj pliki binarne na Linux on x86_64 or i686 przenośny POSIX na system i686 procesorów
* ```make release-static-linux-armv8``` zbuduj pliki binarne na Linux przenośny POSIX na system armv8 procesorów
* ```make release-static-linux-armv7``` zbuduj pliki binarne na Linux przenośny POSIX na system armv7 procesorów
* ```make release-static-linux-armv6``` zbuduj pliki binarne na Linux przenośny POSIX na system armv6 procesorów
* ```make release-static-win64``` zbuduj pliki binarne na 64-bit Windows przenośny na 64-bit Windows system
* ```make release-static-win32``` zbuduj pliki binarne na 64-bit or 32-bit Windows przenośny na 32-bit Windows system

## Instalowanie Aeon z pakietu

**WYŁĄCZENIE ODPOWIEDZIALNOŚCI: Te pakiety nie są częścią tego repozytorium ani nie są utrzymywane przez współpracowników tego projektu i jako takie nie przechodzą przez ten sam proces przeglądu, aby zapewnić ich wiarygodność i bezpieczeństwo.**

Pakiety są dostępne dla

* (**DO ZROBIENIA**) ~Ubuntu i [snap wspierany](https://snapcraft.io/docs/core/install) systemy, za pośrednictwem społecznościowej kompilacji.~

        snap install aeon --beta

~Instalacja snap jest bardzo szybka. Snaps są bezpieczne. TSą odizolowane od wszystkich swoich zależności. Snaps są także automatycznie aktualizowane po wydaniu nowej wersji.~

* (**TODO**) ~Arch Linux (z [AUR](https://aur.archlinux.org/)):~
  - ~Stabilne wydanie: [`aeon`](https://aur.archlinux.org/packages/aeon)~
  - ~Bleeding edge: [`aeon-git`](https://aur.archlinux.org/packages/aeon-git)~

* (**DO ZROBIENIA**) ~Void Linux:~

        xbps-install -S aeon

* (**DO ZROBIENIA**) ~GuixSD~

        guix package -i aeon

* OS X przez [Homebrew](https://brew.sh)

        brew tap sammy007/aeon
        brew install aeon -v

* Docker

        # Buduj używając wszystkich dostępnych rdzeni
        docker build -t aeon .

        # lub zbuduj używając określonej liczby rdzeni (zmniejsz wymagania dotyczące pamięci RAM)
        docker build --build-arg NPROC=1 -t aeon .

        # albo uruchom na pierwszym planie
        docker run -it -v /aeon/chain:/root/.aeon -v /aeon/wallet:/wallet -p 11180:11180 aeon

        # lub w tle
        docker run -it -d -v /aeon/chain:/root/.aeon -v /aeon/wallet:/wallet -p 11180:11180 aeon

* Zbudowanie potrzebuje 3 GB miejsca.
* Poczekaj godzinę lub dłużej

Przygotowanie paczek dla ulubionej dystrybucji byłoby mile widzianym wkładem!

## Właczanie aeond

Kompilacja umieszcza plik binarny w podkatalogu `bin /` w katalogu kompilacji
z którego wywołano cmake (domyślnie root repozytorium). Uruchomić
na pierwszym planie:

    ./bin/aeond

Aby wyświetlić listę wszystkich dostępnych opcji, uruchom `./bin/aeond --help`. Opcje mogą być
określony w linii poleceń lub w pliku konfiguracyjnym przekazanym przez
argument `--config-file`. Aby określić opcję w pliku konfiguracyjnym, dodaj
wiersz ze składnią `argumentname = wartość`, gdzie` nazwa_ argumentu` to nazwa
argumentu bez początkowych myślników, na przykład `log-level = 1`.

Uruchamianie w tle:

    ./bin/aeond --log-file aeond.log --detach

Aby uruchomic jako systemd service, skopiuj
[aeond.service](utils/systemd/aeond.service) do `/etc/systemd/system/` i
[aeond.conf](utils/conf/aeond.conf) do `/etc/`. Przykład [example
service](utils/systemd/aeond.service) oznacza, że istnieje użytkownik `aeon`
a jego katalogiem domowym jest katalog danych określony w [example
config](utils/conf/aeond.conf).

Jeśli jesteś na Macu, może być konieczne dodanie opcji `--max-concurrency 1` do
aeon-wallet-cli, a może do aeond, jeśli się nie uruchomi poprawnie.

## Umiędzynarodowienie

Zobacz [README.i18n.md](README.i18n.md).

## Użycie sieci Tor

Podczas gdy Aeon nie jest przystosowany do integracji z Torem, może być użyty do owijania torsockami przez
ustawianie następujących parametrów konfiguracyjnych i zmiennych środowiskowych:

* `--p2p-bind-ip 127.0.0.1` w linii poleceń lub` p2p-bind-ip = 127.0.0.1` in
  aeond.conf, aby wyłączyć nasłuchiwanie połączeń na zewnętrznych interfejsach.
* `--no-igd` w linii poleceń lub` no-igd = 1` w aeond.conf, aby wyłączyć IGD
  (Negocjacja przekierowania portu UPnP), która nie ma sensu w przypadku Tora.
* `DNS_PUBLIC = tcp` lub` DNS_PUBLIC = tcp: // x.x.x.x` gdzie x.x.x.x jest adresem IP
  żądany serwer DNS, dla żądań DNS, aby przejść przez TCP, tak aby były kierowane
  przez Tora. Gdy IP nie jest określony, aeond używa domyślnej listy
  serwery zdefiniowane w [src / common / dns_utils.cpp] (src / common / dns_utils.cpp).
* `TORSOCKS_ALLOW_INBOUND = 1`, aby poinformować torsocks, aby pozwolił wiązać się z interfejsami
   akceptować połączenia z portfela. W niektórych systemach Linux torsocks
   domyślnie pozwala na powiązanie z localhost, więc ustawienie tej zmiennej jest tylko
   konieczne, aby umożliwić powiązanie z lokalnymi interfejsami LAN / VPN, aby umożliwić portfelom
   połącz ze zdalnymi hostami. W innych systemach może być potrzebny w lokalnych portfelach
   także.
* NIE przekazuj `--detach`, gdy przechodzisz przez torsocks z systemd, (zobacz
  [utils / systemd / aeond.service] (utils / systemd / aeond.service), aby uzyskać szczegółowe informacje).
* Jeśli używasz portfela z demonem Tora przez IP pętli zwrotnej (np. 127.0.0.1:9050),
  następnie użyj `--untrusted-daemon`, chyba że jest to twoja własna usługa ukryta.

Przykładowy wiersz poleceń, aby rozpocząć od Tora:

    DNS_PUBLIC=tcp torsocks aeond --p2p-bind-ip 127.0.0.1 --no-igd

### Uzycie Tor na Tails

TAILS jest dostarczany z bardzo restrykcyjnym zestawem reguł zapory. Dlatego potrzebujesz
aby dodać regułę, aby umożliwić to połączenie, oprócz informowania torsocków
zezwalaj na połączenia przychodzące. Pełny przykład:

    sudo iptables -I OUTPUT 2 -p tcp -d 127.0.0.1 -m tcp --dport 11181 -j ACCEPT
    DNS_PUBLIC=tcp torsocks ./aeond --p2p-bind-ip 127.0.0.1 --no-igd --rpc-bind-ip 127.0.0.1 \
        --data-dir /home/amnesia/Persistent/your/directory/to/the/blockchain

## Debugowanie

Ta sekcja zawiera ogólne instrukcje dotyczące debugowania nieudanych instalacji lub problemów napotkanych w Aeon. Najpierw upewnij się, że używasz najnowszej wersji zbudowanej z repozytorium Github.

### Uzyskiwanie śladów stosów i zrzutów rdzenia na systemach uniksowych

Zwykle używamy narzędzia `gdb` (debugger GNU), aby zapewnić funkcjonalność śledzenia stosu, oraz` ulimit`, aby zapewnić zrzuty rdzenia w kompilacjach, które ulegają awarii lub segfaultowi.

* Aby użyć gdb, aby uzyskać ślad stosu dla kompilacji, która utknęła w martwym punkcie:

Uruchom budowanie.

Po zatrzymaniu wprowadź następujące polecenie:

```
gdb /path/to/aeond `pidof aeond`
```

Wątek typu `zastosuj wszystkie bt` w gdb, aby uzyskać ślad stosu

* Jeśli jednak rdzeń zrzuca lub segfaults:

Wpisz `ulimit -c unlimited` w wierszu poleceń, aby włączyć nieograniczone rozmiary plików dla zrzutów rdzenia

Wpisz `echo core | sudo tee / proc / sys / kernel / core_pattern`, aby zatrzymać rdzenie przed przejęciem przez inne narzędzia

Uruchom budowanie.

Kiedy kończy się wyjściem zgodnym z liniami „Błąd segmentacji (core dumped)”, powinien istnieć plik zrzutu pamięci w tym samym katalogu co aeond. Może mieć nazwę tylko `core` lub` core.xxxx` z dołączonymi numerami.

Możesz teraz przeanalizować ten zrzut rdzenia za pomocą `gdb` w następujący sposób:

`gdb /path/to/aeond /path/to/dumpfile`

Wydrukuj ślad stosu za pomocą `bt`

* Aby uruchomic aeond z gdb:

Wpisz `gdb /path/to/aeond`

Przekaż opcje wiersza polecenia z opcją `--args`, a następnie odpowiednie argumenty

Wpisz `run`, aby uruchomić aeond

### Analiza uszkodzenia pamięci

Dostępne są dwa narzędzia:

* ASAN

Skonfiguruj Aeon za pomocą flagi cmake -D SANITIZE = ON, np:

    cd build/debug && cmake -D SANITIZE=ON -D CMAKE_BUILD_TYPE=Debug ../..

Następnie możesz normalnie uruchomić narzędzia aeon. Wydajność zazwyczaj spada o połowę.

* valgrind

Zainstaluj valgrind i uruchom jako `valgrind / path / to / aeond`. Będzie bardzo powolny.

### LMDB

Instrukcje dotyczące debugowania podejrzewanego uszkodzenia blockchain zgodnie z @HYC

W źródle LMDB znajduje się komenda `mdb_stat`, która może drukować statystyki dotyczące bazy danych, ale nie jest rutynowo budowana. Można to zbudować za pomocą następującego polecenia:

`cd ~/aeon/external/db_drivers/liblmdb && make`

Wyjście `mdb_stat -ea <ścieżka do blockchain dir>` wskaże niespójności w blokach, blokach_głównych i tabeli block_info.

Wyjście bloków `mdb_dump -s <ścieżka do blockchain dir>` i `mdb_dump -s block_info <ścieżka do blockchain dir>` jest przydatne do wskazania, czy bloki i blok_info zawierają te same klucze.

Te rekordy są zrzucane jako dane szesnastkowe, gdzie pierwsza linia jest kluczem, a druga linia jest danymi.
