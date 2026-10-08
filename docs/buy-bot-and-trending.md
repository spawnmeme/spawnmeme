# SPAWN Buy Bot & Trending

Bring supported, confirmed buy activity into your project's Telegram community.

## Connect your group

1. Add [@spawnmeme_bot](https://t.me/spawnmeme_bot) to your project group.
2. Make the bot an administrator.
3. From a visible group-admin account, send the command below with your token's full mint address.

```text
/buybot YOUR_TOKEN_MINT
```

The current version supports verified SPAWN tokens on active bonding curves. Graduated pools and arbitrary external Solana tokens are not currently supported.

One token is connected per group. Multiple groups can follow the same supported token, subject to monitoring capacity. Connecting a group does not establish ownership of the token.

## Project-group commands

| Command | Purpose |
| --- | --- |
| `/buybot` | Show setup guidance |
| `/buybot YOUR_TOKEN_MINT` | Connect a supported token; group admin required |
| `/buybotmin 0.01` | Set the minimum buy alert to 0.01 SOL; group admin required |
| `/stopbuybot` | Pause alerts; group admin required |
| `/trending` | Show the current activity ranks and channel |
| `/ca` | Show the connected token's mint |
| `/buy` | Open the connected token's page |

The main SPAWN group keeps its official token configuration. Connect your project in its own community group.

## Delivery and coverage

Alerts are based on supported confirmed curve activity. SPAWN-site buys can trigger alerts promptly; background checks currently run every five minutes. Network conditions and service capacity can delay alerts.

Use the minimum setting to keep messages relevant to your community. Pausing alerts does not alter the token, wallet or pool.

## The central Trending board

Follow [SPAWN Trending](https://t.me/spawntrending) for the pinned, updating board.

Organic activity rankings use a rolling 60-minute window for connected SPAWN bonding-curve tokens. Qualifying activity requires at least two buyers; creator buys are excluded and repeat-wallet contributions are capped. This is a ranking of the supported monitored set, not every Solana token.

Eligible buy alerts can show the token's current organic rank. Stale rankings should not be treated as current activity.

## Paid visibility

Promoted entries are displayed separately from organic activity ranks. Paying for visibility does not purchase an organic rank.

Use the official [Trending page](https://spawnmeme.com/trending) for current availability, durations and payment instructions. SOL payments use the configured platform receiving wallet and an order-specific reference. Create the order through the site; an unsolicited transfer to an address cannot be assumed to activate a campaign.

## If setup does not work

Check that you are a visible group administrator, the bot is an administrator, the full mint is correct, and the token has an active supported curve. A capacity message means onboarding is currently full. Ask through [Help](https://spawnmeme.com/help) rather than repeatedly reconnecting.

[Open Buy Bot & Trending](https://spawnmeme.com/buy-bot) · [Back to SPAWN](../README.md)
