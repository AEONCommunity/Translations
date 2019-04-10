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

Urheberrecht (c) 2014-2019, AEON, The Monero Project.   
Teilweises Urheberrecht (c) 2012-2013 The Cryptonote developers.

## Entwicklungsressourcen

- Website: [aeon.cash](https://aeon.cash)
- Bitcointalk: https://bitcointalk.org/index.php?topic=641696.0
- Reddit: https://www.reddit.com/r/Aeon
- GitHub: [https://github.com/aeonix/aeon](https://github.com/aeonix/aeon)
- IRC: [#aeon on Freenode](https://webchat.freenode.net/?randomnick=1&channels=%23aeon&prompt=1&uio=d4)
- Discord: https://discord.gg/TM8mEsx

## Reaktion auf Verwundbarkeiten

- Die Entdeckung einer Verwundbarkeit sollte an das Monero Projekt weitergeleitet werden, da die meiste Codebasis von AEON mit Monero geteilt ist
- Der [Prozess zur Reaktion auf Verwundbarkeiten](https://github.com/monero-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) fördert eine verantwortungsbewusste Offenlegung
- Das Monero Projekt ist außerdem verfügbar auf [HackerOne](https://hackerone.com/monero)

## Ankündigungen 

- Du kannst dich in unseren [eMail-Verteiler eintragen](https://docs.google.com/forms/d/e/1FAIpQLSci2UitA67N0W_xgSPLlGj6acGnTOtTdDR_ODZwXTHXZsWnCQ/viewform) um kritische Ankündigungen vom AEON team zu erhalten. Der Verteiler kann sehr nützlich sein um zu erfahren, wenn Sortwareupdates bereitstehen.

## Abdeckung

| Typ      | Status |
|-----------|--------|
| Lizenz   | [![License](https://img.shields.io/badge/license-BSD3-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Einleitung

AEON ist eine private, sichere, nicht nachverfolgbare und dezentralisierte digitale Währung. Du bist deine Bank, du kontrollierst dein Geld, niemand kann deine Überweisungen nachverfolgen, es sei denn du erlaubst es.

**Privatsphäre:** AEON verwendet ein kryptografisch sicheres System um dir das Verschicken und Empfangen von Geld zu erlauben, ohne dass deine Transaktionen auf einfach Art und Weise in der Blockchain (der Nachweis der Transaktionen, die jede kryptografische Währung verwendet) entdeckt werden kann. Dies stellt sicher, dass deine Einkäufe, Kassenzettel und alle Transaktionen absolut privat ablaufen.

**Sicherjeit:** Durch die Kraft eines verteilten Peer-to-Peer Netzwerkes ist jede Transaktion kryptografisch abgesichert. Individuelle Geldbörsen haben eine 25 Wörter lange *merkbare* Passphrase, welche nur ein einziges Mal angezeigt wird. Diese Passphrase sollte aufgeschrieben werden um die Geldbörse im Notfall wiederherzustellen. Die Datein der Geldbörse sind mit einem Passwort verschlüsselt (ein anderes als die 25 Wörter lange *merkbare* Passphrase) um sicher zu stellen, dass die Geldbörsen nutzlos sind, sollten die Dateien gestohlen werden.

**Nicht nachverfolgbar:** Indem die volle Stärke von Ringsignaturen, eine spezielle Art von Kryptografie, ausgenutzt wird stellt AEON sicher, dass Transaktionen nicht nachverfolgbar sind. Außerdem wird ein optionles Maß an Mehrdeutigkeit in jede Transaktion eingearbeitet, welches verhindert, dass sie zu einem bestimmten Computer oder zu einer Person zurück verfolgt werden kann.

## Über das Projekt

Dies ist die Kernimplementation für das [AEON Projekt](https://github.com/aeonix/aeon).
Sie ist quelloffen und komplett frei zu Verwenden, ohne irgendwelche Einschränkungen, ausgenommen solche, die in der Lizenz weiter unter beschrieben werden. Es existieren keinerlei Ristriktionen eine alternative Implementation von AEON zu erstellen, welche das Protokoll oder das Netzwerk in einer kompatiblen Art und Weise verwendet.

Wie bei vielen Entwicklungsprojekten, ist das Repository auf github als der "Staging"-Bereich für die letzten Änderungen anzusehen. Bevor Änderungen im Hauptrepository zusammengeführt werden, werden sie von den Entwicklern in ihren eigenen Abspaltungen getestet. Anschließend werden die Änderungen als pull-request (PR) verschickt und der Code wird von weiteren Mitwirkenden getestet und überprüft. Mit diesem Vorwort im Kopf sollte man genau überlegen, ob man den Code in einer produktiven Umgebung einsetzt, es sei denn im Repository ist ein Patch eingearbeitet, welcher ein Problem beseitigt, das einem vom produktiven Arbeiten abhält. Allgemein ist es besser eine Version zu verwenden, die als *stabil* veröffentlicht wurde.

**Jeder ist eingeladen zu AEON's Codebasis beizutragen!** Wenn du eine Verbesserung für oder Änderung am Code von AEON hast, kannst du ihn direkt an den *master* Zweig des Projekts schicken. In Fällen, in denen die Änderung relativ klein ist oder andere Teile des Codes nicht betroffen sind, wird sie sehr schnell von einem der Betreuer des Projekts eingefügt werden. Andererseits, wenn die Änderung sehr groß oder komplex ist wird erwartet, dass sie vorher oder direkt im *pull-request (PR)* diskutiert wird.


## Das Projekt unterstützen

AEON ist ein zu 100% Community finanziertes Unterfangen. Wenn du uns dabei beistehen willst, ist das Einfachste das Projekt finanziell zu unterstützen. AEON und Bitcoin Spenden können an **donate.aeon.cash** gesendet werden, wenn du eine Anwendung verwendest, die den [OpenAlias](https://openalias.org) Standard verwendet. Alternativ kann AEON direkt mit dem Kommando `donate` an die Spendenadresse gesendet werden (verwende den Befehl `help` in der Kommandozeile um weitere Informationen zu erhalten).

Die AEON Spendenadresse lautet: `WmsSWgtT1JPg5e3cK41hKXSHVpKW7e47bjgiKmWZkYrhSS5LhRemNyqayaSBtAQ6517eo5PtH9wxHVmM78JDZSUu2W8PqRiNs` (viewkey: `71bf19a7348ede17fa487167710dac401ef1556851bfd36b76040facf051630b`)

Die Bitcoin Spendenadresse ist: `12Cyjf3qV6qLyXdzpLSLPdRFPUVidvnzFM`

Die Entwicklung der Kernimplementation wurde bisher großzügig unterstützt von den folgenden Sponsoren:

[<img width="80" src="https://static.getmonero.org/images/sponsors/mymonero.png"/>](https://mymonero.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/kitware.png?1"/>](https://kitware.com)
[<img width="100" src="https://static.getmonero.org/images/sponsors/dome9.png"/>](https://dome9.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/araxis.png"/>](https://araxis.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/jetbrains.png"/>](https://www.jetbrains.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/navicat.png"/>](https://www.navicat.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/symas.png"/>](https://www.symas.com/)

Außerdem unterstützen einige AEON mining pools die Entwicklung mit einem Teil ihrer Einnahmen. Eine Liste kann in unserem [Bitcointalk Beitrag](https://bitcointalk.org/index.php?topic=641696.0) eingesehen werden.

## Lizenz

Siehe [LIZENZ](LICENSE).

## Zur Entwicklung beitragen

Wenn du uns mit der Entwicklung von AEON helfen willst, kannst du unsere Richtlinien dau [hier finden](CONTRIBUTING.md).

## Software Upgrades

AEON verwendet einen Softwareupgardemechanismus (harte Abspaltung, *hard fork*) um neue Funktionen einzubauen. Dies bedeutet, dass die Benutzer von AEON (Endanwender und Services) immer die neuste Version der Software verwenden sollten und diese regelmäßig Upgraden müssen. **Im Gegensatz zu Monero existiert allerdings kein fester Zeitplan für hard forks und der nächste Zeitpunkt wird vorher von der Gemeinschaft diskutiert.** Die benötigte Sorftware für das Upgrade wird rechtzeitig vor dem hard fork zur Verfügung gestellt. Das Repository auf github kann vor dem Upgrade auf die neuste Version überprüft werden.
Unterhalb sind die vergangenen Softwareupgrades und der ungefähre Zeitplan für das nächste Upgrade zu finden. Alle Daten sind als JAHR-MONAT-TAG angegeben.


| Blockhöhe des Softwareupgrades | Datum       | Version der Abspaltung | Minimale AEON Version | Empfohlene AEON Version | Details                                                                            |  
| ------------------------------ | -----------| ----------------- | ---------------------- | -------------------------- | ---------------------------------------------------------------------------------- |
| 592000                        | 2015-08-04 | v1 (außer der Reihe, Versionsnummer nicht erhöht)      | v0.9.0.0                 | v0.9.14.0                     | Blockzeit = 240 Sekunden, CryptoNight-Lite, geringere Herstellungspriorität für eine Ringgröße < 3       |
| 963500                        | 2018-06-03 | v7                | v0.12.0.0                 | v0.12.9.0-aeon                    | Anpassung an die letzte Monero-Codebasis, allerdings ohne RingCT, CryptoNight-Lite variant 1, limitierte Verwendung von Ringgröße 1 und Verbot von Ringgröße 2   |

## Kompilierung der AEON Kernimplementation vom Quellcode

### Abhängigkeiten

Die folgende Tabelle fasst die Werkzeuge und Bibliotheken zusammen, die benötigt werden um AEON zu Kompilieren. Einige der Bibliotheken werden zusammen mit AEON verbreitet. Grundsätzlich verwendet die Kernimplementation die Bibliothek, die das System bereitstellt und ignoriert andere Versionen. Wenn allerdings keine Bibliothek im System gefunden wird, wird die mit AEON verbreitete Version verwendet. Diese Bibliotheken werden außerdem für statisch verlinkte Kompilierungen verwendet, da Pakete oft geteilte (`so`) und keine statischen Bibliotheken (`.a`) verwenden.


| Abhängigkeit  | Min. Version  | verbreitet | Debian/Ubuntu pkg  | Arch pkg     | Fedora            | Optional | Grund        |
| ------------ | ------------- | -------- | ------------------ | ------------ | ----------------- | -------- | -------------- |
| GCC          | 4.7.3         | NEIN       | `build-essential`  | `base-devel` | `gcc`             | NEIN       |                |
| CMake        | 3.5           | NEIN       | `cmake`            | `cmake`      | `cmake`           | NEIN       |                |
| pkg-config   | any           | NEIN       | `pkg-config`       | `base-devel` | `pkgconf`         | NEIN       |                |
| Boost        | 1.58          | NEIN       | `libboost-all-dev` | `boost`      | `boost-devel`     | NEIN       | C++ Bibliothek  |
| OpenSSL      | basically any | NEIN       | `libssl-dev`       | `openssl`    | `openssl-devel`   | NEIN       | sha256 sum     |
| libzmq       | 3.0.0         | NEIN       | `libzmq3-dev`      | `zeromq`     | `cppzmq-devel`    | NEIN       | ZeroMQ Bibliothek |
| OpenPGM      | ?             | NEIN       | `libpgm-dev`       | `libpgm`     | `openpgm-devel`   | NEIN       | für ZeroMQ     |
| libnorm[2]   | ?             | NEIN       | `libnorm-dev`      |              |                   | JA      | für ZeroMQ     |
| libunbound   | 1.4.16        | JA      | `libunbound-dev`   | `unbound`    | `unbound-devel`   | NEIN       | DNS Auflösung   |
| libsodium    | ?             | NEIN       | `libsodium-dev`    | `libsodium`  | `libsodium-devel` | NEIN       | Kryptografie   |
| libunwind    | any           | NEIN       | `libunwind8-dev`   | `libunwind`  | `libunwind-devel` | JA      | Stapelverfolgung   |
| liblzma      | any           | NEIN       | `liblzma-dev`      | `xz`         | `xz-devel`        | JA      | für libunwind  |
| libreadline  | 6.3.0         | NEIN       | `libreadline6-dev` | `readline`   | `readline-devel`  | JA      | Eingabeinterpretation  |
| ldns         | 1.6.17        | NEIN       | `libldns-dev`      | `ldns`       | `ldns-devel`      | JA      | SSL Werkzeuge    |
| expat        | 1.1           | NEIN       | `libexpat1-dev`    | `expat`      | `expat-devel`     | JA      | XML Verarbeitung    |
| GTest        | 1.5           | JA      | `libgtest-dev`[1]  | `gtest`      | `gtest-devel`     | JA      | Testsuite     |
| Doxygen      | any           | NEIN       | `doxygen`          | `doxygen`    | `doxygen`         | JA      | Dokumentation  |
| Graphviz     | any           | NEIN       | `graphviz`         | `graphviz`   | `graphviz`        | JA      | Dokumentation  |
| pcsclite     | ?             | NEIN       | `libpcsclite-dev`  | ?            | `pcsc-lite pcsc-lite-devel` | NEIN | Ledger     |          


[1] Auf Debian/Ubuntu stellt `libgtest-dev` nur Quellen und Header bereit, diese Bibliothek muss daher manuell kompiliert werden. Das folgende Kommando kann dafür verwendet werden ```sudo apt-get install libgtest-dev && cd /usr/src/gtest && sudo cmake . && sudo make && sudo mv libg* /usr/lib/ ```
[2] `libnorm-dev` wird nur gebraucht wenn die zmq-Bibliothek mit `libnorm` kompiliert wurde, anderenfalls nicht. 

Du kannst diesen Befehl verwenden um alle Abhängigkeiten auf einmal zu installieren (Debian/Ubuntu): 
``` sudo apt update && sudo apt install build-essential cmake git pkg-config libboost-all-dev libssl-dev libzmq3-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libreadline6-dev libldns-dev libexpat1-dev doxygen graphviz libpcsclite-dev libpgm-dev```

### Herunterladen des Repository

Vervielfältige das Repository rekursiv um alle benötigten Module mit herunter zu laden:

`$ git clone --recursive https://github.com/aeonix/aeon`

Falls du das Repository schon heruntergeladen hast, kannst du es einfach updaten:

`$ cd aeon && git submodule init && git submodule update`

### Anleitung zum Kompilieren

AEON verwendet das CMake System mit einem übergeordnetem [Makefile](Makefile), welches alle Kommandos enthält.

#### Für Linux und OS X

* Installiere die Abhängigkeiten für AEON (siehe oben)
* Wechsle in den Stammordner des Quellcodes und gehe zur letzten Version. Starte die Kompilierung:

        cd aeon
        git checkout v0.12.9.0-aeon
        make

    *Optional*: Falls dein Computer mehrere Prozessorenkerne besitzt und über genügend RAM verfügt, kannst du auch `make -j<Anzahl der Kerne>` an Stelle von `make` verwenden. Damit das gut funktioniert, sollten ca. 2GB RAM pro Kern zur Verfügung stehen.

    *Amerkung*: Falls cmake die Datei `zmq.hpp` auf OS x nicht finden kann, kann `zmq.hpp` von https://github.com/zeromq/cppzmq heruntergeladen und in den lokalen Ordner `/usr/local/include` kopiert werden. Das sollte den Fehler beseitigen.
    
    *Anmerkung*: Diese Befehle werden die neuste *stabile* Version von AEON kompilieren. Möchtest du stattdessen neue Funktionen oder Code testen, kannst du ```git checkout master``` verwenden. Dies enthält die neusten Updates, die allerdings instabil oder inkompatibel mit älteren Versionen sein können. Das Testen dieser Version ist aber immer genre gesehen! 

* Die Ausführbare Datei kann im Ordner `build/release/bin` gefunden werden.

* Füge den Pfad `PATH="$PATH:$HOME/aeon/build/release/bin"` in die Datei `.profile` ein

* Führe AEON mit `aeond --detach` aus

* **Optional**: kompiliere die Testumgebung um neue Versionen zu verifizieren:

        make release-test

    *Anmerkung*: `core_tests` kann mehrer Stunden in Anspruch nehmen um fertiggestellt zu werden.

* **Optional**: kompiliere eine Version um Fehler zu finden (*debugging*):

         make debug

* **Optional**: kompiliere eine Version mit statisch verlinken Bibliotheken:

         make release-static

Abhängigkeiten müssen mit `-fPIC` kompiliert werden. Statische Bibliotheken sind dies oft nicht, daher müssen sie selbst kompiliert werden. Informationen dazu findest du in der jeweiligen Dokumentaion der Bibliotheken.

* **Optional**: Schreibe die Dokumentation nach `doc/html` (lasse `HAVE_DOT=YES` weg, wenn `graphviz` nicht installiert ist):

        HAVE_DOT=YES doxygen Doxyfile

#### Für einen Raspberry Pi

Getested auf einen Raspberry Pi Zero mit einer frischen Installation von Raspian Stretch (2017-09-07 oder später) von https://www.raspberrypi.org/downloads/raspbian/. Falls du Raspian Jessie verwendest, lies bitte die [folgende Sektion](#note-for-raspbian-jessie-users). 

* `apt-get update && apt-get upgrade` um die neusten Sorfwareupdates für Raspian zu installieren

* Installiere alle Abhängigkeiten aus der Tabelle unter dem Abschnitt *Debian*.

* Erhöhe die Größe des swap:
```	
	sudo /etc/init.d/dphys-swapfile stop  
	sudo nano /etc/dphys-swapfile  
	CONF_SWAPSIZE=2048
	sudo /etc/init.d/dphys-swapfile start  
```
* Falls du ein externes Laufwerk ohne zusätzliche Stromversorgung verwendest, solltest du sicher stellen, dass genügend Strom zur Verfügung steht um Probleme mit der Synchronisation zu vermeiden indem du die Zeile `max_usb_current=1` in` /boot/config.txt` einfügst.

* Wechsle in den Stammordner des Quellcodes und gehe zur letzten Version. Starte die Kompilierung:

        cd aeon
        git checkout v0.12.9.0-aeon
        make
	
* Kompiliere:
```
        make release
```
* Warte 4-6 Stunden.

* Die Ausführbare Datei kann im Ordner `build/release/bin` gefunden werden.

* Füge den Pfad `PATH="$PATH:$HOME/aeon/build/release/bin"` in die Datei `.profile` ein.

* Führe AEON mit `aeond --detach` aus.

* Du kannst anschliessend die Größe des swap wieder reduzieren und den Ordner `boost` löschen.

#### *Hinweis für Raspbian Jessie:*

Falls du ein älteres Raspian Jessie verwendest ist das Kompilieren von AEON ein wenige komplizierter. Die Version von `boost`, die für Jessie zur Verfügung steht ist zu alt um mit AEON verwendet zu werden. Daher muss eine neüre Version selbst kompiliert werden. Der folgende Abschnitt erklärt die Extraschritte und wurde auf einem Raspberry Pi 2 mit einer minimalen Raspian Jessie Installation getestet.

* `apt-get update && apt-get upgrade` um die neusten Sorfwareupdates für Jessie zu installieren

```	
	sudo /etc/init.d/dphys-swapfile stop  
	sudo nano /etc/dphys-swapfile  
	CONF_SWAPSIZE=2048  
	sudo /etc/init.d/dphys-swapfile start  
```

* Installiere alle Abhängigkeiten aus der Tabelle unter dem Abschnitt *Debian*, abgesehen von `libunwind` und `libboost-all-dev`

* Installiere die neuste Version von `boost` (unter Umständen muss vorher die alte Version mit `apt-get remove --purge libboost*` deinstalliert werden):
```
	cd  
	wget https://sourceforge.net/projects/boost/files/boost/1.64.0/boost_1_64_0.tar.bz2  
	tar xvfo boost_1_64_0.tar.bz2  
	cd boost_1_64_0  
	./bootstrap.sh  
	sudo ./b2  
```
* Warte ~8 Stunden
```
	sudo ./bjam cxxflags=-fPIC cflags=-fPIC -a install
```
* Warte ~4 Stunden

* Von hier an kannst du den Anweisungen für die [Installation auf einem Raspberry Pi folgen](#on-the-raspberry-pi). Starte bei dem Schritt " Wechsle in den Stammordner des Quellcodes und gehe zur letzten Version. Starte die Kompilierung".

#### Für Windows:

Ausführbare Datein für Windows werden auf Windows mit mit dem MinGW Werkzeug innerhalb von der [MSYS2 Umgebung](https://www.msys2.org) erstellt. 
MSYS2 emuliert ein POSIX System und MinGW läuft innerhalb dieser Umgebung, es *kreuzkompiliert* die ausführbaren Datein, so dass sie als reguläre Windowsanwendung laufen.


**Vorbereitung der Entwicklungsumgebung**

* Lade den [MSYS2 installer](https://www.msys2.org) entweder als 64-bit oder 32-bit Version herunter (abhängig von deinem System, die meisten Windows 10 Computer verwenden 64-bit) und installiere MSYS2
* öffne eine MSYS2 Konsole mit der `MSYS2 Shell` Verknüpfung
* Update auf die neuste Version mit pacman:

        pacman -Syu  

* Verlasse die Konsole über Alt+F4
* Durch einen Rechtsklick auf die MSYS2 Verknüpfung änderst du den Pfad von "msys2_shell.bat" nach "msys2_shell.cmd -mingw64" für 64-bit oder "msys2_shell.cmd -mingw32" für 32-bit
* öffne nun ein neues Konsolenfenster über die Verknüpfung und update nochmals mit pacman: 

        pacman -Syu  


* Installiere die Abhängigkeiten:

    Um für 64-bit Windows zu kompilieren:

        pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium

    Um für 32-bit Windows zu kompilieren:
 
        pacman -S mingw-w64-i686-toolchain make mingw-w64-i686-cmake mingw-w64-i686-boost mingw-w64-i686-openssl mingw-w64-i686-zeromq mingw-w64-i686-libsodium

* öffne nun eine MinGW Konsole über die entsprechenden 64-bit oder 32-bit Verknüpfung. Wenn du ein 64-bit Windows verwendest sind beide Versionen verfügbar, auf 32-bit Systemen nur die entsprechende 32-bit Version


**Herunterladen**

* Vervielfältige das Repository rekursiv um alle benötigten Module mit herunter zu laden:

        git clone --recursive https://github.com/aeonix/aeon.git

**Kompilieren**

* Wechsle in den Stammordner des Quellcodes:
	
        cd aeon

* **Optional**: Falls du eine bestimmte [Version](https://github.com/aeonix/aeon/tags) von AEON kompilieren willst, führe einen `git checkout` für diese Version aus:
	
        git checkout v0.12.9.0-aeon

* Auf einem 64-bit System verwende den Befehl um die Kompilierung zu staren:

        make release-static-win64

* Auf einem 32-bit System verwende den Befehl um die Kompilierung zu staren:

        make release-static-win32

* Die Ausführbare Datei kann im Ordner `build/release/bin` gefunden werden.

* **Optional**: Um Ausführbare Datein zur Fehlersuche zu erstellen, verwende diese Befehle:

        make debug-static-win64

oder

        make debug-static-win32

* Die Ausführbare Datei kann im Ordner `build/debug/bin` gefunden werden.

#### Für FreeBSD:

Das Projekt kann kompiliert werden, indem die Anleitung für Linux weiter oben verfolgt wird.
Falls du AEON in einem seperaten Container laufen lässt, muss der flag `allow.sysvipc=1` in die Containerkonfiguration eingefügt werden. Anderenfalls wird die LMDB den Fehler `Failed to open lmdb environment: Function not implemented` anzeigen.

Wir wollen AEON in der Zukunft in den ports Baum einfügen, was es einfacher gestalten wird die Installation via ports oder Paketen zu verwalten.

#### Für OpenBSD:

##### OpenBSD < 6.2

Die folgenden Schritte wurden auf OpenBSD 5.8 getestet.

* Du benötigst die Pakete `pkg_add db cmake gcc gcc-libs g++ gtest` um AEON kompilieren zu können.

* Die doxygen und graphviz Pakete sind optional, setzen aber die xbase Bibliothek voraus.

* Das Boost Paket enthält einen Fehler, der `librpc.a` davon abhält erfolgreich zu kompilieren. Um dies zu umgehen muss Boost selst neu kompiliert werden, die Anleitung dazu kann unter https://github.com/bitcoin/bitcoin/blob/master/doc/build-openbsd.md gefunden werden.

* Bevor die Kompilierung gestartet werden kannc müssen die serialization, date_time, und regex Module zu Boost hinzugefügt werden, da sie von AEON gebraucht wreden

* Zum Kompilieren führe den Befehl `env CC=egcc CXX=eg++ CPP=ecpp DEVELOPER_LOCAL_TOOLS=1 BOOST_ROOT=/path/to/the/boost/you/built make release-static-64` aus.

##### OpenBSD >= 6.2

* Du benötigst die Pakete `pkg_add cmake zeromq libiconv` um AEON kompilieren zu können.

* Die doxygen und graphviz Pakete sind optional, setzen aber die xbase Bibliothek voraus.

* Die Boost Bibliothek muss selbst kompiliert werden mit clang. Die anleitung im Folgenden stammt von: https://github.com/bitcoin/bitcoin/blob/master/doc/build-openbsd.md

    Wir setzen voraus, dass ein nicht-Root Benutzer verwendet wird und `doas` eingeschaltet ist.

    **Anmerkung**: Bitte verwende nicht das Boost Paket, welches von OpenBSD bereitgestellt wird, da wir boost nach `/usr/local` installieren.

```
# Erstelle einen Ordner für Boost
mkdir ~/boost
cd ~/boost

# Lade den boost Quellcode herunter
ftp -o boost_1_64_0.tar.bz2 https://netcologne.dl.sourceforge.net/project/boost/boost/1.64.0/boost_1_64_0.tar.bz2 

# überprüfe die Ausgabe: (SHA256) boost_1_64_0.tar.bz2: OK
echo "7bcc5caace97baa948931d712ea5f37038dbb1c5d89b43ad4def4ed7cb683332 boost_1_64_0.tar.bz2" | sha256 -c
tar xfj boost_1_64_0.tar.bz2

# Lade die neusten Patches für Boost auf OpenBSD herunter
ftp -o boost_test_impl_execution_monitor_ipp.patch https://raw.githubusercontent.com/openbsd/ports/bee9e6df517077a7269ff0dfd57995f5c6a10379/devel/boost/patches/patch-boost_test_impl_execution_monitor_ipp
ftp -o boost_config_platform_bsd_hpp.patch https://raw.githubusercontent.com/openbsd/ports/90658284fb786f5a60dd9d6e8d14500c167bdaa0/devel/boost/patches/patch-boost_config_platform_bsd_hpp

# überprüfe die Ausgabe: (SHA256) boost_config_platform_bsd_hpp.patch: OK
echo "1f5e59d1154f16ee1e0cc169395f30d5e7d22a5bd9f86358f738b0ccaea5e51d boost_config_platform_bsd_hpp.patch" | sha256 -c

# überprüfe die Ausgabe: (SHA256) boost_test_impl_execution_monitor_ipp.patch: OK
echo "30cec182a1437d40c3e0bd9a866ab5ddc1400a56185b7e671bb3782634ed0206 boost_test_impl_execution_monitor_ipp.patch" | sha256 -c

cd boost_1_64_0
patch -p0 < ../boost_test_impl_execution_monitor_ipp.patch
patch -p0 < ../boost_config_platform_bsd_hpp.patch

# Kompiliere Boost
echo 'using clang : : c++ : <cxxflags>"-fvisibility=hidden -fPIC" <linkflags>"" <archiver>"ar" <striper>"strip"  <ranlib>"ranlib" <rc>"" : ;' > user-config.jam
./bootstrap.sh --without-icu --with-libraries=chrono,filesystem,program_options,system,thread,test,date_time,regex,serialization,locale --with-toolset=clang
./b2 toolset=clang cxxflags="-stdlib=libc++" linkflags="-stdlib=libc++" -sICONV_PATH=/usr/local
doas ./b2 -d0 runtime-link=shared threadapi=pthread threading=multi link=static variant=release --layout=tagged --build-type=complete --user-config=user-config.jam -sNO_BZIP2=1 -sICONV_PATH=/usr/local --prefix=/usr/local install
```

* Kompilieren von cppzmq und den cppzmq Anbindungen.

    Wir setzen voraus, dass ein nicht-Root Benutzer verwendet wird und `doas` eingeschaltet ist.

```
# Erstelle einen Ordner für cppzmq
mkdir ~/cppzmq
cd ~/cppzmq

# Lade den cppzmq Quellcode herunter
ftp -o cppzmq-4.2.3.tar.gz https://github.com/zeromq/cppzmq/archive/v4.2.3.tar.gz

# überprüfe die Ausgabe: (SHA256) cppzmq-4.2.3.tar.gz: OK
echo "3e6b57bf49115f4ae893b1ff7848ead7267013087dc7be1ab27636a97144d373 cppzmq-4.2.3.tar.gz" | sha256 -c
tar xfz cppzmq-4.2.3.tar.gz

# Kompiliere cppzmq
cd cppzmq-4.2.3
mkdir build
cd build
cmake ..
doas make install
```

* Kompiliere Aeon: `env DEVELOPER_LOCAL_TOOLS=1 BOOST_ROOT=/usr/local make release-static`

#### Für Solaris:

* Der Standard Solaris Compiler kann leider nicht verwendet werden. Du musst `GNU ld` installieren und `cmake` manuell ausführen mit dem Pfad zu `GNU ld`:

        mkdir -p build/release
        cd build/release
        cmake -DCMAKE_LINKER=/Pfad/zu/ld -D CMAKE_BUILD_TYPE=Release ../..
        cd ../..

* Anschließend kann `make` normal verwendet werden.

#### Für Android (mit Hilfe von Docker):

        # Kompiliere für ARM 32-bit
        docker build -f utils/build_scripts/android32.Dockerfile -t aeon-android .

        # Kompiliere für ARM 64-bit
        docker build -f utils/build_scripts/android64.Dockerfile -t aeon-android .

        # Erstelle den Docker Container
        docker create -it --name aeon-android aeon-android bash

        # Lade die ausführbaren Datein
        docker cp aeon-android:/src/build/release/bin .

### Kompilierung von statisch verlinkten, partablen Anwendungen

Normalerweise sind sowohl dynamisch als auch statisch verlinkte Anwendungen spezifisch für einen Prozessortyp und können nicht auf andere Prozessoren übertragen werden. Statisch verlinkte, portable Anwendungen umgehen dieses Problem:

* ```make release-static-linux-x86_64``` kompiliere ausführbare Datein auf Linux mit einem x86_64 Prozessor, die transportierbar sind für alle POSIX Systeme mit x86_64 Prozessoren
* ```make release-static-linux-i686``` kompiliere ausführbare Datein auf Linux mit einem x86_64 oder i686 Prozessor, die transportierbar sind für alle POSIX Systeme mit i686 Prozessoren
* ```make release-static-linux-armv8``` kompiliere ausführbare Datein auf Linux, die transportierbar sind für alle POSIX Systeme mit armv8 Prozessoren
* ```make release-static-linux-armv7``` kompiliere ausführbare Datein auf Linux, die transportierbar sind für alle POSIX Systeme mit armv7 Prozessoren
* ```make release-static-linux-armv6``` kompiliere ausführbare Datein auf Linux, die transportierbar sind für alle POSIX Systeme mit armv6 Prozessoren
* ```make release-static-win64``` kompiliere ausführbare Datein auf Windows 64-bit, die transportierbar sind für alle 64-bit Windows Systeme
* ```make release-static-win32``` kompiliere ausführbare Datein auf Windows 32-bit oder 64-bit, die transportierbar sind für alle 32-bit Windows Systeme

## AEON aus einem Paket installieren

**Warnung: Diese Pakete sind nicht Teil des Repository und werden nicht von den Projektbetreuern verwaltet. Daher durchlaufen sie nicht den gleichen überwchungsprozess um ihre Glaubwürdigkeit und Sicherheit zu überprüfen.**

Pakete sind verfügbar für:

* (**ZU TUN**) ~Ubuntu und andere Linuxdistributionen, die [Snap](https://snapcraft.io/docs/core/install) verwenden.~

        snap install aeon --beta

~Die Installation von Snaps geht sehr schnell. Snaps sind sicher, da sie isoliert vom System laufen zusammen mit all ihren Abhängigkeiten. Außerdem verfügen Snaps über ein automatisches Update.~

* (**ZU TUN**) ~Arch Linux (via [AUR](https://aur.archlinux.org/)):~
  - ~Stabile Version: [`aeon`](https://aur.archlinux.org/packages/aeon)~
  - ~Testversion: [`aeon-git`](https://aur.archlinux.org/packages/aeon-git)~

* (**ZU TUN**) ~Void Linux:~

        xbps-install -S aeon

* (**ZU TUN**) ~GuixSD~

        guix package -i aeon

* OS X mit [Homebrew](https://brew.sh)

        brew tap sammy007/aeon
        brew install aeon -v

* Docker

        # Kompiliere mit allen verfügbaren Prozessorkernen
        docker build -t aeon .

        # oder mit einer bestimmten Anzahl an Kernen (hier 1), was weniger RAM benötigt
        docker build --build-arg NPROC=1 -t aeon .
     
        # AEON im Vordergrund laufen lassen
        docker run -it -v /aeon/chain:/root/.aeon -v /aeon/wallet:/wallet -p 11180:11180 aeon

        # oder im Hintergrund
        docker run -it -d -v /aeon/chain:/root/.aeon -v /aeon/wallet:/wallet -p 11180:11180 aeon

    * Benötigt ca. 3GB Speicherplatz.
    * Der Prozess dauert eine Stunde oder länger.

**Das Bereitstellen für deine favorisierte Distribution ist eine willkommene Unterstützung!**

## aeond ausführen

Die ausführbare Datei `aeond` befindet sich im Unterordner `bin` des Verzeichnisses, in dem AEON kompliliert wurde. Um aeond im Vordergrund laufen lassen, verwende:

    ./bin/aeond

Um alle verfügbaren Optionen anzuzeigen kannst du `./bin/aeond --help` aufrufen. Die Optionen können entweder einzeln in der Kommandozeile angehängt werden oder über eine Konfigurationsdatei aufgerufen werden. Verwende dazu das Argument `--config-file /Pfad/zur/Datei`. In der Konfigurationsdatei werden die Argumente folgendermaßen eingetragen:

    `argumentname1=value`
    `argumentname2=value`

Es werden keine vorangestellen Striche verwendet.

Um aeond im Hintergrund laufen lassen, verwende:

    ./bin/aeond --log-file aeond.log --detach

Um aeond als Systemservice laufen zu lassen, kopiere [aeond.service](utils/systemd/aeond.service) nach `/etc/systemd/system/` und [aeond.conf](utils/conf/aeond.conf) nach `/etc/`.
Der [Service](utils/systemd/aeond.service) nimmt an, dass der Benutzer `aeon` existiert und sein persönlicher Ordner der Datenordner ist, der in der [Konfiguration](utils/conf/aeond.conf).

Falls aeond auf OS X vermehrt abstürtzt, kannst du die option `--max-concurrency 1` für aeond und aeon-wallet-cli verwenden.

## Internationalisierung

Siehe [README.i18n.md](README.i18n.md).

## Verwendung von Tor

Zwar wurde AEON nicht entwickelt um mit Tor integriert zu werden, es kann aber mit Hilfe von Torsocks dazu gebracht werden. Dazu müssen die folgenden Argumente für aeond verwendet werden:

* `--p2p-bind-ip 127.0.0.1` in der Kommandozeile oder `p2p-bind-ip=127.0.0.1` in aeond.conf um Verbindungen von außen zu verhindern.
* `--no-igd` in der Kommandozeile oder `no-igd=1` in aeond.conf um IGD (UPnP port forwarding) zu deaktivieren, was für Tor nicht benötigt wird. 
* `DNS_PUBLIC=tcp` oder `DNS_PUBLIC=tcp://x.x.x.x` wobei x.x.x.x der IP Adresse des gewünschen DNS entspricht, damit DNS Anfragen über TCP und damit über Tor laufen. Wird die IP nicht spezifiziert verwendet aeond eine voreingestellte Serverliste die in [src/common/dns_utils.cpp](src/common/dns_utils.cpp) definiert ist.
* `TORSOCKS_ALLOW_INBOUND=1` um Torsocks zu signalisieren, dass aeond auf Verbindungen z.B. von einer Geldbörse wartet. Einige Linuxsystemen erlauben die Verbindung von lokalen Geräten auch ohne diese Einstellung. Sie ist daher unter Umständen nur nötig um externe Verbindungen zuzulassen. i
* Das Argument `--detach` sollte **nicht** verwendet werden wenn aeond als Systemservice über Torsocks läuft. Siehe [utils/systemd/aeond.service](utils/systemd/aeond.service) für mehr Details.
* Falls du deine Geldbörse mit dem Tor Service über eine Schleifenschaltung IP (*loopback IP*, z.B. 127.0.0.1:9050) verbindest, sollte `--untrusted-daemon` verwendet werden, es sei denn der Tor Service ist dein eigener versteckter Service.

Beispiel um aeond über Torsocks zu starten:

    `DNS_PUBLIC=tcp torsocks aeond --p2p-bind-ip 127.0.0.1 --no-igd`

### Verwendung von "Tor on Tails"

TAILS kommt mit sehr restriktiven Firewalleinstellungen. Daher muss eine extra Regel aufgestellt werden um einkommende Verbindungen zu erlauben (zusätzlich zu der Einstellung um einkommende Verbindungen über Torsocks zu erlauben).
Beispiel:

    sudo iptables -I OUTPUT 2 -p tcp -d 127.0.0.1 -m tcp --dport 11181 -j ACCEPT
    DNS_PUBLIC=tcp torsocks ./aeond --p2p-bind-ip 127.0.0.1 --no-igd --rpc-bind-ip 127.0.0.1 \
        --data-dir /home/amnesia/Persistent/your/directory/to/the/blockchain

## Fehlersuche (Debugging)

Dieser Abschnitt enthält generelle Informationen um Probleme ausfindig zu machen, die mit fehlgeschlagenen Installationen oder anderen Problemen von AEON auftreten könnten. Zuerst solltest du allerdings sicher stellen, dass du die neuste Version von AEON von Github herunterlädst und kompilierst.

### Erhalten von Stack-Traces und Core-Dumps auf Unix-Systemen

Wir verwenden die Werkzeuge `gdb` (GNU debugger) um Stack-Traces zu erstellen und `ulimit` für Core-Dumps, mit Versionen von AEON, die instabil laufen.

* Um `gdb` für einen Stack-Trace von einer AEON Version zu verwenden, die nicht mehr weiter läuft:

    * Starte die AEON Version.

    * Wenn sie nicht mehr weiter läuft, verwende diesen Befehl in der Kommandozeile:

    ```
    gdb /Pfad/zu/aeond `pid of aeond` 
    ```

    * Innerhalb von gdb tippe den folgenden Befehl um einen Stack-Trace zu erhalten:

    `thread apply all bt`


* Für Core-Dumps oder bei Segmentierungsfehlern:

    * In der Kommandozeile, verwende `ulimit -c unlimited` um unbegrenzte Dateigrößen für Core-Dumps zu aktivieren

    * Tippe `echo core | sudo tee /proc/sys/kernel/core_pattern` um zu verhindern, dass Prozessorkerne von anderen Anwendungen verwendet werden.

    * Starte die AEON Version.

    * Wenn sie abstürzt mit der Fehlermeldung *Segmentation fault (core dumped)*, eine Datei mit dem Core-Dump sollte im gleichen Ordner wie aeond erstellt worden sein. Der Name der Datei lautet entweder `core` oder `core.xxxx`, wobei xxxx Zahlen sind.
    
    * Nun kann der Core-Dump mit `gdb` analysiert werden:

        * `gdb /Pfad/zu/aeond /Pfad/zu/core-dump`

    * Zur Ausgabe der Traces kann `bt` verwendet werden


* Um aeond innerhalb von `gdb` zu starten, verwende:

 `gdb /path/to/aeond`

* Um Kommandozeilenargumente einzugeben verwende `--args` gefolgt von der relevanten Argumenten

* Anschließend, tippe `run` um aeond zu starten

### Analyse von Speicherkorruption

Es gibt zwei Werkzeuge dafür:

* ASAN

Kompiliere AEON mit dem CMake flag -D SANITIZE=ON:

    cd build/debug && cmake -D SANITIZE=ON -D CMAKE_BUILD_TYPE=Debug ../..

Anschließend kann AEON normal verwendet werden, die Leistung reduziert sich aber auf ca. die Hälfte.

* valgrind

Installiere valgrind führe es mit `valgrind /pfad/zu/aeond` aus. Es wird allerdings sehr langsam laufen.

### LMDB

Anleitung für die Fehlersuche in der Blockchain-Datei nach dem Benutzer @HYC

Es gibt ein `mdb_stat` Kommando im LMDB  Quelltext, welches Statistiken über die Datenbank ausgeben kann, allerdings wird es normalerweise nicht mit kompiliert. Dies kann mit dem Befehl

`cd ~/aeon/external/db_drivers/liblmdb && make`

gemacht werden.

Die Ausgabe der Befehle `mdb_dump -s blocks <pfad/zum/Blockchain-Ordner>` und `mdb_dump -s block_info <pfad/zum/Blockchain-Ordner>` kann verwendet werden um herauszufinden ob Blocks und block_info die gleichen Schlüssel enthalten.
Die Ausgabe wird im HEX-Format in ein Textfile geschrieben, die erste Zeile entspricht dem Schlüssel und die zweite Zeile enthält die Daten.
