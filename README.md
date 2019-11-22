![ƀ](https://github.com/beyondcoin-project/beyondcoin/blob/master/share/pixmaps/bitcoin256.png) 
# BYND Wallet for Android
----------------------------------

[![download](/images/icon-google-play.png)]
(https://play.google.com/store/apps/details?id=com.byndwallet)

### Beyondcoin done right

This is the Android port of the breadwallet iOS app, which can be found [here](https://github.com/breadwallet/breadwallet/).

##### A completely standalone Beyondcoin wallet:

Unlike many other Beyondcoin wallets, BYNDwallet is a real standalone Beyondcoin
client. There is no server to get hacked or go down, so you can always access
your money. Using
[SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients)
mode, breadwallet connects directly to the bitcoin network with the fast
performance you need on a mobile device.

##### The next step in wallet security:

BYNDwallet is designed to protect you from malware, browser security holes,
*even physical theft*. With AES hardware encryption, app sandboxing, and verified boot, BYND Wallet represents a significant security advance over
web and desktop wallets.

##### Beautiful simplicity:

Simplicity is byndwallet's core design principle. A simple backup phrase is
all you need to restore your wallet on another device if yours is ever lost or
broken.  Because byndwallet is  
[deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki),
your balance and transaction history can be recovered from just your backup
phrase.

### Features:

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification

## Installation:
1. Download and install Java 7 or up
2. Download and install the latest Android studio
3. Download NDK r15c from the [NDK Archives](https://developer.android.com/ndk/downloads/older_releases.html)
4. Clone this repo & init submodules
```bash
git clone https://github.com/jakesum/byndwallet-android.git
git submodule init
git submodule update
```
5. Open the project with Android Studio, navigate to `File > Project Structure > SDK Location`
6. Change `Android NDK Location` with the path to NDK r15c that you downloaded earlier
7. Go to SDK Manager and download all the SDK Platforms and SDK Tools
9. Build -> Rebuild Project
