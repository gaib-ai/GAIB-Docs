# PICE <--> sPICE

## Staking and Unstaking

Users can stake their **PICE** through GAIB's interface. A “Stake” transaction exchanges PICE for **sPICE**, a liquid receipt token representing the staked position. Conversely, an “Unstake” transaction returns staked PICE to the user, instantly updating balances upon confirmation on the blockchain.

A cooldown period of 14 days applies after unstaking, during which users cannot withdraw PICE. Once the cooldown expires, users can freely withdraw their unstaked PICE.

## Reward Mechanism

GAIB leverages a **token vault** approach—similar to Rocketpool’s rETH or Binance’s WBETH—to deliver rewards seamlessly.

1. **Vault Mechanics**
   * **No Rehypothecation**: Deposited PICE remains in the staking contract; it is not lent out or repurposed.
   * **Reward Accrual**: Protocol-level revenue is periodically deposited into the staking contract, increasing the value of sPICE in relation to PICE.
2. **Value Growth**
   * sPICE’s worth in PICE terms rises over time as protocol rewards flow in.
   * The **sPICE:PICE ratio** is calculated as: _sPICE_:PICE ratio = (total _sPICE_ supply) / (total _PICE_ staked + total protocol revenue deposited in _PICE_ terms)
   * Users often receive fewer sPICE tokens than the PICE they stake, but the total value matches. As the ratio increases, sPICE appreciates in PICE terms.&#x20;

When users unstake, they receive an amount of PICE equal to their initial stake plus accrued rewards, as reflected by the increased sPICE-to-PICE ratio.

## Important Notes

* **Stakers Need Not Take Extra Steps**\
  Simply holding sPICE accrues benefits automatically.
* **Fewer Tokens, Equivalent Value**\
  Receiving fewer sPICE tokens than PICE deposited is normal; the underlying value remains the same.
* **Cooldown Period**\
  After unstaking, stakers must wait 14 days before withdrawing PICE.

By aligning sPICE with real protocol growth through a transparent ratio mechanism, GAIB ensures that staking remains straightforward, secure, and rewarding.
