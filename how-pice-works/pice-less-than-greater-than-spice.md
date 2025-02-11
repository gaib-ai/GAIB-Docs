# USDai <--> sUSDai

## Staking and Unstaking

Users can stake their **USDai** through GAIB's interface. A “Stake” transaction exchanges USDai for **sUSDai,** a liquid receipt token representing the staked position. Conversely, an “Unstake” transaction returns staked USDai to the user, instantly updating balances upon confirmation on the blockchain.

A cooldown period of 14 days applies after unstaking, during which users cannot withdraw USDai. Once the cooldown expires, users can freely withdraw their unstaked USDai.

## Reward Mechanism

GAIB leverages a **token vault** approach—similar to Rocketpool’s rETH or Binance’s WBETH—to deliver rewards seamlessly.

1. **Vault Mechanics**
   * **No Rehypothecation**: Deposited USDai remains in the staking contract; it is not lent out or repurposed.
   * **Reward Accrual**: Protocol-level revenue is periodically deposited into the staking contract, increasing the value of sUSDai in relation to USDai.
2. **Value Growth**
   * sPICE’s worth in PICE terms rises over time as protocol rewards flow in.
   * The **sPICE:PICE ratio** is calculated as: _sUSDai:USDai ratio_ = (total _sUSDai_ supply) / (total _USDai_ staked + total protocol revenue deposited in _USDai_ terms)
   * Users often receive fewer sUSDai tokens than the USDai they stake, but the total value matches. As the ratio increases, sUSDai appreciates in USDai terms.&#x20;

When users unstake, they receive an amount of USDai equal to their initial stake plus accrued rewards, as reflected by the increased sUSDai-to-USDai ratio.

## Important Notes

* **Stakers Need Not Take Extra Steps**\
  Simply holding sUSDai accrues benefits automatically.
* **Fewer Tokens, Equivalent Value**\
  Receiving fewer sUSDai tokens than PICE deposited is normal; the underlying value remains the same.
* **Cooldown Period**\
  After unstaking, stakers must wait 14 days before withdrawing USDai.

By aligning sUSDai with real protocol growth through a transparent ratio mechanism, GAIB ensures that staking remains straightforward, secure, and rewarding.
