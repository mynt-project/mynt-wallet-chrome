# Mynt Wallet for Chrome
Copyright (c) 2018 The Mynt Project.
Portions Copyright (c) 2016-2017 bigreddmachine.

## License

This software is released under the terms of the MIT license. See `LICENSE` for
more information or see http://opensource.org/licenses/MIT.


## About

[![Now Available in the Chrome Store](extras/ChromeWebStore_BadgeWBorder_v2_206x58.png)](https://chrome.google.com/webstore/detail/mynt-wallet-for-google-ch/fmpbbjlihlifcpgeidnipmncolfkgjad)

Interact with a local Mynt mynt-wallet-cli via the Chrome or Chromium browser!

* Monitor your wallet's balance
* Send and receive XSM
* Create integrated payment addresses
* Check incoming payment information
* Store contacts' addresses and information
* Make fast payments to Mynt URIs found in open browser tabs


## Contributing

Please feel free to fork, submit pull requests or issues, or otherwise contribute
in making this extension as useful as possible.

If you find this extension useful, please consider donating to the main developer:  
[4AL2cmmrVC41if2TzxfYUKFoVF8xnkzszFX7KVS21zh1HgMWWTfa8wh23xBWLG2htS42LaqfQGgz69vVWA5uZGhaNLc72jB](monero:4AL2cmmrVC41if2TzxfYUKFoVF8xnkzszFX7KVS21zh1HgMWWTfa8wh23xBWLG2htS42LaqfQGgz69vVWA5uZGhaNLc72jB)


## Installation and Use

*Mynt Wallet for Chrome* can be easily installed from the Chrome store (See Above).
If you do not want to install this extension from the Chrome Store, you can
[install from Github](#install-from-github).

This extension is not a full wallet, but rather is an interface to Mynt's official command
line wallet. As such, it is important to note that this wallet does not store any sensitive
information about your wallet (view key, seed, etc), though you can use this wallet to view
these pieces of information.

For the extension to work, you need to have an instance of mynt-wallet-cli running in "RPC Mode"
on the same computer as your browser. To learn how to install and start mynt-wallet-cli, check
[Getting Started with mynt-wallet-cli](https://github.com/AltcoinCoop/mynt-wallet-chrome/blob/master/GETTING_STARTED.md).

For this extension to most easily work, your wallet will need to be open 24/7. For this
reason, it is recommended that you treat the wallet as you would your physical wallet. In
other words, do not store your life savings in this wallet, but only that monero you might
use day-to-day.


## Install from Github

If you would rather not install this extension directly from the Chrome Store, you can instead
install it from this repository, either by downloading a tagged release or building from source
yourself.

### Installing a tagged release

Navigate to [Releases](https://github.com/AltcoinCoop/mynt-wallet-chrome/releases) and
download the latest tagged release package. Then unzip the package.

Then install in Chrome:

1) Navigate to chrome://extensions

2) Enable Developer Mode

3) Load Unpacked Extension and select the unzipped package.


### Build and Install from Source (Linux/OS X)

To build this extension from source:

    git clone https://github.com/AltcoinCoop/mynt-wallet-chrome

    cd mynt-wallet-chrome

    ./build-chrome.sh

Install in Chrome:

1) Navigate to chrome://extensions

2) Enable Developer Mode

3) Load Unpacked Extension located at:

    .../mynt-wallet-chrome/build/chrome
