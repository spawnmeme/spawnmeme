# 7. Buy Bot and Trending

## Community activity at the point of conversation

SPAWN Buy Bot brings supported confirmed buy activity into a project's Telegram group. This allows a community to follow relevant transactions without treating a separate trading page as its only source of updates.

A project administrator adds [@spawnmeme\_bot](https://t.me/spawnmeme_bot), grants administrator access and connects the supported token from a visible group-admin account. The main SPAWN group maintains its official configuration; individual projects connect their own community groups.

| Command                   | Function                                    |
| ------------------------- | ------------------------------------------- |
| `/buybot YOUR_TOKEN_MINT` | Connect a supported token to the group      |
| `/buybotmin 0.01`         | Set a minimum alert size of 0.01 SOL        |
| `/stopbuybot`             | Pause alerts                                |
| `/trending`               | Show activity ranks and the central channel |
| `/ca`                     | Show the connected token's mint             |
| `/buy`                    | Open the connected token's page             |

Configuration commands require group-admin permissions. One token is connected per group. Multiple groups may follow the same supported token, subject to service capacity. Connecting a token does not prove ownership of its project.

## Current coverage

The current documented buy bot supports verified SPAWN tokens on active bonding curves. Graduated pools and arbitrary external Solana tokens are outside that coverage.

SPAWN-site buys can trigger alerts promptly, while background checks currently run every five minutes. Network conditions, confirmation timing and monitoring capacity can delay delivery. An alert is a derived notification and should be checked against the underlying transaction when necessary.

## Central organic rankings

[SPAWN Trending](https://t.me/spawntrending) hosts the pinned, updating Trending board. Organic ranks use a rolling 60-minute window for supported connected bonding-curve tokens.

The documented eligibility requires at least two buyers, excludes creator buys and caps repeat-wallet contributions. These rules limit some obvious distortions but do not establish that every participant is independent or that manipulation is impossible.

Eligible buy alerts can display the token's current organic rank badge. The ranking describes the supported monitored set, not all Solana activity. It is a time-sensitive activity measure rather than an endorsement.

## Paid visibility and SOL payments

Paid promotions are displayed separately from organic ranks. Purchasing visibility does not purchase an organic rank or guarantee trading activity.

Campaigns should be created through the official [Trending page](https://spawnmeme.com/trending). The order supplies current availability, duration and payment instructions. SOL payments use the configured platform receiving wallet and an order-specific reference so the service can associate the payment with its campaign.

An unsolicited transfer to a wallet address cannot be assumed to activate a campaign. Users should follow the order flow and inspect its status rather than resending payment because a promotion is not immediately visible.

## Private token alerts and refreshed records

The shared five-minute refresh records supported tokens’ SOL raised and market cap, marks graduation when the curve completes, and sends [private token alerts](../feature-guides/telegram-and-promotion/43-token-alerts.md). Price alerts stop at graduation; Curve milestones can notify the graduation event. This does not extend Buy Bot trade monitoring to graduated pools. Refresh delays can delay notifications.

Private alerts support market-cap increases of 25% or 2×, decreases of 25%, and curve milestones. Market-cap thresholds are measured at alert creation. Up to 20 alerts can be active; notifications are not real-time execution guarantees.


***

[Previous: 6. NFT collections and public mints](06-nfts.md) · [Next: 8. Community, quests, referrals and airdrops](08-community.md)
