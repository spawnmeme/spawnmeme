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

SPAWN's current model pays no creator trading earnings while a token remains on its bonding curve. After graduation, eligible trading fees accrue to the creator's locked Meteora position. Earnings depend on subsequent trading and may be zero.

The position's liquidity stays locked. **Claim fees** collects available fees; it does not withdraw the underlying liquidity. The dashboard can show SOL and, where present, token units. Any USD figure is only an estimate.

## Claim available fees

1. In **Creator earnings**, find the graduated token.
2. Check **Unclaimed** and the connected wallet.
3. Choose **Claim fees** when available.
4. Review and approve the wallet transaction. Multiple positions can require multiple approvals.
5. Wait for confirmation and use **Claimed. View the transaction** to inspect the result.

Claims have network costs. Very small fee amounts may not justify the immediate transaction cost; the screen can flag this. The claim may also unwrap existing wrapped SOL into ordinary SOL.

## Troubleshooting

| State                                 | Meaning and next step                                                                                                      |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| No tokens                             | Verify the original launch wallet and that registration completed. Check [launch recovery](09-deploy-token.md).   |
| On the bonding curve                  | No creator earnings yet under this model.                                                                                  |
| Graduated, position not in wallet yet | Pool/position creation may still be completing. Recheck later with the same wallet.                                        |
| **Nothing to claim**                  | The readable position currently has no unclaimed fees.                                                                     |
| Earnings unavailable                  | Refresh after connectivity/RPC recovers; an unavailable response is not a zero balance.                                    |
| Claim fails or times out              | Keep the signature if one exists and inspect it before retrying. If nothing was sent, reconnect and request a fresh claim. |

**Success:** the correct token's claim confirms and its available fee balance updates. No fixed earning amount or schedule is promised.

## Follow curve milestones

Open your token page, select **Alerts**, and choose **Curve milestones** in the private bot chat. Alerts cover 25%, 50%, 75% and graduation, with checks every five minutes. See [43. Token alerts in Telegram](../telegram-and-promotion/43-token-alerts.md).


***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
