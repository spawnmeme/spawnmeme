# Technology and integrations

SPAWN combines creation tools with Solana transaction and discovery services.

| Technology | Role |
| --- | --- |
| Solana | Token accounts, wallets and on-chain transactions |
| Meteora | Supported token-launch bonding curves and pool trading |
| Jupiter | Swap routing across available supported liquidity |
| Raydium | Liquidity that may be available through supported swap routes |
| Alchemy | Solana RPC access |
| Metaplex Core | NFT collections and digital assets |
| Arweave | NFT artwork and metadata storage |
| Solscan | External links to on-chain records |
| Telegram | Community bot, configurable buy alerts, Trending board and optional platform-update notices |
| MetaMask Solana | Supported Solana wallet connection and signing flows |

A listed technology identifies an integration or infrastructure role. It does not imply a partnership, endorsement, audit or uninterrupted availability. Routing depends on supported assets, liquidity and current quotes.

Arweave storage described here applies to NFT assets and metadata; do not assume that every other platform asset uses the same storage method.

## Repository scope

This repository publishes documentation, community resources and brand information. It does not contain SPAWN's production application, backend services, wallet credentials, private deployment configuration or a smart-contract audit.

There is no application to install or run from this repository. Use [spawnmeme.com](https://spawnmeme.com) to access the platform. Future public code or developer resources should state their own scope and license when released.

[Features](https://spawnmeme.com/features) · [Security](../SECURITY.md) · [Documentation hub](README.md) · [FAQ](faq.md) · [Back to SPAWN](../README.md)

## Conditional trading boundary

Jupiter also supports SPAWN’s limit-order flow. Order deposits leave the user’s wallet for their Jupiter vault; SPAWN does not hold the funds. Expiry does not automatically return the deposit. See [architecture](whitepaper/03-architecture.md) and [limit-order recovery](feature-guides/discover-and-trade/42-limit-orders.md).
