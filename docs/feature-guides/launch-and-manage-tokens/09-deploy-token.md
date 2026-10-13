# 09. Deploy a Solana token

**Open:** [Deploy a Token](https://spawnmeme.com/create-token). The standalone launch flow requires a supported Solana wallet, not an email signup. To attach a launch to an existing account project, use that project's **Set up token** action.

## Prepare before starting

* Token name: 1–32 characters.
* Ticker: 2–10 uppercase letters or numbers, without spaces.
* Required artwork: PNG, JPG or WebP under 5 MB.
* Description and any website, X/Twitter, Telegram or Discord links.
* Enough SOL for the quoted platform fee, network/account costs and optional first buy.

Check everything carefully. The launch image and identity become part of locked token metadata. Name and ticker are also locked once the launch draft is created; use a new draft if they need changing.

## Launch step by step

1. Choose **Continue with wallet**, or **Verify wallet / load my launches** if already connected. Select the intended launch wallet.
2. Sign the free ownership message when requested. This is separate from the launch payment.
3. Check **My wallet launches** for a draft or completed launch. Choose **Resume draft** if continuing one.
4. Complete the fields and inspect the artwork. Website links must begin with `http://` or `https://`.
5. If **Token standard** is offered, choose **Classic** unless you specifically need Token-2022. The latter can have compatibility limits in older tools; it uses the same SPAWN curve, fees and fixed-supply model.
6. Optionally enter **Your first buy** in SOL. It is capped at 5% of supply; use the current displayed maximum. Leave it empty or zero for no first buy. It increases the total payment and is public on the token page.
7. Review the current platform fee and any promotional status. Choose **Deploy Token**.
8. Review the wallet transaction and approve promptly. The page advises approval within about 20 seconds because the prepared transaction can expire.
9. Keep the page open through confirmation and registration. Save the signature.
10. Open **View token** and confirm the mint, creator wallet, image and launch information.

The standard launch creates a Meteora bonding-curve pool with one billion tokens and six decimals. The token's full mint address identifies it; its name or ticker alone does not.

## Recovery: check before launching again

| Message or state                        | Correct action                                                                                                                                      |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Deployments paused**                  | Wait for the official activation announcement. Do not pay through a third party to bypass it.                                                       |
| Draft already exists                    | Resume it or use **Start another token** only when you intend a separate launch.                                                                    |
| Already launched                        | Open **View token**; do not create a replacement because registration was slow.                                                                     |
| Quote changed/expired and nothing sent  | Review the new price and request a fresh deployment transaction.                                                                                    |
| Approval too slow and nothing sent      | Retry with a fresh transaction and approve promptly.                                                                                                |
| Signature mismatch/account changed      | Reconnect the intended launch wallet. Follow the message indicating whether anything was sent.                                                      |
| Submitted launch / registration pending | Keep the signature and choose **Retry registration**. This checks the existing transaction; it is the recovery path instead of another paid launch. |
| Confirmed on-chain but still not listed | Save the mint and signature, retry registration, then contact support if it remains unresolved.                                                     |

Do not erase saved receipts while a launch is pending. A transaction signature is evidence to investigate, not proof that every part of the site has finished updating.

**Next:** [Creator Dashboard](11-creator-dashboard.md), [Buy Bot](../telegram-and-promotion/28-buybot-setup.md) and [launch fees](../reference-and-support/37-fees.md).

## Creator earnings for new launches

Tokens launched with creator fees earn the launch wallet about **0.25% of each bonding-curve trade**, from the first trade. This is included in the existing **1.2% trading fee**, not an additional charge. Tokens launched before creator fees were enabled retain a permanent 0% creator share on the curve. After graduation, creators can claim the eligible trading fees of the locked Meteora pool, after Meteora’s share. Earnings require trading and may be zero.

Keep access to the launch wallet: it is required to claim. Read [50. Claim your creator fees](50-claim-creator-fees.md).

## Check your launch after publication

The launch flow may use an available branded mint ending in `spwn`, with a normal mint as fallback. A suffix is not guaranteed and does not prove authenticity: compare the full address. Current launches lock metadata at creation; eligible older Classic tokens can use [Lock token metadata](55-lock-token-metadata.md). You can also inspect or create [token locks](54-token-locks.md), review your [creator profile](52-creator-profiles.md), and manage a [DEX Screener profile](../telegram-and-promotion/57-dex-screener-profile.md). These are separate actions with separate requirements.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
