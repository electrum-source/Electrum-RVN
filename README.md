<div align="center">

# Electrum

**Fast, secure, non-custodial desktop wallet for Bitcoin — in continuous development since 2011.**

[![Docs](https://img.shields.io/badge/docs-electrum.readthedocs.io-6c757d)](https://electrum.readthedocs.io/)
[![Website](https://img.shields.io/badge/website-electrum.org-4c1?logo=googlechrome&logoColor=white)](https://electrum.org/)
[![License](https://img.shields.io/badge/license-MIT-brightgreen)](https://github.com/spesmilo/electrum/blob/master/LICENCE)
[![Release](https://img.shields.io/badge/release-4.8.0-blue)](https://github.com/spesmilo/electrum/releases/tag/4.8.0)

</div>

---

## 📦 Downloads — v4.8.0

<div align="center">

[![Windows](https://img.shields.io/badge/⬇_Download-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://download.electrum.org/4.8.0/electrum-4.8.0-setup.exe)
[![macOS](https://img.shields.io/badge/⬇_Download-macOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://download.electrum.org/4.8.0/electrum-4.8.0.dmg)
[![Linux](https://img.shields.io/badge/⬇_Download-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://download.electrum.org/4.8.0/electrum-4.8.0-x86_64.AppImage)

</div>

| Platform | Requirements | File |
|---|---|---|
| 🪟 Windows | Windows 10 (1809) or later, 64-bit | [`electrum-4.8.0-setup.exe`](https://download.electrum.org/4.8.0/electrum-4.8.0-setup.exe) |
| 🍎 macOS | macOS 11 or later | [`electrum-4.8.0.dmg`](https://download.electrum.org/4.8.0/electrum-4.8.0.dmg) |
| 🐧 Linux | Most modern distros, x86_64, glibc 2.31+ | [`electrum-4.8.0-x86_64.AppImage`](https://download.electrum.org/4.8.0/electrum-4.8.0-x86_64.AppImage) |
| 🐍 Source | Python ≥ 3.10 | [`Electrum-4.8.0.tar.gz`](https://download.electrum.org/4.8.0/Electrum-4.8.0.tar.gz) |

Verify every file against its published `.asc` signature (linked next to each download above) before running it.

> Only download Electrum from [electrum.org](https://electrum.org/) or the [official GitHub releases page](https://github.com/spesmilo/electrum/releases) — never from a third-party mirror or search ad.

---

## 🚀 Install

<details>
<summary>🪟 <b>Windows</b></summary>

1. Download `electrum-4.8.0-setup.exe`
2. Run the installer
3. Launch **Electrum** from the Start Menu

No extra dependencies needed.
</details>

<details>
<summary>🍎 <b>macOS</b></summary>

1. Download `electrum-4.8.0.dmg`
2. Open the disk image and drag Electrum to Applications
3. On first launch, right-click the app → **Open** to bypass Gatekeeper's unsigned-app warning
</details>

<details>
<summary>🐧 <b>Linux</b></summary>

```bash
wget https://download.electrum.org/4.8.0/electrum-4.8.0-x86_64.AppImage
chmod +x electrum-4.8.0-x86_64.AppImage
./electrum-4.8.0-x86_64.AppImage
```
</details>

<details>
<summary>🐍 <b>From source (any OS)</b></summary>

```bash
sudo apt-get install libsecp256k1-dev
ELECTRUM_ECC_DONT_COMPILE=1 python3 -m pip install --user ".[gui,crypto]"
```
</details>

---

## ✨ Features

- Non-custodial — private keys stay encrypted on your machine
- Instant on — no full blockchain download required
- Cold storage & watching-only wallets
- Multisig support (2-of-3, 3-of-5, etc.)
- Hardware wallet support (Ledger, Trezor, and others)
- Recover any wallet from a 12/24-word seed phrase
- Cross-platform (Windows / macOS / Linux / Android)
- Third-party plugin support

---

## 🗂️ Where things live

| What | Location |
|---|---|
| Wallet data | `~/.electrum/wallets/` |
| Config | `~/.electrum/config` |
| Logs | `~/.electrum/logs/` |

---

## ⚠️ Important

**Your seed phrase is the only way to recover your funds — write it down and store it offline.** The Electrum developers cannot recover lost seed phrases or reverse transactions, and nobody from "Electrum support" will ever contact you privately — support only happens on public GitHub issues and forums.

---

## 🛠️ Development / build

```bash
git clone https://github.com/spesmilo/electrum.git
cd electrum
git submodule update --init
python3 -m pip install --user -e .
./run_electrum
```

Run tests:

```bash
pytest tests -v
```

Release notes: [`RELEASE-NOTES`](https://github.com/spesmilo/electrum/blob/master/RELEASE-NOTES) · GPG check guide: [docs.electrum.org](https://electrum.readthedocs.io/en/latest/gpg-check.html)

---

## 📚 Stack

- Python (≥ 3.10)
- Qt (PyQt6) — desktop GUI
- Kivy — Android GUI
- [ElectrumX](https://github.com/spesmilo/electrumx) — server protocol

---

## 💬 Support

Docs: [electrum.readthedocs.io](https://electrum.readthedocs.io/) · Issues: [GitHub Issues](https://github.com/spesmilo/electrum/issues) · Community: [Reddit](https://www.reddit.com/r/Electrum/) · [bitcointalk.org](https://bitcointalk.org/index.php?board=98.0)

## 📄 License

[MIT](https://github.com/spesmilo/electrum/blob/master/LICENCE)
