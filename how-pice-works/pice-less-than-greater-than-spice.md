# USDai <--> sUSDai

## Staking and Unstaking

Users can stake their _**USDai**_ through GAIB's interface. A “Stake” transaction exchanges _USDai_ for _**sUSDai**_**,** a liquid receipt token representing the staked position. Conversely, an “Unstake” transaction returns staked _USDai_ to the user, instantly updating balances upon confirmation on the blockchain.

A cooldown period applies after unstaking, during which users cannot withdraw _USDai_. Once the cooldown expires, users can withdraw their unstaked USDai.

## Reward Mechanism

GAIB leverages a **token vault** approach—similar to Rocketpool’s rETH or Binance’s WBETH—to deliver rewards seamlessly.

1. **Vault Mechanics**
   * **No Rehypothecation**: Deposited _USDai_ remains in the staking contract; it is not lent out or repurposed.
   * **Reward Accrual**: Protocol-level revenue is periodically deposited into the staking contract, increasing the value of _sUSDai_ in relation to _USDai_.
2. **Value Growth**
   * _sUSDai_’s worth in _USDai_ terms rises over time as protocol rewards flow in.
   * The _**sUSDai:USDai**_**&#x20;ratio** is calculated as: _sUSDai:USDai ratio_ = (total _sUSDai_ supply) / (total _USDai_ staked + total protocol revenue deposited in _USDai_ terms)
   * Users often receive fewer _sUSDai_ tokens than the _USDai_ they stake, but the total value matches. As the ratio increases, _sUSDai_ appreciates in _USDai_ terms.&#x20;

When users unstake, they receive an amount of _USDai_ equal to their initial stake plus accrued rewards, as reflected by the increased _sUSDai_-to-_USDai_ ratio.

## Important Notes

* **Stakers Need Not Take Extra Steps**\
  Simply holding _sUSDai_ accrues benefits automatically.
* **Fewer Tokens, Equivalent Value**\
  Receiving fewer _sUSDai_ tokens than _USDai_ deposited is normal; the underlying value remains the same.
* **Cooldown Period**\
  After unstaking, stakers must wait till the cool down period finishes before withdrawing USDai.

By aligning _sUSDai_ with real protocol growth through a transparent ratio mechanism, GAIB ensures that staking remains straightforward, secure, and rewarding.
