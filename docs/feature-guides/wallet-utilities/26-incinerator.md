# 26. Token Incinerator and rent recovery

**Open:** [Token Incinerator](https://spawnmeme.com/burn). Connect the wallet whose token accounts you want to inspect.

## Choose the correct action

**Burn tokens** permanently destroys a chosen amount and reduces that mint's supply. It is irreversible and does not pay you the token's market value. **Close empty accounts** reclaims the account rent held in eligible zero-balance accounts. You do not need to burn valuable tokens to use the empty-account tool.

## Burn a chosen amount

1. In **Burn tokens**, choose the token account carefully.
2. Check the full mint and balance. External tokens may appear without a friendly name.
3. Enter the exact amount to destroy.
4. If burning the entire balance, decide whether to also close the now-empty account, when offered.
5. Read and tick the permanent-destruction acknowledgement.
6. Use the burn action, inspect the wallet transaction and approve only the intended mint and amount.
7. Check the confirmation and **View transaction**.

## Reclaim empty-account rent

1. Read **Empty accounts** and the estimated recoverable SOL.
2. Choose **Close \[number] and get back about \[amount] SOL**.
3. Review and approve the closure transaction.
4. Wait for confirmation. If more accounts remain, the page offers another batch.

Recovered rent is the balance in those accounts, less applicable transaction costs; the display is approximate. Buying or receiving the token again can require recreating its account and paying rent again. Closing a wrapped-SOL account can also affect the [referral instant bonus](../community-and-rewards/25-referrals.md).

## Costs and limits

The current Incinerator takes no SPAWN platform fee; Solana network costs apply. Some token accounts may be ineligible because of their program rules, extensions, frozen state or authority. Follow the actual read/simulation result rather than assuming every wallet asset can be burned or closed here.

## Troubleshooting

| Problem                                       | Resolution                                                                                   |
| --------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Token not identifiable                        | Compare its complete mint with a trusted source or Explorer before selecting it.             |
| Amount rejected                               | Use a positive amount within your balance and the token's decimal precision.                 |
| No empty accounts                             | None of the readable eligible accounts currently has a zero balance.                         |
| Closure/burn failed                           | Inspect the error and signature; check account state and fee balance before a fresh attempt. |
| Token still appears after confirmed full burn | Refresh wallet data; an empty account or cached metadata may still be displayed.             |
| Burned the wrong token                        | A confirmed burn cannot be undone by SPAWN or support.                                       |

Do not burn an asset solely because someone claims doing so will increase its price. This feature provides an on-chain action, not a price outcome.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
