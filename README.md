##  Project Overview

A cross-chain layer 2 stable assets issuance platform for greater DeFi
The OINDAO is a cross-chain decentralized stable coin issuance platform based on Ethereum. Different from an existing strategy where whitelisted assets are all staked or leveraged to issue one universal stablecoin, OINDAO is aiming to build a multi-function stablecoin issuance platform enables projects to issue their own stablecoin autonomously by collateralizing their native tokens. This will not only allow the projects a direct onramp to a defi platform and serve the needs of the investors and projects with staking, leverage, and stablecoin, but also bring them onto the OINDAO platform. The value of OIN token is supported by the voting right to govern the platform and transaction fee sharing. 



## **Staking OIN**

#### **Overview**

The currently available beta version allows users to mint USDO1 by locking in OIN in a smart contract. The USDO1/OIN trading pair will also be available on UNISWAP, allowing an easy method to leverage OIN to increase your stake in OIN.

#### **Why staking OIN** 

1、Mining Rewards are available to those who stake. The OIN rewards will be distributed according to your proportion of the total stake. 

2、Leveraging the stake to mint USDO1, you can increase your stake in OIN, further increasing the available rewards. 

3、Pooling is available through other platforms as well, such as Balancer, yEarn, and Curve to get additional rewards while still earning mining rewards with your collateralized stake.

Risk of Staking

Although there are no risks to your stake (you can redeem your OIN collateral by burning corresponding USDO1 amount at any time), there are underlying asset price volatility and the possibility of reaching the predetermined liquidation rate that you must consider.

If the price reaches the predetermined liquidation rate, your collateralized OIN will be returned to the original wallet.

 

#### **The Mint procedure of USDO1**

- Open the[ OINDAO](https://dao.oin.finance/) website.
- Click and enter the staking module, labelled “Staking”.
- Enter the USDO1 amount you wish to mint, double check the OIN amount required, and click “Mint”.
- The mint process is complete! You can now see the staked amount in your wallet.

 

#### **How the USDO1 Pool Works**

In the USDO1 pool, the target collateralization ratio is fixed at 700% OIN (in USDT) to 1 USDO1, with the reference price of 0.20 USDT/OIN. I.e., when OIN is at 0.2 USDT / OIN, you can mint 1 USDO by staking 35 OIN. The formula can be expressed as: STAKE(Per USDO1) = 7 / PRICE. Two parameters determines the exchange ratio.

The spot price for OIN.

The target collateralization ratio.

The staking ratio of 35 OIN to 1 USDO1 will not change for this pool, regardless of price movements. This reference price was determined to provide the most stable pool when taking into consideration several factors, such as price volatility of OIN and the altcoin market, the value of the OIN token, and the strength of the crypto market, among others.

Additional pools with new reference prices may be created at a later date, depending on the price movements of OIN and the market in general.

### **Failsafe Mechanisms**

#### **Minting Freeze**

When the market price is higher than the freeze price, you or anyone with the OIN tokens can mint USDO1. When the market price is below this price however, currently set at 0.20 USDT, USDO1 will be unavailable to mint. 

This is to ensure the stability of the pool and ability to quickly clear in case of a market crash. The pricing was determined through several factors, such as price volatility of OIN and the altcoin market, the value of the OIN token, and the strength of the crypto market, among others.

#### **Clearance Mechanism**

At a 110% ratio (0.0314 USDT), the OIN will be cleared and returned to the users wallets. This is to ensure that the user’s assets are protected.

 

### **Redemption**

- Open the [OINDAO](https://dao.oin.finance/) website.
- Click and enter redemption module, labelled “Redeem”.
- Enter the amount you want to redeem.
- Click the Redeem button. You can redeem any amount of your stake at any time.
- Click Confirm on the pop-up window.
- Check your wallet to ensure that you have received your assets.

Before the price reaches the predetermined liquidation rate, you can redeem your collateral at the original rate, which is 35:1 for the USDO1 pool, with the original price of 0.20 USDT.

If the market price of OIN reaches the liquidation rate of 110% (below 0.0314 USDT), the clearing mechanism will be triggered. USDO1 will no longer be classified as a stablecoin, and the system will return the collateral based on the stake.

Redemption Fee Token holders must pay a gas fee with ETH when they mint the stablecoins. When they return the minted stable coins and redeem them for their collateral, 0.3% of the OIN will be deducted and burned for this beta release.

### **Claiming Rewards**

Currently, the OINDAO will generate 5 OIN for rewards per block, totaling roughly 28,000 OIN per day. The amount of rewards that is generated is subject to change, at first through internal decisions (such as the initial amount set), or through voting and other methods later on. The total mining rewards are vested for 5 years.

You can claim your staking rewards at anytime. Due to the current gas fee of Etheream network, it’s highly recommended to claim your rewards in a lump sum on an as-needed basis.

#### **Steps to Claim Your Rewards**

- Open the OINDAO website and click the mining rewards module, labelled “Mining”.
- The amount of rewards available will be shown.
- Click “Claim Rewards” to claim your rewards!
- Check your wallet to ensure that you have received your rewards.

 

### **How to purchase OIN**

Purchasing on a DEX. OIN is now listed on Uniswap. The contract address of the ETH / OIN trading pair is 0x9aeB50f542050172359A0e1a25a9933Bc8c01259. Please confirm the address before making the purchase.

Purchasing through a CEX. OIN is now listed on centralized exchanges such as BitMax and Gate.io.

Purchasing with USDO1. We will announce the contract address of USDO1 / OIN trading pair on Uniswap in an official announcement, please stay tuned.

 

### **Key Facts**

##### **Address** 

OIN Address: 0x9aeB50f542050172359A0e1a25a9933Bc8c01259

USDO1 Address: 0x88eec3873ac22da27a836f7f63883da4771c96f1

Dparam Address: 0xc9fe746507ce0c0408878f12a955b43760b41216

Esm Address: 0xed39b9a5773a5370471cb89525d914be9eafda2e 

Oracle Address: 0xdc7d33398342d58b935446f9f6e052b48793a4ac 

OinStake Address: 0xD539cb51D7662F93b2B2a2D1631b9C9e989b90ec

 