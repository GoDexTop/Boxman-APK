# Boxpool Android

![Boxpool Banner](/banner.png)

Welcome to Boxpool on Android, a decentralized privacy pool app with a built-in wallet flow called BoxWallet.

Think of it as your privacy lane for Web3:
- shield and manage private balances
- connect external wallets when needed
- use BoxWallet for local, device-first wallet control

## What this app is
- A local-first Android app shell for the Boxpool web app
- Packs the latest static app into the APK
- Serves the app from local assets inside the app for fast startup
- Keeps navigation and wallet handoff behavior locked down for safer usage

## Core features
- Privacy pool flows (shield and unshield UX)
- BoxWallet support in-app
- External wallet support through WalletConnect
- File upload and download support

## Install (easy path)
1. Grab the latest APK
2. Move it to your Android device.
3. Open the APK and allow install from unknown sources if prompted.
4. Launch Boxpool and start with BoxWallet or connect another wallet.

## Update the app icon or web assets
Updates should not delete your assets. It is a good practice to back everything up. 

## Security notes
- App content is served locally from packaged assets
- No unrestricted JavaScript bridge is exposed
- External links are handed off to Android when appropriate
