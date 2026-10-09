# 28. Set up the Telegram Buy Bot

**Open:** [Buy Bot setup](https://spawnmeme.com/trending#buybot). The Buy Bot publishes supported, confirmed buy activity into a Telegram community; it does not buy tokens for members.

## Requirements

* A verified SPAWN token on an **active supported bonding curve**.
* A Telegram group you administer from a visible personal admin account.
* [@spawnmeme\_bot](https://t.me/spawnmeme_bot) added as a group administrator with the required posting/media permissions.
* Available platform monitoring capacity and enabled creator connections.

Graduated pools and arbitrary external Solana tokens are not currently supported. Connecting a token to a group does not prove that the group owns or officially represents that token.

## Connect and preview

1. Choose the token on the setup page, or paste its full mint.
2. Add the official bot to your project group and promote it to administrator.
3. From your visible group-admin account, send:

```
/buybot YOUR_TOKEN_MINT
```

4. Check the connected-token confirmation and `/ca` response.
5. Open settings and post a labelled test:

```
/buybotsettings
/buybotpreview 0.5
```

6. Confirm that the sample displays the intended token, media and buttons.

Replace `YOUR_TOKEN_MINT` with the real address. The preview is synthetic: it does not buy, change rankings or count as payment. Configuration and previews require a visible administrator, not an anonymous admin/channel identity.

## Alert information

| Field                      | Interpretation                                                       |
| -------------------------- | -------------------------------------------------------------------- |
| Buy amount and transaction | Supported confirmed activity; use the transaction link to inspect it |
| Market cap (est.)          | Pool-price and supply estimate, not exit liquidity                   |
| Bonding curve              | Progress against this token's configured migration threshold         |
| Holders                    | Indexed data when available; absence is not zero                     |
| USD value                  | Optional approximate SOL conversion                                  |
| Buyer badge                | Only shown when supported by verified history/evidence               |
| Trending rank              | Current qualifying organic activity rank                             |
| Promoted badge             | Separately purchased sponsored visibility                            |

One token is connected per group. Several groups can follow the same supported token subject to capacity. The main SPAWN group retains its official configuration.

## Pause or resume

Use `/stopbuybot` to pause alerts and `/resumebuybot` to resume. Use `/buybotsettings` to inspect the group's minimum buy amount and display options. Settings apply to that group.

## Troubleshooting

| Symptom                               | Resolution                                                                                                                   |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Not an admin / cannot verify admin    | Use a visible group-admin account and confirm both your role and the bot's role.                                             |
| Unsupported token                     | Check full mint, verified SPAWN registration and active curve state.                                                         |
| Capacity reached / activation pending | Wait for capacity or activation; paying for promotion does not bypass support limits.                                        |
| Sample works, real buy missing        | Check confirmation, alert minimum, pause state and supported pool. Allow indexing/monitoring time.                           |
| Media alerts fail                     | Verify Telegram posting/media permissions and [media limits](29-buybot-customization.md).                                   |
| Market cap or curve unavailable       | Data could not be read/verified for that alert. Recheck the token page and report persistent errors with mint and signature. |
| Holder count unavailable              | Provider indexing may lag; it is not evidence of zero holders.                                                               |
| Buy appeared once but not again       | Delivery avoids duplicate announcements; a missing duplicate is not necessarily a fault.                                     |

Buy alerts are free for supported tokens. Timing depends on confirmation and monitoring; previews do not test every live-data condition. [Customize alerts](29-buybot-customization.md) or [use Trending](30-trending.md).

## Token refresh and private alerts

The shared five-minute refresh records supported tokens’ SOL raised and market cap, marks graduation when the curve completes, and sends [private token alerts](43-token-alerts.md). Price alerts stop at graduation; Curve milestones can notify the graduation event. This does not extend Buy Bot trade monitoring to graduated pools. Refresh delays can delay notifications.


***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
