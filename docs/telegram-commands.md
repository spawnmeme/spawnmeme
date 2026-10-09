# Telegram command guide

Open [@spawnmeme_bot](https://t.me/spawnmeme_bot). Use `/help` for the current command menu; commands and permissions can differ between the official community and connected project groups.

## News, links and platform information

| Command | Purpose |
| --- | --- |
| `/links` | Official website, X, Telegram, Trending and Linktree links |
| `/updates` | Open News & Updates |
| `/promo` | Launch Week offer status and countdown |
| `/roadmap` | Open the interactive Hatching Plan |
| `/features` | Explore the platform toolkit |
| `/howitworks` | Launch-flow guidance |
| `/fees` | Current fee information |
| `/faq` | Common questions |
| `/help` | Grouped command list |
| `/rules` | Community rules |
| `/safety` | Wallet and trading safety information |

## Explore and create

| Command | Purpose |
| --- | --- |
| `/token`, `/ca`, `/buy` | Token information, mint and buying shortcut; context depends on the group |
| `/fresh` | Newly launched tokens |
| `/hot` | Boosted tokens |
| `/top` | Tokens ranked by SOL raised |
| `/markets`, `/gainers` | Wider Solana market discovery |
| `/swap`, `/wallet` | Spawn Swap and My Wallet |
| `/launch` | Telegram-assisted token launch flow |
| `/spawn`, `/creator` | Project creation and creator dashboard |
| `/nfts`, `/nftguide` | NFT tools and guide |
| `/airdrop`, `/sendairdrop` | Creator whitelist and distribution tools |
| `/explorer`, `/burn` | On-chain lookup and Incinerator |
| `/quests`, `/refer` | Community tasks and referral tools |
| `/trending` | Supported token ranks and Trending channel |

## Project buybot administration

Start with `/buybot YOUR_TOKEN_MINT`, then `/buybotsettings`. The settings panel gives access to media instructions, buy-size tiers, emoji bars, minimum amounts, social buttons, USD display and previews.

See the [complete buybot command reference](buy-bot-and-trending.md) for exact syntax and requirements. Configuration and previews require a visible group administrator.

`/links` aliases such as `/website` and `/socials` use the same official-links response, including [Linktree](https://linktr.ee/spawnmeme).

[Documentation hub](README.md) · [Community](community.md) · [Back to SPAWN](../README.md)

## Private alerts

| Command | Context | Purpose |
| --- | --- | --- |
| `/alert MINT` | Private bot chat | Open token-alert choices; replace MINT with the full token address |
| `/alerts` | Private bot chat | List active alerts; tap one to remove it |
| `/opsalerts` | Private chat, official group administrators only | Enable Buy Bot/Trending refresh failure messages |
| `/opsalerts off` | Same administrator context | Disable those failure messages |

See [Token alerts](feature-guides/telegram-and-promotion/43-token-alerts.md) for supported active curves, five-minute checks, market-cap thresholds and the 20-alert limit.
