# 21. Mint, hold, send and trade NFTs

**Open:** a collection from [NFT collections](https://spawnmeme.com/nfts) or its official collection URL. Browsing a collection does not connect your wallet or buy anything.

## Mint from a public collection

1. Verify the collection address and creator source. Similar names or art can be copied.
2. Locate the **Mint** panel and check its status, minted count and remaining supply.
3. Read **Price**, **SPAWN fee**, **You pay**, network-cost estimate, start/end times and any wallet limit.
4. Choose **Connect wallet to mint** and confirm the receiving Solana account.
5. Choose **Mint for \[amount] SOL**.
6. Review and approve the transaction. Wait for **Minted. It is in your wallet now** and inspect **View on Solscan**.

The public mint gives the next item in number order. The preview of the first few images is not a chooser for a particular NFT. The creator price goes to the creator; the platform fee is separate. A zero creator price can still require SOL for platform and network costs.

## Hold or send

Use a wallet that supports Metaplex Core to view and transfer the NFT. If sending, verify the recipient address and the exact NFT. Sending is performed in your wallet or another supported tool, not through an invented SPAWN send button.

## Resale

SPAWN does not currently operate its own NFT marketplace. Use a marketplace that supports the asset's standard, following that venue's current listing process and fees. Each venue decides what it indexes and displays. A successful mint does not guarantee a listing, floor price, liquidity or a buyer. Royalty treatment depends on the venue.

## Troubleshooting

| State                                | What it means                                                                                                                                                  |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| No Mint panel                        | The creator may not have launched a public mint. Individual creator-minted items are different.                                                                |
| Not open / ended / sold out          | The sale's on-chain conditions do not currently permit a mint.                                                                                                 |
| Wallet at limit                      | This wallet has reached the configured allowance.                                                                                                              |
| Rules no longer match                | SPAWN pauses the page's mint action when on-chain rules differ from the displayed configuration. Ask the creator for clarification; do not bypass the warning. |
| Not enough SOL                       | Fund enough for the displayed total plus applicable network/account costs.                                                                                     |
| Transaction failed                   | Check the receipt. No successful NFT mint occurred, but a submitted failed transaction may still incur a network fee.                                          |
| Confirmed NFT missing from wallet UI | Check the recipient and asset address, refresh, and allow for Core support/indexing delays.                                                                    |

A completed mint cannot be undone through SPAWN. If a transaction was submitted, inspect its signature before pressing Mint again.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
