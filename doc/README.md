blockidcoin
=============

Setup
---------------------
[blockidcoin](https://blockidcoin.trade/#wallets) is the original blockidcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of blockidcoin transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run blockidcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/blockidcoin-qt` (GUI) or
- `bin/blockidcoind` (headless)

### Windows

Unpack the files into a directory, and then run blockidcoin-qt.exe.

### macOS

Drag blockidcoin-Qt to your applications folder, and then run blockidcoin-Qt.

### Need Help?

* See the documentation at the [blockidcoin Wiki](https://github.com/blockidcoinvps-project/blockidcoin/wiki)
for help and more information.
* Ask for help on [blockidcoin Helpdesk](https://blockidcoin.com/).
* Join our Discord server [Discord Server](https://discord.gg/RpBXAnvp7k)

Building
---------------------
The following are developer notes on how to build blockidcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The blockidcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://www.fuzzbawls.pw/blockidcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Join the [blockidcoin Discord](https://discord.gg/RpBXAnvp7k).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
