# 11. Security, controls and limitations

## User authorization

The documented transaction model keeps user signing authority in the wallet. Users should never provide a seed phrase or private key to a website, Telegram administrator, support account or GitHub issue.

Connecting a wallet, signing a message and signing an asset-moving transaction are different actions. Each request deserves review. Non-custodial authorization does not eliminate risks from deceptive interfaces, compromised accounts or instructions the user approves by mistake.

## Verification and recovery boundaries

The full token mint, transaction signature, on-chain authorities and pool configuration are the relevant verification records. Screenshots, display names and bot posts are supporting information rather than substitutes for those records.

When an interface shows a pending action, inspect the transaction status before repeating it. Keep public identifiers for support, but remove private or sensitive information from screenshots and issue reports.

SPAWN can moderate hosted content and operate its application services. Those controls are different from reversing an executed blockchain transaction. A hidden project page does not erase an on-chain token.

## Risk categories

| Risk                          | Practical implication                                                       |
| ----------------------------- | --------------------------------------------------------------------------- |
| Smart contracts and protocols | Bugs, dependencies or changed configurations may affect funds and execution |
| Liquidity and price movement  | An asset may be difficult to sell or lose substantial value                 |
| Wallet and account compromise | An attacker may obtain access or induce harmful approvals                   |
| Data and infrastructure       | RPC, indexing, storage or hosting failures can interrupt the interface      |
| Activity manipulation         | Rankings and apparent participation can be distorted                        |
| Permanent publication         | NFT files and blockchain records may not be retractable                     |
| Creator and content conduct   | A technical launch does not validate promises or ownership claims           |

These categories are relevant to using the platform; they are not a claim that every risk can be detected or prevented.

## Privacy and service dependencies

Wallet addresses and transactions are public blockchain information. Hosted account details and project records have a different lifecycle. Users should review the site's current privacy and service terms before supplying personal information or publishing material.

This paper does not claim that all application data is decentralized, that every service remains available without SPAWN, or that a third-party audit has verified the complete system.

## Reporting concerns

Use [Responsible disclosure](../feature-guides/reference-and-support/49-responsible-disclosure.md) for private security reports; follow the published testing rules and never include private keys or seed phrases. SPAWN does not run a paid bug bounty. Use [Report](../feature-guides/reference-and-support/46-report.md) for content moderation and [Status](../feature-guides/reference-and-support/48-status.md) for browser-based service checks. Status checks do not establish chain-wide or wallet-wide health. The [Help page](https://spawnmeme.com/help) remains available for general support.

## Open-order funds

A swap uses a current quote, with funds in the wallet until the transaction executes. A limit order waits for the selected dollar price with funds deposited in your own Jupiter vault. SPAWN does not hold the deposit. Expired orders require withdrawal; cancellation also requires completing the withdrawal. Only the connected owner wallet can deposit or withdraw.

## Interpreting inspection labels

RugCheck findings, holder concentration, lock schedules, creator profiles and DEX paid status answer different questions. No one label guarantees safety. Some token locks can be cancelled; a locked balance does not restrict a creator's other wallets. Immutability prevents metadata edits but does not independently guarantee the permanence of external file hosting. Download the Android APK through the official page and compare the fingerprint for that release. Store submission is not store approval.

***

[Previous: 10. The SPAWN token](10-spawn-token.md) · [Next: 12. Roadmap: The Hatching Plan](12-roadmap.md)
