# 38. Troubleshooting and transaction recovery

Start with the visible symptom and whether a transaction was sent. Do not treat every error as a reason to repeat an action.

## 1. Was anything sent?

| Evidence                                  | Next step                                                                            |
| ----------------------------------------- | ------------------------------------------------------------------------------------ |
| Connection/message request only           | No on-chain payment is part of that step. Reconnect or verify again if appropriate.  |
| Wallet rejected and app says nothing sent | Fix the cause and make a fresh request if you still want the action.                 |
| Transaction signature exists              | Save it and inspect its status before repeating the action.                          |
| Transaction failed on-chain               | Check the error and any network fee; the intended operation did not complete.        |
| Transaction succeeded, site not updated   | Use the feature's receipt/registration recovery action.                              |
| Unsure whether submission occurred        | Inspect wallet activity and the chain record. Do not assume a timeout means failure. |

## 2. Use the matching recovery control

| Feature                        | Recovery path                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------ |
| Token deployment               | Same wallet → Deploy a Token → **Retry registration**                                |
| Trending                       | **Check payment**; use **Recover my orders** if needed                               |
| Advertising                    | Order → **Check my payment**                                                         |
| Spawn Kit                      | Project → **Retry verification**                                                     |
| Boost                          | Reopen the same token page to recheck saved pending confirmation; retain signature   |
| NFT collection/individual mint | Reopen the page and complete/check the saved pending transaction                     |
| Public NFT upload              | Same browser and original image set → **Continue the upload**                        |
| Public mint setup              | **Finish launching**                                                                 |
| Airdrop fee                    | **Draw my wallets**                                                                  |
| Airdrop batches                | **Continue sending** or history → **Continue**                                       |
| Swap or creator claim          | Check the signature, then refresh balances/fees; a new action is not a receipt check |

## 3. Page blank, frozen or unable to scroll

1. Record the exact URL, device, operating system, wallet/browser versions and what action preceded the problem.
2. If you were paying, copy the signature/order from wallet activity first.
3. Check that the URL is the official site and that your connection works.
4. Reopen the page once. For an ordinary browsing issue, compare another supported browser environment.
5. For an in-progress NFT upload or saved receipt, preserve the original browser and local data; switching devices may not resume that state.
6. Report whether the issue begins on a specific route or after an ad/image loads.

SafePal Android loading/freezing problems have been reported; they are not confirmed resolved. Do not describe iPhone success as proof that all Android environments work. Avoid repeatedly approving transactions in a frozen page.

## 4. Images or metrics missing

Images, market quotes, holder data, curve stats and wallet balances can come from different services. One missing field does not prove the entire action failed. Refresh the relevant view, use the full mint/signature in Explorer and preserve the exact error.

“Unavailable” is different from zero. A missing market price does not erase a token balance; an unavailable holder count does not mean no holders; a failed chart embed does not guarantee an executable swap route.

## 5. Identity or permission errors

Confirm all three identities where relevant: SPAWN account, Solana wallet and Telegram administrator. The account owning a project may differ from the connected wallet. A group admin can configure alerts but cannot claim another wallet's creator fees. Reopen records from the owning account's dashboard and verify full addresses.

## 6. What not to erase during recovery

Preserve pending receipts, original NFT upload files and browser storage until the issue is resolved. Local storage can contain watchlists and recovery state; clearing it is not a harmless first step. Save useful public identifiers before any later browser reset.

If the issue persists, use the [support template](39-support-and-safety.md). Never provide a seed phrase, private key, password or login code.

## MetaMask authorization recovery

| Symptom | What to do |
| --- | --- |
| MetaMask says "The requested account and/or method has not been authorized by the user" | The saved authorization may have expired. SPAWN asks MetaMask to reconnect and retries. If it persists, disconnect on SPAWN, select **MetaMask**, approve the Solana account and retry. This authorization failure sends no transaction and charges nothing. |


## Check service status and limit-order states

When a feature is not working, check [Status](48-status.md) first. It runs checks from your browser and does not cover every wallet, exchange or Solana issue. Keep any signature and inspect it before retrying a paid action.

For **Depositing**, **Waiting for price**, an expired order or **Withdrawal not finished**, follow [Limit orders](../discover-and-trade/42-limit-orders.md). Do not duplicate a deposit; expiry does not automatically return the vault balance.


## Recover a creator-fee claim

If a claim fails or times out, keep any transaction signature and inspect it before retrying. A failed submitted transaction may still incur a network fee. Refresh the claimable amount and wallet balance; retry only after confirming the earlier claim did not succeed. Older tokens may have no curve claim because their creator share is permanently zero. See [50. Claim your creator fees](../launch-and-manage-tokens/50-claim-creator-fees.md).


***

[Guide home](../README.md) · [Troubleshooting](38-troubleshooting.md) · [Get help](39-support-and-safety.md)
