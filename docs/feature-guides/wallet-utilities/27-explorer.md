# 27. SPAWN Explorer

**Open:** [Explorer](https://spawnmeme.com/explorer). It reads public Solana information. No wallet connection, signature or payment is needed.

## Search

1. Paste a full token mint, wallet address or transaction signature into the search field.
2. Choose **Search**.
3. Check what kind of result appears. A token account is different from both its owning wallet and its mint.
4. Follow the linked addresses to related records, or choose **View on Solscan** for a fuller external view.

## Read a token result

Review supply, decimals, token program, mint authority, freeze authority and available metadata mutability information. The largest-holder view concerns large token accounts/owners available from the query; it is not a complete count of all distinct people holding the asset.

An absent mint authority means no further minting through that authority; it does not prove project quality or price stability. Authority and metadata facts are not a safety rating. Liquidity, creator behavior and market conditions require separate assessment.

## Read a wallet result

Check its SOL balance, readable token holdings and recent activity. The Explorer can also identify programs or other account types. The interface limits the displayed holdings list; use the external record for a fuller view when needed.

## Read a transaction result

Check **Result**, time, network fee, signing accounts, programs used and token/SOL movements. Use this when a launch, payment or trade has a signature but the feature page has not updated.

SOL balance movements can include network fees, account rent, transfers and wrapped-SOL handling. A net movement is not automatically the exact purchase amount. Use the detailed transaction to understand the operation.

## Troubleshooting

| Symptom                              | What to do                                                                               |
| ------------------------------------ | ---------------------------------------------------------------------------------------- |
| Invalid search                       | Paste the full address/signature without ellipses, spaces or a ticker symbol.            |
| Newly sent transaction not found     | Allow propagation time and check the wallet's receipt/external link.                     |
| Token account shown instead of token | Follow the **Token** mint link in that result.                                           |
| Holder list unavailable              | Retry later or follow the external holder-view link.                                     |
| Image/name missing                   | Metadata lookup may have failed while core chain data remains available.                 |
| Query fails                          | Check connectivity and try again; a service failure does not prove the record is absent. |

**Success:** the result corresponds to the exact input, and you can identify its type and relevant confirmation/ownership details. For an unresolved paid action, include its signature in your [support report](../reference-and-support/39-support-and-safety.md).

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
