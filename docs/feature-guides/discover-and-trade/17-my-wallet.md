# 17. My Wallet: balances, receive and activity

**Open:** [My Wallet](https://spawnmeme.com/wallet). Connect your existing Solana wallet; no email account is required. SPAWN reads the wallet rather than taking custody of it.

## Read balances

1. Connect and verify the full address at the top.
2. Review **SOL balance**, **Estimated portfolio value** or **Known priced value (partial)**, and **Tokens held**.
3. Search **Holdings** by name, symbol or mint.
4. Open **Token details** for a holding, or **Sell / quote** to load its swap direction.
5. Choose **Refresh** to read balances again.

Unpriced tokens are excluded from the displayed USD total. A partial value is not your complete portfolio valuation. The holdings count reflects readable nonempty token accounts; this page is not a comprehensive NFT gallery.

## Receive SOL or tokens

1. Choose **Receive**.
2. Confirm the address shown beneath the QR code.
3. Use **Copy address** or the QR code in the sending wallet/service.
4. Ensure the sender is using **Solana** and the intended asset.
5. After confirmation, choose **Refresh** and inspect the receipt if the asset is not immediately visible.

Receiving here does not ask you to sign a transaction. My Wallet exposes receive information and trade shortcuts; it does not replace every send/asset-management feature of your wallet app.

## Recent activity and shortcuts

Open a recent transaction to view its full record on Solscan. Statuses such as failed or confirmed describe the transaction, while a balance view can still be waiting for a refresh. Use **Explorer**, **Swap**, **Creator earnings**, **Referrals** or **Quests** to move to the related tool. Empty-account notices link to the [Incinerator](../wallet-utilities/26-incinerator.md).

## Troubleshooting

| Symptom                  | Resolution                                                                                         |
| ------------------------ | -------------------------------------------------------------------------------------------------- |
| Balance looks wrong      | Check the full connected address and Solana network, refresh, then compare the transaction record. |
| Token has no USD value   | Pricing is unavailable; the token amount can still be valid.                                       |
| Token name/image missing | Metadata providers may not know it; identify it by mint.                                           |
| Activity unavailable     | Retry after service connectivity recovers; it does not prove there were no transactions.           |
| QR/copy unavailable      | Carefully select and copy the full displayed address, then compare it in the sending app.          |
| Wrong wallet connected   | Use **Disconnect** and reconnect the intended wallet.                                              |

Reading, searching and displaying a receive address have no SPAWN fee. Any subsequent swap, send or account closure has its own transaction costs.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
