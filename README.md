## ShtPay for Android
------

[<img src="https://github.com/ShitcoinDeLuxe-project/shtpay-android/raw/master/images/icon-google-play.png">](
https://play.google.com/store/apps/details?id=org.shtpay)

### A completely standalone Shitcoin DeLuxe wallet

Unlike many other wallets, ShtPay is a real standalone SHT
client. There is no server to get hacked or go down, so you can always access
your money. Using
[SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients)
mode, ShtPay connects directly to the SHT network with the fast
performance you need on a mobile device.

### The next step in wallet security

ShtPay is designed to protect you from malware, browser security holes,
*even physical theft*. With AES hardware encryption, app sandboxing, and verified boot, ShtPay represents a significant security advance over
web and desktop wallets.

### Beautiful simplicity

Simplicity is ShtPay's core design principle. A simple backup phrase is
all you need to restore your wallet on another device if yours is ever lost or
broken.  Because ShtPay is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki),
your balance and transaction history can be recovered from just your backup
phrase.

### Features

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification

### How to set up the development environment
1. Download and install Java 7 or up
2. Download and Install the latest Android studio
3. Download and install the 15c version of NDK https://developer.android.com/ndk/downloads/older_releases
4. Clone or download this project
5. Open the project with Android Studio and let the project sync
6. Go to SDK Manager and download all the SDK Platforms and SDK Tools
7. Build -> Rebuild Project