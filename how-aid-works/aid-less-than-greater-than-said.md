# AID <--> sAID

## Staking and Unstaking

Users can stake their _**AID**_ through GAIB's interface. A “Stake” transaction exchanges _AID_ for _**sAID**_**,** a liquid receipt token representing the staked position. Conversely, an “Unstake” transaction returns staked _AID_ to the user, instantly updating balances upon confirmation on the blockchain.

A cooldown period applies after unstaking, during which users cannot withdraw _AID_. Once the cooldown expires, users can withdraw their unstaked _AID_.

## Reward Mechanism

GAIB leverages a **token vault** approach—similar to Rocketpool’s rETH or Binance’s WBETH—to deliver rewards seamlessly.

1. **Vault Mechanics**
   * **No Rehypothecation**: Deposited _AID_ remains in the staking contract; it is not lent out or repurposed.
   * **Reward Accrual**: Protocol-level revenue is periodically deposited into the staking contract, increasing the value of _sAID_ in relation to _AID_.
2. **Value Growth**
   * _sAID_’s worth in _AID_ terms rises over time as protocol rewards flow in.
   * The _**sAID:AID**_**&#x20;ratio** is calculated as: _sAID:AID ratio_ = (total _sAID_ supply) / (total _AID_ staked + total protocol revenue deposited in _AID_ terms)
   * Users often receive fewer _sAID_ tokens than the _AID_ they stake, but the total value matches. As the ratio increases, _sAID_ appreciates in _AID_ terms.&#x20;

When users unstake, they receive an amount of _AID_ equal to their initial stake plus accrued rewards, as reflected by the increased _sAID_-to-_AID_ ratio.

## Important Notes

* **Stakers Need Not Take Extra Steps**\
  Simply holding _sAID_ accrues benefits automatically.
* **Fewer Tokens, Equivalent Value**\
  Receiving fewer _sAID_ tokens than _AID_ deposited is normal; the underlying value remains the same.
* **Cooldown Period**\
  After unstaking, stakers must wait till the cool down period finishes before withdrawing _AID_.

By aligning _sAID_ with real protocol growth through a transparent ratio mechanism, GAIB ensures that staking remains straightforward, secure, and rewarding.
