# 6. NFT collections and public mints

## Collections and individual assets

SPAWN supports NFT collections and public mints using Metaplex Core, with artwork and metadata stored on Arweave. A collection provides an on-chain grouping for a creator's assets.

The documented creation flow requires a SPAWN account and a supported wallet. The creator enters a collection name and description, supplies a cover image, chooses royalties and approves the collection transaction. The creator can then mint individual NFTs with their own artwork, names and optional traits, to their wallet or another destination.

A one-of-one claim must match the actual minting and collection configuration. Writing “1/1” in an image or description alone does not enforce scarcity across a creator's future releases.

## Public mint setup

The documented public-mint workflow supports sets of 2 to 10,000 NFTs. Creators select their images, optionally include traits and shuffle the order, then set the mint price, opening time, optional closing time and per-wallet limit.

The flow separates storage from mint creation. First, the creator approves payment to the storage service and uploads the assets to Arweave. A second transaction creates the mint on Solana. Interrupted uploads can be resumed through the documented workflow using the same image set.

Uploaded images are public before minting, and NFTs are minted in number order. This is relevant to any description of a reveal, randomized allocation or collectible rarity. Creators should not advertise mechanics that the configured mint does not implement.

## Buyer and creator flows

A buyer opens a collection page, reviews its price and fees, and approves the mint through a supported wallet. The mint price goes to the creator, while the SPAWN fee is paid on top by the buyer under the documented model.

The SPAWN interface does not allow public-mint price, timing or wallet limits to be edited after launch. The creator wallet controls the on-chain rules; the documented interface pauses minting if externally changed rules no longer match the displayed page.

## Storage, rights and resale

Arweave is used to retain uploaded NFT artwork and metadata independently of SPAWN's web hosting. The documented workflow treats uploaded material as permanent and not editable or deletable afterward. Creators should review files carefully and avoid publishing private information.

The NFT ownership record and intellectual-property rights are separate matters. Any art license, access benefit or other entitlement must be stated by the creator. Royalty settings depend on marketplace support and enforcement.

SPAWN does not operate an NFT resale marketplace. External venues determine collection visibility, indexing, supported standards and trading rules.

***

[Previous: 5. Markets, trading and wallet tools](05-markets-wallet.md) · [Next: 7. Buy Bot and Trending](07-buybot-trending.md)
