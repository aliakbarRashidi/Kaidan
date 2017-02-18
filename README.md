# Kaidan - Cross platform XMPP client

[![Release](https://img.shields.io/github/release/kaidanim/kaidan.svg)](https://github.com/kaidanim/kaidan/releases)
[![Downloads](https://img.shields.io/github/downloads/kaidanim/kaidan/total.svg)](https://github.com/kaidanim/kaidan/releases)
[![Issues](https://img.shields.io/github/issues/kaidanim/kaidan.svg)](https://github.com/kaidanim/kaidan/issues)
[![Translation](https://hosted.weblate.org/widgets/kaidan/-/svg-badge.svg)](https://hosted.weblate.org/projects/kaidan/translations/)
[![License](https://img.shields.io/badge/license-GPLv3+ / CC BY‐SA 4.0-blue.svg)](https://raw.githubusercontent.com/kaidanim/kaidan/master/LICENSE.txt)

## Installation

On Linux do the following:

Create a working directory

 * `mkdir build`
 * `cd build`

Install dependencies to build Kaidan (example for Debian)

 *  `sudo apt-get install git-core cmake build-essential zlib1g-dev libglib2.0-dev libssl-dev libxml2-dev libcrypto++-dev libpthread-stubs0-dev libidn11-dev libminiupnpc-dev libnatpmp-dev libswiften-dev libboost-system-dev libboost-program-options-dev libboost-serialization-dev libqt5quick5 libqt5quickcontrols2-5 libqt5quickwidgets5 libqt5qml5 libqt5gui5 libqt5core5a qtdeclarative5-dev qttools5-dev qt5-default qml-module-qtquick-controls2 qml-module-org-kde-kirigami`

Get Kaidan source code

 * `git clone https://github.com/kaidanim/kaidan`

Finally compile it

 * `mkdir kaidan/build ; cd kaidan/build`
 * `cmake .. -DI18N=1`
 * `make -j<number of threads>`

You can now run Kaidan:

 * `./bin/kaidan`
