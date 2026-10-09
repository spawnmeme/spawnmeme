# 02. Connect a wallet and use mobile browsers

**Open:** [My Wallet](https://spawnmeme.com/wallet). SPAWN offers Phantom, Solflare, Backpack, SafePal and MetaMask connections when available in your browser.

## Before you start

Unlock your wallet and select the Solana account you intend to use. For a paid action, that account needs SOL on Solana. Owning tokens or another network's currency does not cover Solana transaction fees.

## Connect

1. Open SPAWN in a browser supported by your wallet. On mobile, the wallet's own browser is useful when available.
2. Choose the wallet by its name. Approve the connection request.
3. Compare the address shown by SPAWN with the full address in your wallet.
4. If the feature requests a **message signature**, read it and approve only the expected SPAWN ownership request. A verification message does not send SOL.
5. When performing a paid action, review the separate **transaction** request, its account, amounts and instructions.

Use **Disconnect** in My Wallet to clear SPAWN's selected connection. Then select a different wallet if needed. Changing accounts inside a wallet may update the site; always check the displayed address before continuing.

## MetaMask on Solana

Choose **MetaMask** explicitly. SPAWN's integration needs a Solana account and Solana signing support; an Ethereum connection alone is insufficient. Depending on your environment, the connection may use the installed wallet or a mobile/QR flow. Complete that flow, then return to the original SPAWN tab and verify the account.

If MetaMask unexpectedly opens Phantom, return to the site, disconnect the old selection and choose **MetaMask** again. Do not approve an unrelated wallet prompt. Record the page, device, browser and wallet version if the wrong redirect persists.

## Mobile checklist

* Open the official HTTPS address directly, rather than an embedded social-media preview.
* Keep the original page open while switching to the wallet to approve.
* Use one active launch/payment tab to avoid confusing old and new prompts.
* Review promptly: launch transactions can expire while waiting for approval.
* Preserve transaction signatures before closing a frozen or interrupted session.

## Troubleshooting

| Symptom                                                 | What to do                                                                                                                                                                                             |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Wallet not detected                                     | Unlock it and use its supported browser or extension. Named **Open in Phantom** or **Open in Backpack** links intentionally open those wallets.                                                        |
| Wrong account shown                                     | Disconnect, select the intended Solana account, reconnect and compare addresses.                                                                                                                       |
| Message signing unsupported                             | Use a wallet/environment that supports Solana message signing for ownership-based tools.                                                                                                               |
| Invalid signature or account changed                    | Check the selected account. If the error explicitly says nothing was sent, reconnect and obtain a new request.                                                                                         |
| Approval expired                                        | Check whether a signature exists. If nothing was sent, request a fresh transaction and approve promptly.                                                                                               |
| Site freezes or images never load in SafePal on Android | Compatibility issues have been reported and are not confirmed resolved. Preserve receipts, close the affected tab and try another supported environment. Report Android, SafePal and browser versions. |
| Works on iPhone but not Android                         | Treat them as separate environments; successful iPhone use does not confirm Android compatibility.                                                                                                     |

Do not clear browser storage as your first repair step: it can remove pending receipts, watchlists and upload-resume data. Never enter your seed phrase into SPAWN or send it to support.

**Success:** the expected Solana address appears and the requested feature can obtain the correct message or transaction signature. Connection itself has no platform fee.

## MetaMask authorization recovery

| Symptom | What to do |
| --- | --- |
| MetaMask says "The requested account and/or method has not been authorized by the user" | The saved authorization may have expired. SPAWN asks MetaMask to reconnect and retries. If it persists, disconnect on SPAWN, select **MetaMask**, approve the Solana account and retry. This authorization failure sends no transaction and charges nothing. |


***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
