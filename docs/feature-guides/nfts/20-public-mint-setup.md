# 20. Launch a public NFT mint

**Open:** your collection page → **Launch a public mint**. Sign in as the creator and connect the collection's creator wallet. Public-mint creation must be enabled; an admin preview is not general availability.

## Prepare your files

* Select a set of 2–10,000 images, within the limits shown by the form.
* Use PNG, JPG, WebP or GIF, up to 5 MB each.
* Give every image a unique filename. Keep the original files for recovery.
* Optionally prepare a JSON traits file keyed by the exact image filenames.

```json
{
  "1.png": { "Background": "Lime", "Hat": "Crown" },
  "2.png": { "Background": "Black", "Hat": "None" }
}
```

The uploader also accepts arrays of `trait_type`/`value` objects. Filenames must match, including extensions. [Download the example traits file](../../examples/nft-traits.json) and replace its example filenames and values. Prepare only public artwork and metadata: uploaded permanent files cannot be withdrawn.

## Set up the mint

1. Under **1. Images**, select all images together.
2. Inspect the image count and order. Files are numbered by filename; optionally choose **Shuffle the order before uploading**.
3. Add the optional **Traits file** and review any parsing message.
4. Under **2. Mint settings**, enter the **NFT name** prefix, up to 20 characters. Items receive numbered names such as `Collection #1`.
5. Set **Price per NFT (SOL)**, **Minting opens**, optional **Minting closes** and optional **Limit per wallet**. Date/time inputs use the browser's local time; check your timezone before announcing an opening time.
6. Review the storage quote, setup network cost and what each buyer will pay.
7. Choose **3. Pay for storage and upload**. Approve the storage payment and keep the tab open until all files are stored.
8. Recheck the final settings, then choose **4. Create the public mint** and approve the separate on-chain setup transaction.
9. Confirm that the collection page displays the public **Mint** panel and correct rules.

Setting the creator price to zero does not remove SPAWN's public-mint fee or network costs. Buyers receive the next item in number order. Uploaded images are already public; this is not a hidden-art reveal system.

## Recover an interruption

| Situation                        | Recovery                                                                                                                   |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Storage upload stopped           | Return in the same browser, select the exact original images and choose **Continue the upload**.                           |
| Files/names locked               | Upload preparation has begun; use the original set.                                                                        |
| Setup transaction pending        | Choose **Finish launching** and inspect the existing signature.                                                            |
| Need to restart before launch    | **Start over** warns that paid storage is not refunded and uploaded files remain public. Read the warning before using it. |
| Wrong creator wallet             | Reconnect the original collection wallet.                                                                                  |
| Invalid traits file              | Use valid JSON, exact filenames and nonempty trait names/values.                                                           |
| Rules need changing after launch | SPAWN currently provides no edit control for the price, times or per-wallet limit after launch.                            |

Keep local browser data and original files until completion. Do not start a second paid setup simply because confirmation or indexing is slow.

**Next:** share the collection URL and [buyer instructions](21-minting-and-collecting.md).

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
