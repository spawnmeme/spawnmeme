# 19. Mint an individual NFT or 1-of-1 artwork

**Open:** your collection from [NFT collections](https://spawnmeme.com/nfts). Sign in as its creator and connect the wallet that created it.

## Prepare the artwork and metadata

Use a clear, finished image in a supported format, up to 5 MB. Square art is convenient for common display cards, but the collection's upload control determines accepted files. Write a description explaining the artwork, not a promised resale value.

Traits are descriptive name/value pairs. For example:

| Trait      | Value          |
| ---------- | -------------- |
| Character  | Lime Hatchling |
| Background | Launch Lab     |
| Shell      | Speckled Cream |
| Edition    | 1 of 1         |

A trait saying “1 of 1” is descriptive metadata. It does not technically stop you or someone else from minting another asset with similar artwork. To represent a genuine single edition, mint it once and accurately describe any rights or edition commitments.

## Mint the item

1. Open **Mint an NFT** on the collection page.
2. Enter the NFT name, up to 32 characters, and its description.
3. Upload artwork or use the collection's available AI image option. Check the remaining AI allowance shown.
4. Add optional traits. Use short trait names and values; the current fields allow 40 and 60 characters respectively.
5. Leave the recipient empty to mint to your connected wallet, or enter the intended recipient's full Solana wallet address.
6. Recheck the image, metadata and recipient. Minting directly to another wallet gives that wallet the item.
7. Review the quoted fee and approve the mint transaction.
8. Wait for confirmation, then inspect the collection listing and receiving wallet.

The published creator-mint fee is 0.005 SOL per NFT, plus applicable storage, account, protocol and network costs. Each item has its own wallet approval.

## Troubleshooting

| Problem                                | Resolution                                                                                                  |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| No **Mint an NFT** form                | Use the creator account and collection-owning wallet; visitors do not see creator controls.                 |
| Wrong wallet warning                   | Switch to the wallet that created the collection.                                                           |
| Recipient rejected                     | Paste the complete Solana wallet address; do not use a token mint, username or shortened address.           |
| AI unavailable or allowance exhausted  | Upload finished artwork instead.                                                                            |
| Sent but not listed                    | Use the saved pending-mint completion action before attempting another mint.                                |
| Wallet does not show the NFT           | Confirm the recipient and successful chain record, then check support for Metaplex Core and indexing delay. |
| Need to change a minted image or trait | SPAWN does not offer post-mint editing for these details. Do not promise an automatic correction.           |

Owning the NFT does not automatically grant copyright or commercial rights to the artwork. State any intended license separately and clearly. For sending or resale, see [collecting and trading NFTs](21-minting-and-collecting.md).

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
