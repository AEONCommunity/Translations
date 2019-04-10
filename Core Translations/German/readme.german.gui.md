# Aeon GUI

Urheberrecht (c) 2014-2019, AEON, The Monero Project

## Entwicklungsressourcen

- Website: [aeon.cash](http://aeon.cash)
- Bitcointalk: https://bitcointalk.org/index.php?topic=641696.0
- Reddit: https://www.reddit.com/r/Aeon
- Github: [https://github.com/aeonix/aeon-gui](https://github.com/aeonix/aeon-gui)
- IRC: [#aeon on Freenode](https://webchat.freenode.net/?randomnick=1&channels=%23aeon&prompt=1&uio=d4)
- Discord: https://discord.gg/TM8mEsx

## Reaktion auf Verwundbarkeiten

- Die Entdeckung einer Verwundbarkeit sollte an das Monero Projekt weitergeleitet werden, da die meiste Codebasis von AEON mit Monero geteilt ist
- Der [Prozess zur Reaktion auf Verwundbarkeiten](https://github.com/monero-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) fördert eine verantwortungsbewusste Offenlegung
- Das Monero Projekt ist ausserdem verfügbar auf [HackerOne](https://hackerone.com/monero)

## Einleitung

AEON ist eine private, sichere, nicht nachverfolgbare und dezentralisierte digitale Währung. Du bist deine Bank, du kontrollierst dein Geld, niemand kann deine Überweisungen nachverfolgen, es sei denn du erlaubst es.

**Privatsphäre:** AEON verwendet ein kryptografisch sicheres System um dir das Verschicken und Empfangen von Geld zu erlauben, ohne dass deine Transaktionen auf einfach Art und Weise in der Blockchain (der Nachweis der Transaktionen, die jede kryptografische Währung verwendet) entdeckt werden kann. Dies stellt sicher, dass deine Einkäufe, Kassenzettel und alle Transaktionen absolut privat ablaufen.

**Sicherheit:** Durch die Kraft eines verteilten Peer-to-Peer Netzwerkes ist jede Transaktion kryptografisch abgesichert. Individuelle Geldbörsen haben eine 25 Wörter lange *merkbare* Passphrase, welche nur ein einziges Mal angezeigt wird. Diese Passphrase sollte aufgeschrieben werden um die Geldbörse im Notfall wiederherzustellen. Die Datein der Geldbörse sind mit einem Passwort verschlüsselt (ein anderes als die 25 Wörter lange *merkbare* Passphrase) um sicher zu stellen, dass die Geldbörsen nutzlos sind, sollten die Dateien gestohlen werden.

**Nicht nachverfolgbar:** Indem die volle Stärke von Ringsignaturen, eine spezielle Art von Kryptografie, ausgenutzt wird stellt AEON sicher, dass Transaktionen nicht nachverfolgbar sind. Ausserdem wird ein optionles Maß an Mehrdeutigkeit in jede Transaktion eingearbeitet, welches verhindert, dass sie zu einem bestimmten Computer oder zu einer Person zurück verfolgt werden kann.


## Über das Projekt

Dies ist die grafische Benutzeroberfläche (graphical user interface, GUI) für das [AEON Projekt](https://github.com/aeonix/aeon).
Sie ist quelloffen und komplett frei zu Verwenden, ohne irgendwelche Einschränkungen, ausgenommen solche, die in der Lizenz weiter unter beschrieben werden. Es existieren keinerlei Ristriktionen eine alternative Implementation von AEON zu erstellen, welche das Protokoll oder das Netzwerk in einer kompatiblen Art und Weise verwendet.

Wie bei vielen Entwicklungsprojekten, ist das Repository auf github als der "Staging"-Bereich für die letzten Änderungen anzusehen. Bevor Änderungen im Hauptrepository zusammengeführt werden, werden sie von den Entwicklern in ihren eigenen Abspaltungen getestet. Anschliessend werden die Änderungen als pull-request (PR) verschickt und der Code wird von weiteren Mitwirkenden getestet und überprüft. Mit diesem Vorwort im Kopf sollte man genau überlegen, ob man den Code in einer produktiven Umgebung einsetzt, es sei denn im Repository ist ein Patch eingearbeitet, welcher ein Problem beseitigt, das einem vom produktiven Arbeiten abhält. Allgemein ist es besser eine Version zu verwenden, die als *stabil* veröffentlicht wurde.


## Das Projekt unterstützen

AEON ist ein zu 100% Community finanziertes Unterfangen. Wenn du uns dabei beistehen willst, ist das Einfachste das Projekt finanziell zu unterstützen. AEON und Bitcoin Spenden können an **donate.aeon.cash** gesendet werden, wenn du eine Anwendung verwendest, die den [OpenAlias](https://openalias.org) Standard verwendet.

Die AEON Spendenadresse lautet: `WmsSWgtT1JPg5e3cK41hKXSHVpKW7e47bjgiKmWZkYrhSS5LhRemNyqayaSBtAQ6517eo5PtH9wxHVmM78JDZSUu2W8PqRiNs` (viewkey: `71bf19a7348ede17fa487167710dac401ef1556851bfd36b76040facf051630b`)

Die Bitcoin Spendenadresse ist: `12Cyjf3qV6qLyXdzpLSLPdRFPUVidvnzFM`

Die Entwicklung der GUI wurde bisher großzügig unterstützt von den folgenden Sponsoren:

[<img width="80" src="https://static.getmonero.org/images/sponsors/mymonero.png"/>](https://mymonero.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/kitware.png?1"/>](http://kitware.com)
[<img width="100" src="https://static.getmonero.org/images/sponsors/dome9.png"/>](http://dome9.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/araxis.png"/>](http://araxis.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/jetbrains.png"/>](http://www.jetbrains.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/navicat.png"/>](http://www.navicat.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/symas.png"/>](http://www.symas.com/)

Ausserdem unterstützen einige AEON mining pools die Entwicklung mit einem Teil ihrer Einnahmen. Eine Liste kann in unserem [Bitcointalk Beitrag](https://bitcointalk.org/index.php?topic=641696.0) eingesehen werden.

## Lizenz

Siehe [LIZENZ](LICENSE).

## AEON GUI von einem Package installieren

(**ZU TUN**) ~Packages sind verfügbar für~

* ~Arch Linux via AUR: [aeon-wallet-qt](https://aur.archlinux.org/packages/aeon-wallet-qt/)~
* ~Void Linux: xbps-install -S aeon-core~
* ~GuixSD: guix package -i aeon-core~

Das Bereitstellen für deine favorisierte Linuxdistribution ist eine willkommene Unterstützung!

## Kompilierung der AEON GUI vom Quellcode

### Für Linux:

(Getestet auf Ubuntu 17.10 x64, Ubuntu 18.04 x64 and Gentoo x64)

1. Installiere die Abhängigkeiten für AEON

  - Für Debian Distributionen (Debian, Ubuntu, Mint, Tails...)

	`sudo apt install build-essential cmake libboost-all-dev miniupnpc libunbound-dev graphviz doxygen libunwind8-dev pkg-config libssl-dev libzmq3-dev libsodium-dev libhidapi-dev`

  - Für Gentoo

	`sudo emerge app-arch/xz-utils app-doc/doxygen dev-cpp/gtest dev-libs/boost dev-libs/expat dev-libs/openssl dev-util/cmake media-gfx/graphviz net-dns/unbound net-libs/ldns net-libs/miniupnpc net-libs/zeromq sys-libs/libunwind dev-libs/libsodium dev-libs/hidapi`

2. Installieren von Qt:

  *Anmerkung*: Qt 5.7 ist die niedrigste Version, die für die GUI benötigt wird. Das bedeutet, dass **manche** Distributionen obsolet sind (wie z.B. Ubuntu 16.x or Linux Mint 18.x). Die GUI kann weiterhin kompiliert werden, wenn ein [offizieller Qt Release](https://wiki.qt.io/Install_Qt_5_on_Ubuntu) installiert wird, allerdings wird dies nicht offiziell unterstützt.
  
  - Für Ubuntu 17.10+

    `sudo apt install qtbase5-dev qt5-default qtdeclarative5-dev qml-module-qtquick-controls qml-module-qtquick-controls2 qml-module-qtquick-dialogs qml-module-qtquick-xmllistmodel qml-module-qt-labs-settings qml-module-qt-labs-folderlistmodel qttools5-dev-tools qml-module-qtquick-templates2`

  - Für Gentoo

    `sudo emerge dev-qt/qtcore:5 dev-qt/qtdeclarative:5 dev-qt/qtquickcontrols:5 dev-qt/qtquickcontrols2:5 dev-qt/qtgraphicaleffects:5`

  - Optional: Komplilierung mit dem flag `WITH_SCANNER`

    - Für Ubuntu

      `sudo apt install qtmultimedia5-dev qml-module-qtmultimedia libzbar-dev`

    - Für Gentoo

      Die *qml* USE flag muss aktiviert sein!

      `emerge dev-qt/qtmultimedia:5 media-gfx/zbar`


3. Herunterladen des Repository

    `git clone https://github.com/aeonix/aeon-gui.git`

4. Komplilieren

    ```
    cd aeon-gui
    QT_SELECT=5 ./build.sh
    ```

Die Ausführbare Datei kann im Ordner `build/release/bin` gefunden werden.

### Auf OS X:

1. Installieren von Xcode vom AppStore

2. Installieren von [homebrew](http://brew.sh/)

3. Installiere die Abhängigkeiten für [AEON](https://github.com/aeonix/aeon)

  `brew install boost --c++11`

  `brew install openssl` - um die openssl header zu installieren

  `brew install pkgconfig`

  `brew install cmake`

  `brew install zeromq`

  *Anmerkung*: Falls cmake die Datei `zmq.hpp` auf OS x nicht finden kann, kann `zmq.hpp` von https://github.com/zeromq/cppzmq heruntergeladen und in den lokalen Ordner `/usr/local/include` kopiert werden. Das sollte den Fehler beseitigen.

4. Installieren von Qt

  `brew install qt5`  (alternativ kann Qt 5.8+ von [qt.io](https://www.qt.io/download-open-source/) heruntergeladen werden)

  Falls du eine ältere Version von Qt via homebrew installiert hast, kann homebrew gezwungen werden Qt 5.x zu installieren:
  
  `brew link --force --overwrite qt5`

5. Hinzufügen des Qt Ordners zu dem lokalen PATH

    Beispiel: `export PATH=$PATH:$HOME/Qt/5.8/clang_64/bin`

    Das sollte der Pfad sein, in welchem Qt 5.x auf **deinem** System installiert ist.

6. Herunterladen des Repository

  `git clone https://github.com/aeonix/aeon-gui.git`

7. Wechsle zum Ordner der AEON GUI

  `cd aeon-gui`

8. Starte den build

  `./build.sh`

Die Ausführbare Datei kann im Ordner `build/release/bin` gefunden werden.

**Anmerkung:** Lösung für den Fehler "ERROR: Xcode not set up properly"

Ändere `$HOME/Qt/5.8/clang_64/mkspecs/features/mac/default_pre.prf`

ersetze
`isEmpty($$list($$system("/usr/bin/xcrun -find xcrun 2>/dev/null")))`

mit
`isEmpty($$list($$system("/usr/bin/xcrun -find xcodebuild 2>/dev/null")))`

Mehr Informationen: http://stackoverflow.com/a/35098040/1683164


### Auf Windows:

Die AEON GUI für Windows ist 64-bit; 32-bit Windows GUI Versionen werden nicht mehr offiziell unterstützt.

1. Installiere [MSYS2](https://www.msys2.org/), folge den Anweisungen auf der Website um dein System und die Pakete auf die neuste Version zu updaten.

2. Öffne eine 64-bit MSYS2 shell: Verwende den *MSYS2 MinGW 64-bit* shortcut oder die `msys2_shell.cmd` Batch-Datei mit dem `-mingw64` Parameter

3. Installiere die MSYS2 Pakete für die Abhängigkeiten von [AEON](https://github.com/aeonix/aeon); die benötigten 64-bit Pakete haben `x86_64` in ihren Namen stehen

    ```
    pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium mingw-w64-x86_64-hidapi
    ```

    Du kannst mehr über die Abhängigkeiten in der [AEON](https://github.com/aeonix/aeon) Dokumentation erfahren.
    *Anmerkung:* Es ist nicht mehr nötig *Boost* vom Quellcode zu kompilieren, es kann, wie alles andere auch, direkt mit dem MSYS2 Paket installiert werden.
 
4. Installieren von Qt5

    ```
    pacman -S mingw-w64-x86_64-qt5
    ```
    *Anmerkung:* Es ist nicht mehr nötig einen speziellen Installer von der Qt Website herunterzuladen. Das Standard MSYS2 Paket für Qt wird die Aufgabe normlerweise gut erledigen. 

5. Installieren von git

    ```
    pacman -S git
    ```

6. Herunterladen des Repository

    ```
    git clone https://github.com/aeonix/aeon-gui.git
    ```

7. Kompiliere

    ```
    cd aeon-gui
    source ./build.sh release-static
    cd build
    make deploy
    ```

    **Anmerkung:** Die Verwendung von `source` unter Schritt 7 ist eine schnelle Abhilfe für einen möglichen Bug in QT version 5.11.2-3, welche mit dem MSYS2 Paket verbreitet wird. Fuer weitere Informationen, siehe https://github.com/monero-project/monero-gui/issues/1559 
    
Die Ausführbare Datei kann im Ordner `.\release\bin` gefunden werden.
