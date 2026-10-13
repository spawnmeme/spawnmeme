# 54. Inspect and create token locks

**Open:** a launched token page from [Spawn Feed](https://spawnmeme.com/launchpad).

The **Locked tokens** card reads supported Jupiter Lock and Streamflow locks from Solana. It shows tokens restricted by those schedules. This is separate from the permanently locked liquidity position created when a SPAWN token graduates.

## Inspect a lock

1. Review **Locked now**, the token amount and number of locks.
2. Compare **Locked by the creator** and **Next unlock**.
3. Read each schedule, including when unlocking begins and when it finishes.
4. Look for **Can be cancelled**. Such a lock may be ended early under its contract rules.
5. Open the linked Jupiter Lock escrow or Streamflow account on Solscan to inspect the record. Choose **Check again** to request a refresh.

Streamflow schedules are counted while they still restrict tokens, including eligible vesting schedules. A lock covers only the tokens in that contract; other holdings remain transferable.

## Creator workflow

If no locks are found, the connected creator may see **Lock your tokens**. This prompt is private to that wallet; a detected lock becomes visible to visitors.

1. Choose **Open Jupiter Lock** and verify the external service and token mint.
2. Connect the intended wallet and select the token, amount and unlocking schedule.
3. Review cancellation settings, costs and the complete transaction in that service before approving.
4. Return to the SPAWN token page and choose **Check again**.

SPAWN displays the result and cannot unlock tokens for you. Check the provider's current terms and wallet request; do not assume every lock is cancellable or free.

## Missing or delayed results

The card may be absent when no supported lock is detected or its data is unavailable. Absence is not proof that no lock exists anywhere. Check the external record and retry after indexing catches up.

**Success:** the expected lock, amount and schedule are visible and agree with the external contract.

***

[Guide home](../README.md) · [Get help](https://spawnmeme.com/help)
