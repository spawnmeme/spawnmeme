# 3. Architecture and transaction boundaries

## Three operating layers

SPAWN combines a hosted application, user-controlled wallet authorization and external blockchain or infrastructure services. These layers have different roles and failure modes.

| Layer                        | Responsibility                                                                        | Boundary                                                            |
| ---------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| SPAWN application            | Creation tools, project pages, discovery, account records and transaction preparation | Depends on hosting, application services and data availability      |
| User wallet                  | Displays and signs approved messages or transactions                                  | The user must inspect the request and protect wallet access         |
| Solana and external services | Execute supported on-chain actions, provide RPC access, routing, storage and records  | Each program or provider has its own configuration and dependencies |

A wallet signature, network submission, confirmed transaction and platform listing are separate events. An interface should not be treated as authoritative proof of settlement when the transaction has not been confirmed.

## Technology roles

| Technology    | Documented role                                    |
| ------------- | -------------------------------------------------- |
| Solana        | Settlement and public token, pool and NFT records  |
| Meteora       | Supported bonding-curve launches and pool trading  |
| Jupiter       | Swap routing and supported vault-based limit orders  |
| Raydium       | Liquidity accessible through supported swap routes |
| Alchemy       | Solana RPC access                                  |
| Metaplex Core | NFT collection and asset standard                  |
| Arweave       | Storage for NFT artwork and metadata               |
| Solscan       | External inspection of on-chain records            |
| Telegram      | Community bot, buy alerts and the Trending channel |

These names describe integrations. They do not imply partnerships, endorsements or an audit of SPAWN.

## Wallet-approved execution

SPAWN's documented model prepares transactions for wallet review. User wallet keys remain with the wallet; the application does not require users to supply seed phrases. A message signature used to prove wallet control is distinct from an on-chain transaction that moves assets or changes state.

Wallet approval preserves a user's ability to reject an action, but approval can still authorize an irreversible mistake. Users must review assets, recipients, amounts, permissions and expected effects.

## Hosted data and on-chain state

Project content, account information, AI output, indexed discovery and quest records rely on application services. Solana records provide the corresponding on-chain state for token and NFT actions. NFT artwork storage is another separate dependency; the use of Arweave for NFTs should not be generalized to every file on the platform.

RPC or indexing failures may interrupt access, delay a quote or show an outdated status without changing the underlying ownership record. Community alerts are notifications derived from supported activity, not the settlement record itself.

## Limit-order boundary

A swap uses a current quote, with funds in the wallet until the transaction executes. A limit order waits for the selected dollar price with funds deposited in your own Jupiter vault. SPAWN does not hold the deposit. Expired orders require withdrawal; cancellation also requires completing the withdrawal. Only the connected owner wallet can deposit or withdraw.

## Mobile access and inspection services

The Android app wraps the SPAWN website and uses Solana Mobile Wallet Adapter for supported installed-wallet authorization. An APK is available from the official Android page; dApp Store approval is pending in this edition. RugCheck supplies independent token-risk reports; Jupiter Lock and Streamflow supply token-lock records; DEX Screener supplies paid-profile status. A Bubblemaps embed depends on partner configuration and coverage. These are separate provider boundaries, not SPAWN audits or endorsements.

***

[Previous: 2. Project creation and publishing](02-creation.md) · [Next: 4. Token launches and graduation](04-token-launches.md)
