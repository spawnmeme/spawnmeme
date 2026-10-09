# 10. Prepare a launch in Telegram

**Open:** [@spawnmeme\_bot](https://t.me/spawnmeme_bot?start=launch). The bot prepares a draft; the final on-chain launch happens on SPAWN with your wallet.

## Prepare the draft

1. Open the bot's private conversation and send `/launch`. A group shortcut may direct you into the private flow.
2. Enter a token name of 1–32 characters.
3. Enter a ticker of 2–10 letters or numbers. The bot converts it to uppercase and removes a leading `$`.
4. Enter a description of up to 500 characters, or send `/skip`.
5. Send a PNG, JPG or WebP image under 5 MB, or `/skip` to add it on the site. Launch artwork has different limits from Buy Bot alert media.
6. Send your website, X and Telegram links, or `/skip`.
7. Review the completed draft and open **Open in browser**, **Open in Phantom** or **Open in Solflare**, as appropriate for your wallet.

Send `/cancel` to stop the collection flow. Starting `/launch` again begins a fresh collecting draft. The launch link expires 24 hours after that draft was created.

## Finish on SPAWN

1. Check that the opened address belongs to `spawnmeme.com`.
2. Review every prefilled field; add required artwork if you skipped it.
3. Connect and verify the wallet that should own the launch.
4. Review the current launch quote and any optional first buy.
5. Follow [Deploy a Token](09-deploy-token.md), sign the launch transaction and wait for confirmation.

The bot does not hold your keys or sign for you. A Telegram draft or “ready to launch” message does not mean a token exists yet. No seed phrase belongs in the chat.

## Troubleshooting

| Problem                           | Resolution                                                                               |
| --------------------------------- | ---------------------------------------------------------------------------------------- |
| Bot says launches are paused      | Wait for SPAWN's official announcement.                                                  |
| Name/ticker rejected              | Remove spaces from the ticker and respect the displayed limits.                          |
| Bot cannot save the image         | Use a supported still-image file under 5 MB, or skip and upload on the site.             |
| Links not recognized              | Send full public URLs, such as `https://x.com/yourproject`, then check the website form. |
| Launch link expired               | Send `/launch` to make a new draft; do not reuse an old link.                            |
| Wallet link opens the wrong app   | Use **Open in browser** and choose your wallet explicitly on SPAWN.                      |
| Payment sent but token not listed | Recover using **Retry registration** on the launch page, not a fresh Telegram launch.    |

Preparing the conversation is free. Normal launch, network and optional-buy costs apply when you approve the website transaction.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
