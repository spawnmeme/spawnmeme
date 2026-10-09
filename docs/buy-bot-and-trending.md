# SPAWN Buy Bot & Trending

Bring supported, confirmed buy activity into your project's Telegram community. The buybot is free for supported SPAWN tokens on active bonding curves.

## Connect your group

1. Add [@spawnmeme_bot](https://t.me/spawnmeme_bot) to your project group and make it an administrator.
2. From a visible group-admin account, connect your token using its full mint address.
3. Open the settings panel and preview a sample alert.

```text
/buybot YOUR_TOKEN_MINT
/buybotsettings
/buybotpreview 0.5
```

One token is connected per group. Multiple groups can follow the same supported token, subject to monitoring capacity. Connecting a group does not establish ownership of the token. The main SPAWN group keeps its official token configuration.

## Richer buy alerts

| Detail | How to read it |
| --- | --- |
| Estimated market cap | An estimate based on the supported pool price and minted supply; not liquidity or a guaranteed exit value |
| Bonding-curve progress | Progress against that token's configured migration threshold |
| Holder count | Indexed holder data when available; unavailable data is not shown as zero |
| USD buy value | Optional approximate conversion of the SOL amount |
| Buyer labels | Shown only when supported by verified transaction or recorded history evidence |
| Trending badge | Current qualifying activity rank; sponsored visibility is separate |

Data can lag or be unavailable. A successful alert does not guarantee every optional statistic is available.

## Photos, GIFs and video

Send a photo, GIF/animation or MP4 video with `/buybotimage` as its caption, or reply to that media with the command. Use Telegram photo, animation or video mode rather than a document attachment.

- Photos: up to 10 MB.
- GIF/animation and video: up to 50 MB.
- `/buybotimage reset` returns the base alert to token artwork.

Media settings apply to the connected group. They do not change the token's public artwork.

## Match media to buy size

Attach or reply to media with one of these examples:

```text
/buybottier medium 1
/buybottier large 5
```

The highest qualifying tier wins. Large must be above medium; smaller buys use the base media. Sending a tier command without new media changes an existing tier's threshold.

Use `/buybottier medium reset` or `/buybottier large reset` to remove a tier. Resetting base media does not remove the tiers.

## Settings and commands

Configuration commands and previews require a visible group administrator.

| Command | Purpose |
| --- | --- |
| `/buybotsettings` | Open the settings panel, presets, media instructions and controls |
| `/buybotpreview 0.5` | Show a labelled sample for a 0.5 SOL buy |
| `/buybotmin 0.01` | Set the minimum alert size in SOL |
| `/buybotemoji 🔥` | Set up to three standard emoji for the buy bar |
| `/buybotemoji off` | Hide the emoji bar |
| `/buybotstep 0.1` | Set SOL represented by each repeat |
| `/buybotusd on` or `/buybotusd off` | Toggle the approximate USD buy value |
| `/buybotlinks on` or `/buybotlinks off` | Toggle social buttons |
| `/stopbuybot` | Pause alerts |
| `/resumebuybot` | Resume alerts |
| `/trending` | Open current ranks and the Trending channel |
| `/ca` | Show the connected token's mint |
| `/buy` | Open the connected token's page |

Premium custom Telegram emoji are not supported. Emoji bars are capped to fit Telegram captions; a `+` indicates the display limit.

Previews use example data. They do not record a buy, change rankings or count as a payment.

## Social buttons

Set a public HTTPS address for each button:

```text
/buybotsocial website https://example.com
/buybotsocial x https://x.com/yourproject
/buybotsocial telegram https://t.me/yourgroup
```

Use `/buybotsocial x off` to hide that button or `/buybotsocial x reset` to return to token metadata. Replace `x` with `website` or `telegram` as needed. These addresses are example inputs, not SPAWN's official links.

## Coverage and delivery

The current version supports verified SPAWN tokens on active bonding curves. Graduated pools and arbitrary external Solana tokens are not currently supported.

Alerts depend on confirmed activity, indexing and monitoring capacity. SPAWN-site buys can trigger alerts promptly, while background monitoring helps catch other supported activity. Network and service conditions can introduce delays.

## The central Trending board

Follow [SPAWN Trending](https://t.me/spawntrending) for the pinned, updating board. Organic rankings use a rolling 60-minute window for connected SPAWN bonding-curve tokens. Qualifying activity requires at least two buyers; creator buys are excluded and repeat-wallet contributions are capped.

This ranks the supported monitored set, not every Solana token. Stale rankings should not be treated as current activity.

## Paid visibility

Promoted entries are displayed separately from organic activity ranks. Paying for visibility does not purchase an organic rank.

Use the official [Trending page](https://spawnmeme.com/trending) for availability, durations and payment instructions. SOL payments use the configured platform receiving wallet and an order-specific reference. Create the order through the site; an unsolicited transfer cannot be assumed to activate a campaign.

## Troubleshooting

Check that you and the bot are group administrators, the full mint is correct, and the token has an active supported curve. A capacity message means onboarding is currently full. If media is rejected, check its type, size and Telegram attachment mode. An unavailable statistic means its source could not be confirmed; it is not a zero value.

[Open Buy Bot & Trending](https://spawnmeme.com/trending#buybot) · [All bot commands](telegram-commands.md) · [Documentation hub](README.md) · [FAQ](faq.md) · [Back to SPAWN](../README.md)

## Private token alerts and refreshed data

The shared five-minute refresh records supported tokens’ SOL raised and market cap, marks completed curves as graduated and sends private token alerts. This does not add post-graduation Buy Bot trade monitoring.

Use `/alert MINT` in a private chat for market-cap increases of 25% or 2×, a decrease of 25%, or curve milestones at 25%, 50%, 75% and graduation. `/alerts` lists active alerts; up to 20 may be active. Price thresholds use market cap at creation, send once and end at graduation. See [the full alert guide](feature-guides/telegram-and-promotion/43-token-alerts.md).
