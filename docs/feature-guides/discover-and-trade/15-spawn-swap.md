# 15. SPAWN Swap

**Open:** [Spawn Swap](https://spawnmeme.com/spawn-swap), or the embedded swap panel on a Markets token page. Quotes use supported routing, including available Meteora and Raydium liquidity through Jupiter-backed services.

## Prepare and quote

1. Connect the wallet that holds the asset you want to swap.
2. Select the token chip and search by name, symbol or mint. For an exact address, use **Use this mint address** when offered.
3. Check **You pay** and **You receive (estimated)**. Use the direction-switch button if they are reversed.
4. Enter the input amount. The current interface pairs the selected token with SOL; use the controls actually shown rather than assuming any arbitrary pair is available.
5. Wait for supported route quotes and select a route if choices are offered.
6. Review expected output, **minimum receive**, price impact, route and fees.

## Slippage and approval

Open **Slippage settings** and choose an available tolerance if you need to change it. A larger tolerance permits a worse execution price; it does not create missing liquidity or guarantee success. Do not raise it automatically just because a route failed.

Choose **Swap \[asset] for \[asset]**, review the transaction in your wallet and approve only if the amounts still match your intent. Keep the page open for the result.

## Result states

* **Swap complete**: confirmation was obtained. Inspect the transaction and balances.
* **Swap sent**: submission occurred, but confirmation is taking longer. Check the transaction before swapping again.
* **Nothing was sent**: the error explicitly states that no submission occurred; a fresh attempt may be appropriate after fixing the cause.

The default platform fee is 0.3%, with the precise fee shown by the live route. DEX/pool and network costs can also apply. Keep spare SOL, including when selling a token for SOL.

## Troubleshooting

| Message                            | What to do                                                                                                   |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Swaps are not switched on yet**  | Wait for service activation; do not send a manual payment.                                                   |
| **Selected token unavailable**     | Recheck the mint and provider coverage.                                                                      |
| **No route found**                 | Retry later or consider a smaller amount if appropriate. Some tokens have no supported executable liquidity. |
| **Not enough…**                    | Check the input asset, wallet and spendable balance, including fee reserve.                                  |
| Signature does not match           | Reconnect the correct account and request a fresh transaction if the app says nothing was sent.              |
| Failed on-chain                    | Inspect the receipt. The exchange did not complete; a network transaction fee can still have been charged.   |
| Sent but no visible balance change | Check the signature's result and the full input/output mints, then refresh My Wallet.                        |

Token-page bonding-curve referral rewards do not automatically apply to Spawn Swap. See [Refer & Earn](../community-and-rewards/25-referrals.md) for exact program coverage.

## Trade at a chosen price

The Swap page links to [Limit orders](42-limit-orders.md). A swap uses a current quote, with funds in the wallet until the transaction executes. A limit order waits for the selected dollar price with funds deposited in your own Jupiter vault. SPAWN does not hold the deposit. Expired orders require withdrawal; cancellation also requires completing the withdrawal. Only the connected owner wallet can deposit or withdraw.


***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
