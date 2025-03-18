# Protocol Mechanics

<figure><img src="../.gitbook/assets/Protocol Mechanics Mar 18.svg" alt=""><figcaption><p>GAIB Architecture</p></figcaption></figure>

## Off-chain Components&#x20;

### Cloud / Data Centers 1, 2, 3, ... N

GAIB structures financing deals with reputable cloud companies and data centers around the world with GPU clusters and their contracts as backing.&#x20;

#### Deal type

* Debt model: cloud / data centers pay interests on the borrowed capital.
* Equity model: cloud / data centers pay a revenue share of the GPUs.
* Hybrid model: cloud / data centers pay interests plus providing upside through revenue share of the GPUs.&#x20;

#### Collateral

* All agreements are backed by physical GPUs. Currently GAIB prioritises highly sought-after enterprise grade GPUs like NVIDIA H100s, H200s, GB200s, etc.&#x20;
* GAIB structures deals on a cluster basis and prioritizes GPU clusters that are already reserved by clients from 1 to 3 years. &#x20;
* Bankruptcy-remote structure would be used.  &#x20;
* Maturity: depending on deal structuring, maturity can range from 3 months (e.g. bridge financing) to 3 years. Given the short payback period of enterprise-grade GPUs due to the high demand, GPU backed loans could have much shorter maturity than typical debt.&#x20;

#### Gross Yield

* Debt model: estimated yield 10% - 20%&#x20;
* Equity model: estimated yield 60% - 80%+&#x20;

#### Risk Management&#x20;

* GAIB and other underwriters on the platform conduct stringent due diligence according to the Credit Analysis framework and work with 3rd party auditors when necessary.&#x20;
* All loans are over-collateralized by the GPU assets.&#x20;
* In case of default, GAIB has the authority to liquidate the GPUs to pay back the investors, or continue to host and manage the GPUs using GAIB’s strategic partners’ data center facilities to keep on generating revenue for investors. &#x20;

#### Strategic Collaboration with Decentralized Compute

given the surge of decentralized compute protocols aggregating under utilized compute resources and bridging compute supply and demand via blockchain, GAIB partners up with them to tokenize the on-chain revenue streams of compute providers on different de-compute platforms, starting with Aethir. ([details](https://x.com/gaib_ai/status/1882052295472656411)) &#x20;

### Treasury Bills&#x20;

GAIB holds a reserve of treasury bills to ensure liquidity in the case of redemption.&#x20;

### Third Party&#x20;

GAIB works with third-party auditors, credit underwriters, custody, attestation, and other professional service providers when necessary, to maximize investor protection and risk-reward of each GPU financing deals.&#x20;

## On-chain Components

### Mint & Redeem&#x20;

Through GAIB's mint and redeem smart contracts, whitelisted KYC-ed users can directly mint GAIB's AI Synthetic Dollar _AID_ with stablecoins and redeem their stablecoins with _AID_ on the GAIB protocol.&#x20;

### Staking&#x20;

All users can stake their _AID_, and receive _sAID_, a liquid receipt token representing their staked _AID_ position. _sAID_ accrues yield, allowing them to claim yield when they unstake. Details can be found on the [AID <-> sAID](../how-aid-works/aid-less-than-greater-than-said.md) page.&#x20;

### Liquidity Pools

GAIB will integrate with major AMMs and maintain liquidity pools for _AID_. Through the GAIB interface, all users can exchange stablecoins for _AID_ and vice versa by accessing external liquidity pools.

### DeFi Use Cases&#x20;

#### **Lending and Borrowing**

GAIB will integrate with major lending protocols, allowing users to deposit _**AID**_ into lending pools for additional yields. Users may also borrow _AID_ by locking major cryptocurrencies as collateral, improving liquidity and capital efficiency within the ecosystem.

#### **Yield Trading**

As a yield-bearing asset, _**sAID**_ will be adopted by specialized yield-trading protocols. Holders can create or trade Principal Tokens (PT) and Yield Tokens (YT) based on _sAID_, or supply liquidity for PT and YT pairs. By offering various risk-reward profiles—ranging from stable returns to higher-risk speculation—this approach caters to a broad range of investor strategies.

#### **Derivatives**

With robust liquidity and steady yield generation, _**AID**_ and _**sAID**_ can serve as the foundation for diverse derivative products. This fosters greater market innovation while meeting the growing demand for advanced hedging, speculation, and risk management.&#x20;

#### **Customized Yield Strategies**

GAIB will integrate with yield optimizers, vaults, and other innovative DeFi protocols, enabling the creation of novel yield strategies built on tokenized GPU assets. Users can tailor these strategies to their individual risk-reward preferences, further enhancing personalization and accessibility in the GAIB ecosystem.
