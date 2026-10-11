# 50. Claim your creator fees

Collect the trading fees your token has earned, in SOL, with the wallet that launched it.

**Open:** [Creator Dashboard](https://spawnmeme.com/creator-dashboard). It is in the **Tools** menu as **Creator earnings**, and in the site footer. On your own token's page, a box at the bottom links to it when your launch wallet is connected.

## What you earn

| When | What you earn | Button |
| --- | --- | --- |
| While the token is on its bonding curve | About 0.25% of every trade, from the first trade, on tokens launched with creator fees | **Claim curve fees** |
| After the token graduates | The trading fees of its locked Meteora pool, after Meteora's share | **Claim fees** |

Both are paid in SOL. They wait in the token's own pool until you claim them, and they never expire.

## Before you start

* Only the wallet that launched the token can claim. No other wallet, and not SPAWN, can claim for you.
* Tokens launched before creator fees were switched on earn nothing on the curve. A pool's settings are permanent, so this cannot be changed for them. They still earn pool fees after graduation.
* A claim costs only the Solana network fee, which varies with the transaction and network conditions. Review the wallet estimate and keep enough SOL to pay it.
* SPAWN never holds these fees. Your wallet signs the claim and the SOL is paid straight from the pool to your wallet.

## Claim

1. Open the **Creator Dashboard** and connect the wallet that launched the token. If a different wallet is connected, press the **Wallet** button in the menu and switch.
2. Find the token under **Creator earnings**.
   * **Curve fees unclaimed** is what it has earned on the bonding curve.
   * **Unclaimed** is what its Meteora pool has earned since graduation.
3. Press **Claim curve fees** or **Claim fees**. Each button is one transaction for one token.
4. Approve the transaction in your wallet. The preview shows SOL arriving in your wallet and the network fee.
5. Wait for **Claimed. View transaction**. Check the confirmed transaction and wallet balance. The claimed amount clears; new trading fees may already be accruing.

You can claim as often as you like. If the amount waiting is about the size of the network fee, it pays to wait until more has built up.

## When a token graduates

Claim any curve fees still showing. They stay claimable after graduation. The token's Meteora pool appears on the dashboard a few minutes after graduation, and from then on its fees are claimed with **Claim fees**.

The pool's liquidity is locked permanently. Nobody, including you and SPAWN, can withdraw it; only the fees it earns can be claimed.

## Troubleshooting

| Symptom | What to do |
| --- | --- |
| The token is not listed | Connect the wallet that launched it. The dashboard lists only that wallet's launches. |
| No claim button | Nothing is waiting yet, or the token was launched before creator fees and is still on its curve. |
| "On the bonding curve. Launched before creator fees" | That token earns nothing on the curve. Its earnings start when it graduates. |
| "Graduated. Its Meteora pool position is not in this wallet yet" | Wait a few minutes after graduation and refresh. |
| The claim failed or expired | If a signature exists, check its status in Explorer before retrying. A failed submitted transaction can still cost a network fee. Refresh the claimable amount, keep enough SOL for fees, then retry only after confirming the earlier claim did not succeed. |
| Your wallet shows a warning before signing | Do not sign. Refresh the page and try again; if it repeats, contact support with the token's mint address. |
| "You cancelled the claim in your wallet" | Nothing was sent. Press the button again when you are ready. |

**Success:** the dashboard shows **Claimed. View transaction**, the transaction is confirmed, and your wallet balance reflects the payout minus applicable network costs. The claimed amount has cleared; a small new accrual may remain.

***

[Guide home](../README.md) · [Creator Dashboard and earnings](11-creator-dashboard.md) · [Fees](../reference-and-support/37-fees.md)
