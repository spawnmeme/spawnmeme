# 13. Trade on a SPAWN token page

**Open:** a token from [Spawn Feed](https://spawnmeme.com/launchpad), or its `https://spawnmeme.com/token/MINT_ADDRESS` link. Replace the placeholder with the full mint.

## Before a trade

Check the mint, creator details, token image and public links. Connect the wallet you intend to trade from. A buy needs SOL; a sell needs the token and some SOL for network costs. Read the token's current curve state.

## Buy

1. Select **Buy**.
2. Connect your named wallet if necessary.
3. Enter **Spend SOL**. If using **Max**, still check that sufficient SOL remains for all costs.
4. Wait for **Estimated receive** and the minimum receive amount.
5. Review the displayed live quote, pool fees and the current fixed 1% slippage allowance used by this curve panel.
6. Choose the buy action and approve the matching wallet transaction.
7. Wait for confirmation, save the signature and check your token balance.

## Sell

1. Select **Sell** and confirm the token balance belongs to the intended wallet.
2. Enter **Sell $TICKER** in token units, or use **Max**.
3. Read the estimated and minimum SOL receive amounts.
4. Approve the sale and verify the confirmed transaction and resulting balances.

This page's curve trading and [Spawn Swap](15-spawn-swap.md) are different routes. If a token graduates, follow the trading option available for its new state; the old curve may no longer accept trades.

## Fees and interpretation

New SPAWN bonding pools use a 1.2% base trading fee. Other protocol and network costs can apply; the live quote and wallet review govern your trade. Market cap and curve percentage are informational. Neither guarantees that an amount can be sold at the displayed price.

## Troubleshooting

| Problem                                 | Resolution                                                                                                                             |
| --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Trade button disabled                   | Connect a wallet, enter a positive valid amount and wait for a quote.                                                                  |
| Insufficient balance                    | Reduce the amount and retain SOL for fees; token holdings cannot pay Solana network fees.                                              |
| Quote changes or trade simulation fails | Recheck price, liquidity and curve state. Request a fresh quote; do not approve a stale transaction.                                   |
| Wallet rejected                         | If nothing was sent, no trade occurred. Start again only if you still want it.                                                         |
| Transaction pending                     | Inspect the saved signature before submitting another trade.                                                                           |
| Buy not in Telegram                     | The buy must be confirmed, supported and above that group's alert minimum; see [Buy Bot troubleshooting](../telegram-and-promotion/28-buybot-setup.md). |
| Sell succeeds but balance looks old     | Refresh My Wallet and compare the confirmed chain record.                                                                              |

**Success:** a confirmed on-chain swap shows the intended wallet, token and asset changes. A loading indicator or wallet approval alone is not confirmation.

## Inspect, share and follow a token

* **Top holders:** inspect creator holdings, supply concentration and labelled pool addresses. See [44. Top holders: check a token before you buy](44-top-holders.md).
* **Share:** copy a link with the token’s own preview. See [45. Share links that preview the page](../platform-information/45-share-links.md).
* **Alerts:** follow market-cap moves or curve milestones in a private Telegram chat. See [43. Token alerts in Telegram](../telegram-and-promotion/43-token-alerts.md).
* **Report:** send suspected scams, copies or abusive content to SPAWN for review. See [46. Report a token, NFT collection or project](../reference-and-support/46-report.md).

To trade at a chosen dollar price, use [Limit orders](42-limit-orders.md). These are a separate Jupiter flow, with funds deposited into your Jupiter vault and no guaranteed fill.


## How the curve trading fee is shared

For creator-fee launches, the creator receives about 0.25% of trade value from the existing 1.2% curve fee. Older pools retain their original settings. This does not add another fee to the trader’s quote. See [50. Claim your creator fees](../launch-and-manage-tokens/50-claim-creator-fees.md).

## More context on the token page

Inspect the [RugCheck report](56-risk-reports.md), [Locked tokens](../launch-and-manage-tokens/54-token-locks.md), creator activity and **DEX paid** status when available. Paid-profile status is not a safety endorsement. [The Nest](../community-and-rewards/58-the-nest.md) now supports a verified wallet or email account and sits below the chart and trades for linked projects. Embedded holder maps depend on partner configuration and provider coverage. The Blink button is currently disabled; use the normal page-share link.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
