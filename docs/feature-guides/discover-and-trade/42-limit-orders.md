# 42. Limit orders

Buy or sell a token for SOL when its dollar price reaches a level you choose.

**Open:** [Limit orders](https://spawnmeme.com/limit-orders). It is also in the **Tools** menu and linked from SPAWN Swap.

## Before you start

* Limit orders are held and filled by Jupiter, not by SPAWN. Placing an order moves the funds from your wallet into your own vault at Jupiter, where the deposit remains until settlement or withdrawal. Only your wallet can deposit or withdraw; expiry alone does not return the funds.
* This is different from a swap, where funds stay in your wallet until the trade happens.
* The smallest order is $10. Every order expires, at most 30 days out.
* Orders are between SOL and one token. Prices are set in dollars.
* SPAWN charges no fee on limit orders. Solana network fees and any Jupiter fees still apply.
* You need a wallet that can sign messages and a little SOL for network fees.

## Place an order

1. Open **Limit orders** and connect your wallet.
2. Press **Sign in with** your wallet and approve the short message. It is free and sends nothing to Solana.
3. Choose **Buy a token** or **Sell a token**.
4. Paste the token's mint address. Check the name, symbol and current price shown under the field.
5. Enter the amount: SOL to spend when buying, or tokens to sell.
6. Choose when it should fill and enter the **Price in dollars**:
   * Buying: **falls to** (buy the dip) or **rises to** (buy a breakout).
   * Selling: **rises to** (take profit) or **falls to** (stop loss).
7. Choose the **Slippage allowed** and **Expires in**.
8. Read the **Your order** summary, tick the confirmation box and press **Place order**.
9. Approve the deposit in your wallet.

The order appears under **Your orders → Active** as **Waiting for price**.

## Cancel an order or withdraw from an expired one

1. Open **Limit orders** and sign in.
2. Find the order under **Active** or **Past**.
3. Press **Cancel and withdraw** (or **Withdraw funds**) and approve the withdrawal in your wallet.

An expired order keeps its funds in your vault until you withdraw them.

## Troubleshooting

| Symptom | What to do |
| --- | --- |
| "The order must be worth at least $10" | Increase the amount. |
| "Jupiter has no price for this token" | The order may never trigger. Choose a token Jupiter prices, or use SPAWN Swap. |
| Warning that the order would fill straight away | Your price is already reached. Change the price or the direction if that is not what you want. |
| "Your limit-order session has expired" | Press **Sign in** again. Sign-ins are short on purpose. |
| Order shows **Depositing** for a long time | Wait a few minutes and reopen the page. Do not place the same order twice. |
| Order shows **Withdrawal not finished** | Press **Withdraw funds** and approve the withdrawal again. |
| Order did not fill at your price | A fill is not guaranteed. Fast moves, thin liquidity or tight slippage can leave an order unfilled or partly filled. |

**Success:** the order appears under **Active**. After a fill, check settlement; for a cancelled or expired order, complete **Cancel and withdraw** or **Withdraw funds** and confirm the returned balance. Expiry alone does not return funds to your wallet.

***

[Guide home](../README.md) · [SPAWN Swap](15-spawn-swap.md) · [Fees](../reference-and-support/37-fees.md)
