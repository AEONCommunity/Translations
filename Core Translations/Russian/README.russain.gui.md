# Aeon GUI

Copyright (c) 2014-2018, AEON, The Monero Project

## Ресурсы разработки

- Сайт: [aeon.cash](http://aeon.cash)
- Bitcointalk: https://bitcointalk.org/index.php?topic=641696.0
- Reddit: https://www.reddit.com/r/Aeon
- Github: [https://github.com/aeonix/aeon-gui](https://github.com/aeonix/aeon-gui)
- IRC: [#aeon on Freenode](irc://chat.freenode.net/#aeon)

## Реакция на уязвимость

- Реакция на уязвимость должна быть переадресована в Monero, поскольку большая часть кодовой базы Aeon является общей
- Наш [процесс реагирования на уязвимость]((https://github.com/monero-project/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) поощряет ответственное раскрытие информации
- Мы также доступны на [HackerOne](https://hackerone.com/monero)

Aeon - это приватная, безопасная, защищенная, не отслеживаемая, децентрализованная цифровая валюта. Вы являетесь вашим банком, вы контролируете свои средства, и никто не может отследить ваши переводы, если вы не позволите им это сделать.

**Приватность:** Aeon использует криптографическую систему, позволяющую отправлять и получать денежные средства, не раскрывая транзакции в блокчейне (книге транзакций, которая есть у всех участников сети). Это гарантирует, что ваши покупки, чеки и переводы останутся абсолютно конфиденциальными по умолчанию.

**Безопасность:** Используя потенциал распределенной пиринговой консенсус-сети, каждая транзакция защищена криптографически. Индивидуальные кошельки имеют мнемоническую фразу из 25 слов, которая отображается только один раз, и может быть записана для резервного копирования кошелька. Файлы кошелька зашифрованы паролем, чтобы быть уверенными, что они бесполезны в случае кражи.

**Неотслеживаемость:** Используя кольцевые подписи, которые являются особым свойством определенного типа криптографии, Aeon может гарантировать, что транзакции не только не отслеживаются, но и имеют опциональную неопределенность, которая обеспечивает затрудненную привязку транзакций к конкретному пользователю или компьютеру.

## О проекте

Это GUI версия кошелька для [Aeon](https://github.com/aeonix/aeon). Проект поставляется с открытым исходным кодом и полностью свободен для использования без ограничений, за исключением тех, которые указаны в лицензионном соглашении ниже. Нет никаких ограничений на создание альтернативной реализации Aeon, которая будет использовать протокол и сеть совместимым образом.

Как и во многих других проектах, репозиторий на Github считается "плацдармом" для последних изменений. Перед включением изменений в основную ветвь репозитория, отдельные разработчики тестируют эти изменения в своих собственных ветках, после чего отправляют запрос на их добавление в основную ветку, а затем проверяются специалистами, которые занимаются тестированием и анализом кода. Учитывая вышесказанное, перед использованием в рабочей среде, репозиторий должен быть тщательно проработан, если только в репозитории нет патча для конкретной задачи. Обычно для обеспечения стабильности лучше использовать тегированный релиз.

## Поддержка проекта

Aeon - проект на 100% спонсируемый сообществом. Если вы хотите присоединиться к проекту, самое простое, что вы можете сделать, это оказать финансовую поддержку проекту. Пожертвования как в Aeon, так и в Bitcoin могут быть сделаны на **donate.aeon.cash**, если вы используете клиент, который поддерживает стандарт [OpenAlias](https://openalias.org).

Адрес пожертвования для Aeon: `WmsSWgtT1JPg5e3cK41hKXSHVpKW7e47bjgiKmWZkYrhSS5LhRemNyqayaSBtAQ6517eo5PtH9wxHVmM78JDZSUu2W8PqRiNs` (viewkey: `71bf19a7348ede17fa487167710dac401ef1556851bfd36b76040facf051630b`)

Адрес пожертвования для Bitcoin: `12Cyjf3qV6qLyXdzpLSLPdRFPUVidvnzFM`

Разработка GUI а также некоторые вспомогательные услуги также любезно предоставляются спонсорами:

[<img width="80" src="https://static.getmonero.org/images/sponsors/mymonero.png"/>](https://mymonero.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/kitware.png?1"/>](http://kitware.com)
[<img width="100" src="https://static.getmonero.org/images/sponsors/dome9.png"/>](http://dome9.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/araxis.png"/>](http://araxis.com)
[<img width="150" src="https://static.getmonero.org/images/sponsors/jetbrains.png"/>](http://www.jetbrains.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/navicat.png"/>](http://www.navicat.com/)
[<img width="150" src="https://static.getmonero.org/images/sponsors/symas.png"/>](http://www.symas.com/)

Существует также несколько майнинговых пулов, которые любезно жертвуют часть своих сборов, список которых можно найти [в нашем посте на Bitcointalk](https://bitcointalk.org/index.php?topic=641696.0).

## Лицензия

Посмотрите [ЛИЦЕНЗИЮ](LICENSE).

## Установка Aeon GUI с помощью пакета

(**НУЖНО СДЕЛАТЬ**) ~Пакеты доступны для~

* ~Arch Linux через AUR: [aeon-wallet-qt](https://aur.archlinux.org/packages/aeon-wallet-qt/)~
* ~Void Linux: xbps-install -S aeon-core~
* ~GuixSD: guix package -i aeon-core~

Приветствуется создание пакета для вашего любимого дистрибутива!

## Сборка Aeon GUI из исходного кода

### На Linux:

(Протестировано на Ubuntu 17.10 x64, Ubuntu 18.04 x64 и Gentoo x64)

1. Установка зависимостей Aeon

  - Для Debian дистрибутивов (Debian, Ubuntu, Mint, Tails...)

	`sudo apt install build-essential cmake libboost-all-dev miniupnpc libunbound-dev graphviz doxygen libunwind8-dev pkg-config libssl-dev libzmq3-dev libsodium-dev libhidapi-dev`

  - Для Gentoo

	`sudo emerge app-arch/xz-utils app-doc/doxygen dev-cpp/gtest dev-libs/boost dev-libs/expat dev-libs/openssl dev-util/cmake media-gfx/graphviz net-dns/unbound net-libs/ldns net-libs/miniupnpc net-libs/zeromq sys-libs/libunwind dev-libs/libsodium dev-libs/hidapi`

2. Установка Qt:

  *Примечание*: Qt 5.7 является минимальной версией, необходимой для сборки GUI кошелька. Это делает некоторые дистрибутивы (в основном основанные на Debian, такие как Ubuntu 16.x или Linux Mint 18.x) устаревшими. Вы все еще можете собрать GUI, если вы Установка [официальный релиз Qt](https://wiki.qt.io/Install_Qt_5_on_Ubuntu), но он официально не поддерживается.

  - Для Ubuntu 17.10+

    `sudo apt install qtbase5-dev qt5-default qtdeclarative5-dev qml-module-qtquick-controls qml-module-qtquick-controls2 qml-module-qtquick-dialogs qml-module-qtquick-xmllistmodel qml-module-qt-labs-settings qml-module-qt-labs-folderlistmodel qttools5-dev-tools qml-module-qtquick-templates2`

  - Для Gentoo

    `sudo emerge dev-qt/qtcore:5 dev-qt/qtdeclarative:5 dev-qt/qtquickcontrols:5 dev-qt/qtquickcontrols2:5 dev-qt/qtgraphicaleffects:5`

  - Опционально: Чтобы собрать флаг `WITH_SCANNER`

    - Для Ubuntu

      `sudo apt install qtmultimedia5-dev qml-module-qtmultimedia libzbar-dev`

    - Для Gentoo

      Флаг *qml* должен быть включен.

      `emerge dev-qt/qtmultimedia:5 media-gfx/zbar`


3. Клонирование репозитория

    `git clone https://github.com/aeonix/aeon-gui.git`

4. Сборка

    ```
    cd aeon-gui
    QT_SELECT=5 ./build.sh
    ```

Исполняемый файл находится в папке build/release/bin.

### На OS X:

1. Установка Xcode с AppStore

2. Установка [homebrew](http://brew.sh/)

3. Установка необходимые зависимости для [Aeon](https://github.com/aeonix/aeon):

  `brew install boost --c++11`

  `brew install openssl` - для установки openssl заголовков

  `brew install pkgconfig`

  `brew install cmake`

  `brew install zeromq`

  *Примечание*: Если cmake не может найти файл zmq.hpp на OS X, установка `zmq.hpp` с
  https://github.com/zeromq/cppzmq в `/usr/local/include` должна решить эту проблему.

4. Установка Qt:

  `brew install qt5`  (или скачайте QT 5.8+ с [qt.io](https://www.qt.io/download-open-source/))

  Если у вас установлена старая версия Qt с помощью homebrew, вы можете заставить ее использовать 5.x следующим образом:

  `brew link --force --overwrite qt5`

5. Добавить каталог Qt bin к пути

    Пример: `export PATH=$PATH:$HOME/Qt/5.8/clang_64/bin`

    Это каталог, в котором Qt 5.x установлен в **вашей** системе

6. Возьмите последнюю копию репозитория aeon-gui

  `git clone https://github.com/aeonix/aeon-gui.git`

7. Зайдите в репозиторий.

  `cd aeon-gui`

8. Начните сборку

  `./build.sh`

Исполняемый файл находится в папке `build/release/bin`.

**Примечание:** Решение проблемы "ERROR: Xcode not set up properly"

Измените `$HOME/Qt/5.8/clang_64/mkspecs/features/mac/default_pre.prf`

замените
`isEmpty($$list($$system("/usr/bin/xcrun -find xcrun 2>/dev/null")))`

на
`isEmpty($$list($$system("/usr/bin/xcrun -find xcodebuild 2>/dev/null")))`

Больше информации: http://stackoverflow.com/a/35098040/1683164


### На Windows:

Aeon GUI на Windows доступен только для 64-битных систем; 32-битные Windows GUI сборки больше официально не поддерживаются.

1. Установите [MSYS2](https://www.msys2.org/), следуйте инструкциям на этой странице о том, как обновить систему и пакеты до последних версий.

2. Откройте 64-битную оболочку MSYS2: Используйте *64-битный ярлык MSYS2 MinGW* или файл `msys2_shell.cmd` с параметром `-mingw64`.

3. Установите MSYS2 пакеты для получения зависимостей Aeon; необходимые 64-битные пакеты имеют `x86_64` в названиях.

    ```
    pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium mingw-w64-x86_64-hidapi
    ```

    Более подробную информацию об этих зависимостях вы найдете в [документации Aeon](https://github.com/aeonix/aeon). Обратите внимание, что больше нет необходимости компилировать Boost из исходников; как и все остальное, вы можете установить его с помощью пакета MSYS2.

4. Установите Qt5

    ```
    pacman -S mingw-w64-x86_64-qt5
    ```

    Больше нет необходимости загружать какую-либо отдельную программу установки для Qt, стандартный пакет MSYS2 для Qt подойдет практически при всех обстоятельствах.

5. Установите git

    ```
    pacman -S git
    ```

6. Склонируйте репозиторий

    ```
    git clone https://github.com/aeonix/aeon-gui.git
    ```

7. Соберите

    ```
    cd aeon-gui
    source ./build.sh release-static
    cd build
    make deploy
    ```

    **Примечание**: Использование вышеприведенного `источника` является грязным обходом при подозрении на ошибку в текущей версии QT 5.11.2-3, доступной в системе упаковки MSYS2, см. https://github.com/monero-project/monero-gui/issues/1559 для более подробной информации.

    **Note:** The use of `source` above is a dirty workaround for a suspected bug in the current QT version 5.11.2-3 available in the MSYS2 packaging system, see https://github.com/monero-project/monero-gui/issues/1559 for more info.

Исполняемый файл можно найти в каталоге `.\release\bin`
