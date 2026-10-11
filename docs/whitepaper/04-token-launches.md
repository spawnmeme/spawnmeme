# 4. Token launches and graduation

## Launch preparation

The documented standard launch creates a Solana token and a Meteora bonding-curve pool through a transaction approved by the creator. The published standard describes a supply of **1,000,000,000 tokens**, **six decimals** and **SOL as the quote asset**. The creator must review the actual configuration presented by the deployment flow.

The process starts with the token's name, ticker, image, description and links. SPAWN prepares and simulates the transaction before wallet approval. The documented flow removes mint and freeze authority, locks token metadata and can include an optional initial creator purchase capped at 5% of supply.

These properties should be checked on the resulting token and pool. A familiar name, logo or address suffix is not proof that a launch uses the expected settings.

## Approval and confirmation

The creator reviews the complete transaction and its costs in the wallet. Token creation, pool creation, the platform launch fee and any supported initial buy form the documented launch transaction.

After execution, SPAWN reads the confirmed result and verifies launch conditions before listing the token. Its documented checks cover the token and pool, standard settings, fee payment and initial-buy limit. A transaction signature alone does not prove successful execution.

If a transaction remains pending or a page loses connection, users should inspect its status before repeating the launch. Network fees may apply to a submitted transaction that fails; local preparation or simulation is a different stage.

## Curve trading

Buy and sell transactions interact with the pool. Price depends on the deployed curve and pool state. The documented model uses a custom square-root-price curve; this paper does not substitute a simplified formula for the actual on-chain configuration.

The fee page describes a 1.2% base trading fee for new SPAWN bonding pools. Protocol deductions and network costs remain relevant. Price can move downward, and a pool's existence does not ensure liquid trading at a user's preferred price.

## Graduation

Graduation follows the pool's on-chain curve and Meteora rules. This edition does not assign a universal SOL graduation threshold. Users should inspect the current pool progress and configuration rather than relying on a promotional approximation.

Under the documented model, graduated liquidity is permanently locked in a Meteora position held by the creator wallet. The position's eligible fee income can be claimed separately through the Creator Dashboard. Claiming fees does not withdraw the locked liquidity.

A liquidity lock is a specific restriction on a position. It is not a guarantee of token value, active trading, creator conduct or protocol security.

## Creator earnings before and after graduation

Tokens launched with creator fees earn the launch wallet about **0.25% of each bonding-curve trade**, from the first trade. This is included in the existing **1.2% trading fee**, not an additional charge. Tokens launched before creator fees were enabled retain a permanent 0% creator share on the curve. After graduation, creators can claim the eligible trading fees of the locked Meteora pool, after Meteora’s share. Earnings require trading and may be zero.

Accrued curve fees stay claimable after graduation. The graduated pool’s fees are a separate claim; locked liquidity remains inaccessible. See [50. Claim your creator fees](../feature-guides/launch-and-manage-tokens/50-claim-creator-fees.md).


***

[Previous: 3. Architecture and transaction boundaries](03-architecture.md) · [Next: 5. Markets, trading and wallet tools](05-markets-wallet.md)
