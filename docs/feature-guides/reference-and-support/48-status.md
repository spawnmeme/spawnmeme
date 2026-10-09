# 48. Check whether SPAWN is working

Use the Status page to see live checks of SPAWN's services.

**Open:** [Status](https://spawnmeme.com/status). It is linked in the footer.

## What is checked

The page checks these from your own browser and rechecks every minute while it is open:

* Token launches
* Solana connection
* SOL price
* Markets and SPAWN Swap data
* Buy Bot and Trending
* News and updates

Each row shows **Working**, **Degraded** or **Not responding**, with a short note. Press **Check again** to recheck now.

## What it does not cover

The page covers SPAWN's own services. Solana itself, your wallet app and other exchanges can have problems of their own that do not show here. For a pending or failed transaction, look up its signature in the [Explorer](https://spawnmeme.com/explorer).

## What to do with the result

| Result | What to do |
| --- | --- |
| All systems are working, but something fails for you | Follow [Troubleshooting](38-troubleshooting.md). Check your wallet, browser and connection too; green checks do not rule out a feature-specific problem. |
| A service is **Degraded** | It is slow or catching up. Wait a few minutes before retrying a paid action. |
| A service is **Not responding** | Do not repeat a payment. Keep any transaction signature and check back shortly. |
| Buy Bot and Trending is "catching up" | Buy alerts, the Trending board and token alerts may be delayed. |

**Success:** you know whether to retry, wait or look at your own setup.

***

[Guide home](../README.md) · [Troubleshooting](38-troubleshooting.md) · [Get help](39-support-and-safety.md)
