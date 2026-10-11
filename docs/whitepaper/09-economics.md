# 9. Fees and creator economics

## Economic model

SPAWN charges for selected platform actions and provides separately priced visibility products. It also relies on network, protocol, storage and infrastructure services whose costs should be distinguished from the platform's own charges.

The table below reflects the documented schedule and application defaults reviewed for this edition. It is not a guarantee of the total payable for a future transaction. Live configuration, pool settings and the wallet preview take precedence.

| Action                                   | Documented platform charge          | Context                                                    |
| ---------------------------------------- | ----------------------------------- | ---------------------------------------------------------- |
| Publish a Spawn Page                     | No site deployment fee              | Paid Spawn Kit upgrades are not offered             |
| Deploy a token                           | 0.025 SOL default                   | The live configuration supplies the actual launch fee      |
| Trade a new SPAWN bonding pool           | 1.2% base fee                       | Other protocol and network costs may apply                 |
| Spawn Swap                               | 0.3% default platform fee           | The route shows the applicable fee                         |
| Create an NFT collection                 | 0.1 SOL                             | Documented holder discount may apply                       |
| Mint an individual NFT into a collection | 0.005 SOL                           | Storage, rent and protocol costs are additional            |
| Buy through a public NFT mint            | 3% of mint price, minimum 0.005 SOL | Paid on top of the creator's price                         |
| Paid visibility                          | Order-specific quote                | Duration, placement and availability depend on the product |

Creator airdrops carry a **0.001 SOL per recipient** SPAWN fee, plus transferred tokens, network fees and any required account creation costs. **Limit orders earn SPAWN no fee**; their minimum value is $10, with network and any Jupiter charges separate. SPAWN has no subscriptions or card checkout, and paid Spawn Kit artwork upgrades are not offered.

## Additional transaction costs

Users may also pay Solana transaction fees, account rent, protocol charges, NFT storage and the value of an initial purchase. The platform headline fee is not the total wallet balance required. A price denominated in SOL also changes in fiat value as market prices move.

Simulation and wallet review help reveal the proposed action, but do not promise that a submitted transaction will execute successfully or without network costs.

## Token creator fees

Tokens launched with creator fees earn the launch wallet about **0.25% of each bonding-curve trade**, from the first trade. This is included in the existing **1.2% trading fee**, not an additional charge. Tokens launched before creator fees were enabled retain a permanent 0% creator share on the curve. After graduation, creators can claim the eligible trading fees of the locked Meteora pool, after Meteora’s share. Earnings require trading and may be zero.

After graduation, the fee page describes a 1% base fee at the Meteora pool. The creator wallet holds the locked position and can claim its eligible share after protocol deductions through the Creator Dashboard. Those claimable fees and the underlying locked liquidity are different rights.

Creator-fee launches can earn before graduation when trades occur. Legacy launches start earning eligible pool fees only after graduation and subsequent trading. No fixed income or trading volume is promised.

## NFT creator proceeds

The creator receives the public mint price directly under the documented flow. SPAWN's public-mint fee is paid by the buyer on top. Collection royalties are set between 0% and 10% in the documented creation flow and go to the creator when honored by the resale venue; SPAWN takes no royalty share under that schedule.

Royalties are conditional on marketplace behavior. They should not be presented as guaranteed recurring income.

## Sustainability

Transaction fees and paid services provide a mechanism to fund ongoing operation and development. This edition does not disclose financial statements, profitability, treasury balances or a predetermined allocation of platform revenue. The existence of a fee model does not establish commercial sustainability by itself.

## Curve split and claim flow

The current split of a 1.2% curve fee is 0.24% of trade value to Meteora, 0.2496% to the creator and 0.7104% to SPAWN before referral payouts. The creator receives 26% of the 0.96% remaining after Meteora’s share. Public copy rounds 0.2496% to about 0.25%. Existing pools keep their permanent settings.

Creator fees accrue in the pool without expiry. Only the launch wallet can claim; SPAWN does not hold those balances. **Claim curve fees** collects accrued curve fees, and **Claim fees** collects graduated pool fees. Each claim requires wallet approval and a network fee. See [50. Claim your creator fees](../feature-guides/launch-and-manage-tokens/50-claim-creator-fees.md).


***

[Previous: 8. Community, quests, referrals and airdrops](08-community.md) · [Next: 10. The SPAWN token](10-spawn-token.md)
