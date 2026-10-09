# Frequently asked questions

## Getting started

### What can I do with SPAWN?

Create a project identity and public presence, launch Solana tokens, explore markets and swap routes, create NFT collections, and connect supported community tools. The [getting-started guide](getting-started.md) explains the main paths.

### Do I need to build a website first?

No. A website is optional. If you already have your identity and artwork, start at [Deploy a Token](https://spawnmeme.com/create-token).

### Do I need an email account?

No email signup is required for wallet-only token deployment. Connect and verify your Solana wallet, then use the same wallet to return to your drafts and launched tokens. Some other features use an account. Wallet verification and the actual launch transaction are separate approvals.

### Can I use SPAWN on my phone?

Use the mobile site and, where needed, open it inside your Solana wallet's browser. If a wallet connection does not complete, check that you are using the intended wallet and browser context before trying again.

## Tokens, wallets and swaps

### How do I identify the correct token?

Compare the full mint address with the project's official source. Names and symbols can be duplicated. For SPAWN's own token, use the official website and the main bot's `/ca` command.

### Can I connect MetaMask?

Yes. Choose MetaMask in SPAWN’s wallet selector and follow the Solana connection prompts. Device and browser support varies. See the [wallet guide](markets-and-wallet.md).

### Why is a chart or swap route unavailable?

Chart coverage, pool support, liquidity and data availability vary by token. A token appearing in discovery does not guarantee an available trading route. See [Markets & Wallet](markets-and-wallet.md).

### Where do I check fees?

Review the quote or transaction screen and the current [Fees page](https://spawnmeme.com/fees). Different actions can have different costs; keep enough SOL for network costs as well.

### What should I do if a transaction is pending?

Check its signature and status on the explorer before repeating the action. Keep the public transaction signature and page URL for a support request. Do not include private wallet credentials.

## Telegram and Trending

### Why will Buy Bot not connect my token?

Check that the bot and your visible account are group administrators, that the mint is correct, and that the token has a supported active SPAWN bonding curve. Coverage and monitoring capacity also apply. See the [Buy Bot guide](buy-bot-and-trending.md).

### Will every buy alert appear immediately?

Delivery depends on supported confirmed activity, indexing and monitoring. SPAWN-site buys can trigger alerts promptly; background monitoring helps catch other supported activity. Network and service conditions can add delays.

### Can I use GIFs or video for buy alerts?

Yes. Use a photo, GIF/animation or MP4 video with `/buybotimage` as its caption, or reply to the media with the command. Photos support up to 10 MB; animation/video up to 50 MB. Send media in its normal Telegram mode, not as a document. You can also configure medium and large buy-size tiers.

### Why does market cap, curve progress or holder count say unavailable?

Optional statistics depend on confirmed pool configuration, mint data and external data sources. If a source cannot be confirmed, the alert labels the statistic unavailable instead of guessing. See the [buybot guide](buy-bot-and-trending.md).

### Do sample previews create activity?

No. `/buybotpreview` uses clearly labelled example data and does not create a trade, affect a rank or count as a payment.

### Does paying for visibility improve the organic rank?

Paid promotions are displayed separately. Organic ranks reflect qualifying activity in the supported monitored set. Buying visibility does not purchase an organic rank.

### Can I send SOL directly to activate Trending?

Create an order on the official [Trending page](https://spawnmeme.com/trending) and follow the order-specific instructions. An unsolicited transfer cannot be assumed to activate a campaign.

## Updates and promotions

### Where can I read platform announcements?

Use [News & Updates](https://spawnmeme.com/updates) or `/updates` in the SPAWN bot. Articles have individual shareable links. [Linktree](https://linktr.ee/spawnmeme) and `/links` collect official destinations.

### Does Launch Week make every launch cost free?

No. The October 8–15, 2026 promotion waives the 0.025 SOL platform deployment fee during its stated window. Network fees, account creation costs and optional first buys still apply. See [the offer details](launch-week.md) and the current launch quote.

## NFTs, quests and this repository

### Does calling an NFT “1 of 1” enforce its supply?

No. Its actual collection and mint configuration must match that claim. Review the settings and metadata before publishing. See [NFTs & airdrops](nfts-and-airdrops.md).

### Do quests or whitelist participation guarantee a reward?

No. Check the relevant campaign's current eligibility, rules and allocation details. Participation and points alone do not guarantee a token allocation or financial value.

### Is this the application source code?

This is SPAWN's public documentation and community repository. It does not contain the production application, wallet credentials or deployment secrets. Use [spawnmeme.com](https://spawnmeme.com) to access the platform.

### Where can I suggest a feature?

Use the repository's [issue chooser](https://github.com/spawnmeme/spawnmeme/issues/new/choose). Explain the problem, who it affects and the outcome you want. For account help, use [Help](https://spawnmeme.com/help).

[Documentation hub](README.md) · [Back to SPAWN](../README.md)
