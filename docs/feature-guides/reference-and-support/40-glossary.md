# 40. Glossary

| Term                   | Meaning in this guide                                                                                   |
| ---------------------- | ------------------------------------------------------------------------------------------------------- |
| Account                | Your SPAWN login identity for account-based projects and tools                                          |
| Wallet                 | The application/account used to hold assets and sign Solana actions                                     |
| Public address         | An address others can use to identify a wallet or on-chain record                                       |
| Mint address           | The unique on-chain identifier of a fungible token; different from its ticker                           |
| Token account          | An account holding one wallet's balance of one token                                                    |
| SOL                    | Solana's native asset, used for fees and many SPAWN payments                                            |
| Wrapped SOL / WSOL     | SOL represented through a token account for compatible program operations                               |
| Message signature      | Proof of wallet control; by itself, not an on-chain asset transfer                                      |
| Transaction            | An on-chain operation or group of instructions approved by the required signers                         |
| Transaction signature  | The identifier used to inspect a submitted transaction                                                  |
| Confirmed              | The chain has confirmed a transaction at the observed commitment level; a website can still be updating |
| RPC                    | A service through which the app reads or submits Solana data                                            |
| Account rent           | SOL held to support an on-chain account, sometimes recoverable when eligible accounts close             |
| Quote                  | An estimated/current offer for a trade or service; it can expire or change                              |
| Slippage               | The allowed difference between the quoted and executable trade outcome                                  |
| Minimum received       | The lowest output permitted by the prepared trade's current limits                                      |
| Price impact           | The effect an order can have on execution price given available liquidity                               |
| Liquidity              | Assets available in a trading pool; not the same as market capitalization                               |
| Market cap (estimated) | A price-and-supply estimate, not cash available for all holders to exit                                 |
| Bonding curve          | The configured pool pricing progression used before migration/graduation                                |
| Graduation             | Migration from the initial curve to the next pool stage under its actual on-chain rules                 |
| Creator position       | The launch wallet's eligible post-graduation pool position; fee claims do not unlock its liquidity      |
| Classic / Token-2022   | Different Solana token programs; support differs across tools                                           |
| Metadata               | A token/NFT's associated name, description, image and other details                                     |
| Immutable              | Not changeable through the relevant authority or supported flow after it is locked                      |
| Metaplex Core          | The NFT standard used by SPAWN collection and NFT tools                                                 |
| Collection             | An on-chain record grouping related NFTs                                                                |
| Trait                  | A descriptive NFT attribute with a name and value                                                       |
| Public mint            | A configured sale/distribution allowing eligible visitors to mint under its rules                       |
| Arweave                | The permanent storage network used for supported NFT files and metadata                                 |
| Royalty                | A resale payment rule whose effect depends on marketplace support/enforcement                           |
| Whitelist              | The wallet list from which participating creators draw airdrop recipients                               |
| Buy Bot                | The Telegram alert tool for supported confirmed token buys                                              |
| Organic Trending       | Activity-based ranking of qualifying supported connected tokens                                         |
| Promoted               | A paid sponsored entry, separate from organic rank                                                      |
| Boost                  | Paid, time-limited website discovery visibility                                                         |
| Order memo/reference   | Information attached to a service payment so it can be matched to the intended order                    |
| Indexing               | A service discovering and processing chain records for search, stats or display                         |
| Draft                  | Saved work that may still need publishing or an on-chain transaction                                    |
| UTC                    | The timezone used for quest check-in days and the campaign times in this manual                         |

If a term appears in an error, keep the exact message and use [Troubleshooting](38-troubleshooting.md) to connect it to the correct recovery step.

## New feature terms

| Term | Meaning |
| --- | --- |
| Limit order | A conditional SOL/token order at a chosen dollar price, subject to expiry, liquidity and slippage. A fill is not guaranteed. |
| Jupiter vault | The connected wallet’s deposit location at Jupiter for limit-order funds; it is separate from the wallet balance and is not held by SPAWN. |
| Curve milestone | A supported token’s 25%, 50%, 75% or graduation alert threshold. |
| Share link | A page-specific link that supplies that page’s title, description and artwork for social previews. |
| Top holders | The token-page view of the largest holders, creator holdings and top-ten concentration excluding the bonding pool from that aggregate. |


***

[Guide home](../README.md) · [Troubleshooting](38-troubleshooting.md) · [Get help](39-support-and-safety.md)
