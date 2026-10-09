# 29. Customize Buy Bot media, tiers and buttons

Work in the connected project group as a visible administrator. Start with `/buybotsettings`; it provides controls and instructions for the same settings below.

## Set base media

Send a photo, GIF/animation or MP4 video with `/buybotimage` as its caption, or reply to existing media with `/buybotimage`.

| Media         | Maximum | Telegram attachment mode |
| ------------- | ------- | ------------------------ |
| Photo         | 10 MB   | Photo                    |
| GIF/animation | 50 MB   | Animation/GIF            |
| MP4 video     | 50 MB   | Video                    |

Use Telegram media mode, not a generic document attachment. A file with a renamed extension is not necessarily valid media. Use `/buybotimage reset` to restore the base token artwork. This changes group alert presentation, not the token's immutable image.

## Add buy-size media tiers

Attach media with, or reply to it using:

```
/buybottier medium 1
/buybottier large 5
```

These example thresholds are in SOL. Buys below 1 SOL use base media, buys from 1 to below 5 SOL use medium media, and buys of at least 5 SOL use large media. The highest qualifying threshold wins, and large must be above medium. Replace the numbers with your intended valid thresholds.

A tier command without media can change an existing tier's threshold. Remove tiers separately:

```
/buybottier medium reset
/buybottier large reset
```

Resetting base media does not remove the tiers.

## Tune alert size and display

| Example command                        | Effect                                          |
| -------------------------------------- | ----------------------------------------------- |
| `/buybotmin 0.01`                      | Alert minimum in SOL; it does not limit trading |
| `/buybotemoji 🔥`                      | Use standard emoji in the buy bar               |
| `/buybotemoji off`                     | Hide the emoji bar                              |
| `/buybotstep 0.1`                      | One repeated emoji unit per 0.1 SOL             |
| `/buybotusd on` / `/buybotusd off`     | Show/hide approximate USD buy value             |
| `/buybotlinks on` / `/buybotlinks off` | Show/hide social buttons                        |
| `/buybotpreview 0.5`                   | Preview a labelled 0.5 SOL sample               |

Up to three standard emoji are supported. Telegram premium custom emoji are not supported. Emoji bars are capped to fit captions; a `+` indicates the cap, not missing buy value. The step must be within the bot's accepted range, currently 0.001–1,000 SOL.

## Set social buttons

```
/buybotsocial website https://example.com
/buybotsocial x https://x.com/yourproject
/buybotsocial telegram https://t.me/yourgroup
```

Replace the example URLs with your public HTTPS links. To hide one button, use `/buybotsocial x off`. To restore its token-metadata value, use `/buybotsocial x reset`. Replace `x` with `website` or `telegram` as needed.

## Verify your configuration

Post sample previews below, at and above your tier thresholds. Check media, emoji, social destinations and the selected token. A preview never records a real buy or purchases promotion.

## Troubleshooting

| Problem                            | Resolution                                                                   |
| ---------------------------------- | ---------------------------------------------------------------------------- |
| Media rejected                     | Check size, supported format, attachment mode and bot permissions.           |
| Large tier rejected                | Set a large threshold greater than medium.                                   |
| Wrong tier image                   | Check the SOL thresholds and remember that the largest qualifying tier wins. |
| Old tier remains after image reset | Reset that tier explicitly.                                                  |
| No social buttons                  | Turn links on and check per-button off/reset state and HTTPS URL validity.   |
| Bar looks shorter than expected    | Check step size and display cap.                                             |

These settings are free and local to the connected group. [Setup and live-alert troubleshooting](28-buybot-setup.md).

## Token refresh and private alerts

The shared five-minute refresh records supported tokens’ SOL raised and market cap, marks graduation when the curve completes, and sends [private token alerts](43-token-alerts.md). Price alerts stop at graduation; Curve milestones can notify the graduation event. This does not extend Buy Bot trade monitoring to graduated pools. Refresh delays can delay notifications.


***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
