# 11. Creator Dashboard and earnings

**Open:** [Creator Dashboard](https://spawnmeme.com/creator-dashboard). Connect the wallet that actually launched the token. Email identity alone does not control its creator position.

## Find your launches

1. Choose **Connect Wallet** if needed.
2. Confirm the connected address.
3. Review **Verified Launches** and **Your tokens**.
4. Open a token card to view its public page.
5. Use **Set up Buy Bot & Trending** for its Telegram tools, or **Send an airdrop** to distribute tokens you hold.

The dashboard lists verified launches recorded for the wallet. A project draft without a confirmed launch is not a verified token.

## Understand creator earnings

Tokens launched with creator fees earn the launch wallet about **0.25% of each bonding-curve trade**, from the first trade. This is included in the existing **1.2% trading fee**, not an additional charge. Tokens launched before creator fees were enabled retain a permanent 0% creator share on the curve. After graduation, creators can claim the eligible trading fees of the locked Meteora pool, after Meteora’s share. Earnings require trading and may be zero.

Creator fees wait in the token’s own pool until claimed and do not expire. SPAWN does not hold them. Only the launch wallet can sign the claim. Graduated liquidity remains permanently locked; claiming fees does not withdraw it.

## Claim available fees

1. Open **Creator earnings** with the original launch wallet.
2. Check **Curve fees unclaimed** for accrued curve fees and **Unclaimed** for graduated pool fees.
3. Select **Claim curve fees** or **Claim fees**. Each button claims for one token in one transaction.
4. Review the SOL payout and network fee, then approve in your wallet.
5. Wait for **Claimed. View transaction** and inspect the confirmed result. New trading fees may accrue immediately after the claim.

Curve fees remain claimable after graduation. The graduated Meteora position can take a few minutes to appear. Network costs apply; small balances can be left to accumulate. See [50. Claim your creator fees](50-claim-creator-fees.md) for the complete walkthrough and recovery steps.

## Troubleshooting

| State                                 | Meaning and next step                                                                                                      |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| No tokens                             | Verify the original launch wallet and that registration completed. Check [launch recovery](09-deploy-token.md).   |
| On the bonding curve | Creator-fee launches can accrue claimable fees. Older launches retain 0% curve earnings; check the token’s displayed eligibility. |
| Graduated, position not in wallet yet | Pool/position creation may still be completing. Recheck later with the same wallet.                                        |
| **Nothing to claim**                  | The readable position currently has no unclaimed fees.                                                                     |
| Earnings unavailable                  | Refresh after connectivity/RPC recovers; an unavailable response is not a zero balance.                                    |
| Claim fails or times out              | Keep the signature if one exists and inspect it before retrying. If nothing was sent, reconnect and request a fresh claim. |

**Success:** the correct token's claim confirms and its available fee balance updates. No fixed earning amount or schedule is promised.

## Follow curve milestones

Open your token page, select **Alerts**, and choose **Curve milestones** in the private bot chat. Alerts cover 25%, 50%, 75% and graduation, with checks every five minutes. See [43. Token alerts in Telegram](../telegram-and-promotion/43-token-alerts.md).


***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
