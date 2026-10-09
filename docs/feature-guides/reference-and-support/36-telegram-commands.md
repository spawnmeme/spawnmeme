# 36. Telegram command reference

**Bot:** [@spawnmeme\_bot](https://t.me/spawnmeme_bot). Send `/help` for the current grouped menu. Some commands behave differently in the official community, private bot chat and connected project groups.

## Platform and information

| Command       | Purpose                                           |
| ------------- | ------------------------------------------------- |
| `/help`       | Current command menu                              |
| `/links`      | Official website/social links, including Linktree |
| `/updates`    | News & Updates                                    |
| `/promo`      | Launch Week status and countdown                  |
| `/roadmap`    | Interactive Hatching Plan                         |
| `/features`   | Platform toolkit                                  |
| `/howitworks` | Overview of the launch workflow                   |
| `/fees`       | Platform fee information                          |
| `/faq`        | Common questions                                  |
| `/rules`      | Community rules                                   |
| `/safety`     | Wallet/trading safety information                 |

`/website` and `/socials` use the official-links response. Use the [official Linktree](https://linktr.ee/spawnmeme) when sharing the full ecosystem link list.

## Explore and create

| Command                    | Purpose                                                            |
| -------------------------- | ------------------------------------------------------------------ |
| `/token`, `/ca`, `/buy`    | Token information, mint and buy-page shortcut; check group context |
| `/fresh` | Newly launched token discovery |
| `/hot` | Boosted token discovery |
| `/top` | Tokens ranked by SOL raised |
| `/markets`, `/gainers`     | Wider Solana market discovery                                      |
| `/swap`, `/wallet`         | Spawn Swap and My Wallet                                           |
| `/launch`                  | [Telegram-assisted launch](../launch-and-manage-tokens/10-telegram-launch.md)            |
| `/spawn`, `/creator`       | Project creation and Creator Dashboard                             |
| `/nfts`, `/nftguide`       | NFT tools and explanation                                          |
| `/airdrop`, `/sendairdrop` | Whitelist and creator distributions                                |
| `/explorer`, `/burn`       | Explorer and Incinerator                                           |
| `/quests`, `/refer`        | Points participation and referral tools                            |
| `/trending`                | Supported ranks and central Trending channel                       |

During the private launch conversation, `/skip` skips an optional prompt and `/cancel` cancels the draft conversation. Name and ticker are required.

## Project Buy Bot administration

| Command/example                             | Purpose                                          |
| ------------------------------------------- | ------------------------------------------------ |
| `/buybot YOUR_TOKEN_MINT`                   | Connect the group's supported token              |
| `/buybotsettings`                           | Open configuration panel                         |
| `/buybotpreview 0.5`                        | Labelled sample; no real trade                   |
| `/buybotmin 0.01`                           | Minimum buy amount for alerts, in SOL            |
| `/buybotimage`                              | Caption/reply to supported base media            |
| `/buybotimage reset`                        | Restore base token artwork                       |
| `/buybottier medium 1`                      | Configure/update medium tier                     |
| `/buybottier large 5`                       | Configure/update large tier                      |
| `/buybottier medium reset`                  | Remove medium tier; use `large` for large        |
| `/buybotemoji 🔥` / `/buybotemoji off`      | Emoji bar selection or disable                   |
| `/buybotstep 0.1`                           | SOL per emoji repeat                             |
| `/buybotusd on` / `off`                     | Approximate USD display                          |
| `/buybotlinks on` / `off`                   | Social buttons                                   |
| `/buybotsocial website https://example.com` | Website button; also supports `x` and `telegram` |
| `/buybotsocial x off` / `reset`             | Hide button or restore metadata default          |
| `/stopbuybot`, `/resumebuybot`              | Pause/resume alerts                              |

Where a row shows `on / off`, send the full command with one selected value. Do not send the slash-separated alternatives literally. Replace example addresses and amounts with your intended settings.

## Command troubleshooting

Confirm the exact official bot username, spelling, chat context and permissions. Configuration requires a visible group administrator. If several bots share a group, Telegram may show a bot-specific command form; select the SPAWN bot. A stale menu does not necessarily mean a typed command is unavailable; check `/help` and the [setup guide](../telegram-and-promotion/28-buybot-setup.md).

## Private alerts and service monitoring

| Command | Where | Purpose |
| --- | --- | --- |
| `/alert MINT` | Private bot chat | Open alert choices for the supplied token mint |
| `/alerts` | Private bot chat | List active alerts; tap one to remove it |
| `/opsalerts` | Private bot chat; official group administrators only | Enable failure messages for the Buy Bot and Trending refresh |
| `/opsalerts off` | Same administrator context | Disable those failure messages |

Replace `MINT` with the full token address. See [43. Token alerts in Telegram](../telegram-and-promotion/43-token-alerts.md) for supported tokens, thresholds and the 20-alert limit.


***

[Guide home](../README.md) · [Troubleshooting](38-troubleshooting.md) · [Get help](39-support-and-safety.md)
