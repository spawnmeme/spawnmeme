# 43. Token alerts in Telegram

Get a private Telegram message when a token's market cap moves or its bonding curve reaches a milestone.

**Open:** any token page on [the Spawn Feed](https://spawnmeme.com/launchpad) and tap **Alerts**, or message [@spawnmeme_bot](https://t.me/spawnmeme_bot).

## Before you start

* Alerts cover SPAWN tokens that are still on their bonding curve. Graduated tokens are not covered.
* Alerts arrive in a private chat with the bot, so you need Telegram.
* Checks run every five minutes. A message can arrive a few minutes after the move.
* You can have 20 active alerts.
* Alerts are information, not advice.

## Set an alert

1. Open the token page and tap **Alerts**. Telegram opens a private chat with the bot.
2. Press **Start** if Telegram asks.
3. Choose one:
   * **Up 25%** or **2x**: one message when the market cap reaches that level.
   * **Down 25%**: one message if it falls that far.
   * **Curve milestones**: a message at 25%, 50% and 75% of the bonding curve, and again at graduation.
4. The bot confirms the alert and the level it is watching.

Price alerts are measured from the market cap at the moment you set them, and each sends once. You can also send `/alert` followed by a mint address to the bot.

Launched a token? Choose **Curve milestones** on your own token page to follow its progress.

## See or remove alerts

Send `/alerts` to the bot in the private chat. Tap an alert in the list to remove it.

## Troubleshooting

| Symptom | What to do |
| --- | --- |
| The bot replies in a group that alerts are private | Tap **Open alerts** and continue in the private chat. |
| "The price for this token has not been read yet" | Try again in a few minutes. |
| "You already have this alert" | Each token and alert type can be set once at a time. |
| "You can have 20 active alerts" | Send `/alerts` and remove one first. |
| No message arrived | Check you have not blocked or muted the bot, and remember the five-minute check. |
| Your alert ended at graduation | Price alerts stop when a token graduates. The bot tells you when that happens. |

**Success:** the bot confirms the alert, and `/alerts` lists it.

***

[Guide home](../README.md) · [Telegram command reference](../reference-and-support/36-telegram-commands.md) · [Trade on a token page](../discover-and-trade/13-token-trading.md)
