# 16. Find tokenized stocks and ETFs

**Open:** [Markets](https://spawnmeme.com/markets). Tokenized asset discovery uses the same market search and swap interface as other supported Solana tokens; there is no separate SPAWN brokerage account flow described here.

## Research before using the tool

1. Obtain the exact mint from the asset issuer's official source.
2. Search that mint in Markets. Names such as stock tickers can be copied by unrelated tokens.
3. Open the market details and confirm the mint again.
4. Review available liquidity, chart, pricing and route availability.
5. Read the issuer's current asset-specific terms, geographic eligibility and any redemption requirements.
6. If you are eligible and choose to proceed, follow the [Swap guide](15-spawn-swap.md) and review the live quote.

The platform's feature catalogue includes examples such as GOOGLx, GLDx and STRCx. These are examples of discoverable tokenized exposure, not a promise that a specific route is available at all times.

## What you are using

A tokenized stock or ETF product is a token with its own issuer, structure and restrictions. Do not assume holding it grants the same rights as a directly registered share, including voting rights or unrestricted redemption. Price, fees, transferability and eligibility depend on the particular product and its current terms.

SPAWN discovery and routing do not establish issuer approval, legal eligibility or a guarantee that the token tracks a reference asset exactly. Use official issuer information to resolve those questions.

## Troubleshooting

| Problem                                | What to check                                                                                         |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Many similar names                     | Compare the complete mint with the issuer's official listing.                                         |
| Asset not found                        | Provider coverage may be incomplete; do not substitute a similarly named token.                       |
| Price differs from another source      | Compare timestamp, currency, venue and the precise product. The quote is for the token on that route. |
| No executable route                    | Market discovery does not guarantee available liquidity or current trading support.                   |
| Unsure about eligibility or redemption | Consult the issuer's current official terms before attempting a transaction.                          |

Costs are those of the live swap route plus any applicable issuer/product costs. SPAWN's generic swap quote should not be treated as a complete description of the product's economics.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
