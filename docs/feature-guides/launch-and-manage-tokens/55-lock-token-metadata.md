# 55. Lock an older token’s metadata

**Open:** your token page while connected to its metadata update-authority wallet.

Current SPAWN launches lock their token identity at creation. Some earlier Classic tokens retain mutable Metaplex metadata. For an eligible token, **Lock token metadata** lets its update-authority wallet make the name, symbol and metadata link permanent.

## Before you continue

Check the current name, ticker and metadata link. **This action is irreversible.** It does not burn tokens, lock a token balance, change supply or create a liquidity lock. Locking a URL also does not independently guarantee permanent storage of whatever an external host serves at that URL.

## Lock step by step

1. Connect the wallet that currently controls the token's metadata update authority.
2. Find **Lock token metadata**. The card appears only when the interface detects mutable metadata and a matching connected authority.
3. Read the permanent-change notice and tick the acknowledgement.
4. Choose **Lock metadata permanently**.
5. Review the transaction and network fee in your wallet, then approve promptly.
6. Wait for **Metadata locked** and inspect the resulting on-chain metadata status.

The action costs the Solana network fee. It does not transfer holders' tokens.

## Troubleshooting

If the card is absent, the metadata may already be immutable, the connected wallet may not be the update authority, or the metadata may not be supported by this Classic-token workflow. It is not a general editor for every token program.

If preparation or approval expires before submission, obtain a fresh request. If a signature exists, check its status before retrying. **Success:** the on-chain metadata is immutable and the page confirms the lock.

***

[Guide home](../README.md) · [Get help](https://spawnmeme.com/help)
