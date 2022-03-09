## “Interest Rate Swaps” in DeFi?

In the following article we will delve into Interest Rate Swaps (IRS, not the best abbreviation lol). Generally speaking IRS is huge in TradFi, the size of interest rate derivatives market is over $1 quadrillion. Interest Rate Swaps are in finance in order to create a new money market, where users can swaps their derivatives to match their risk preference. Given the fact that each user has a unique risk preference, the IRS market allows for that preference to be swapped for another derivative which has a better match for the users risk preference. It could be that the user is risk averse, thus wants Fixed rates, or instead the user is speculative and risk taking which may push them towards Variable rates.

Let’s look at the DeFi ecosystem and on why we need Interest Rate Swaps. Over the years crypto space has grown exponentially, which was as a result of revolutionary protocols made by great minds. The protocols such as Maker, Compound, AAVE, Uniswap, Curve ( and many more) allowed DeFi to provide the TradFi services in a decentralised and efficient manner. They all provided more instruments for users to utilise in the ecosystem for sound and open finance. However, as the space is growing we see that not everyone is a degen anymore, the rise of protocols such as Anchor who have 20% stable interest represents the rise of risk-averse users. There is also lack of new innovative instruments in DeFi, since the listed above protocols are already in full use, thus there is a need for a new innovative instrument.

The introduction of IRS instrument into DeFi would boost the ecosystem, because the many interest bearing tokens would have more use cases. IRS would essentially allow greater flexibility for all users of interest bearing tokens, because then users can speculate on the interest they receive. Thus I expect an increase in usage of interest bearing protocols, once an IRS protocol is established.

Currently in DeFi there are very few IRS protocols, the ones I found are: Voltz (voltz.xyz), Tempus, Swivel, Element Fi, Strips and Pendle. Almost all of them are very new and have potential, the infancy of IRS protocols in DeFi means there is no one ‘correct’ way to build an IRS protocol. Therefore, we will delve into each one and depict their differences. 

**Voltz:**

*How it works?*

Voltz is an innovative IRS protocol, their innovation comes in different levels. First and foremost, rather than a simple AMM, Voltz decided to go with splitting it into 2. There is the vAMM and the Margin Engine, the vAMM is used for price discovery and Margin Engine for the calculations. 

*What does it allow?*

The idea is that the protocol will let users either fix their returns or give the opportunity to trade with 10x leverage. Therefore, both risk-averse and true ‘degens’ can trade on the protocol. 

**Tempus**: 

*How it works?*

Tempus is a Fixed income protocol, they follow the idea of splitting tokens. Given that interest bearing tokens garner value through the interest that’s being accrued on the underlying asset as well as that the underlying assets value is also changing. Thus by splitting them, the single interest asset becomes the Capital and Yield Tokens. The tokens then create a Tempus Pool which is connected to the Tempus AMM. The AMM and Pool allows the trade of both tokens. The AMM is made up of Uniswap (x*y=k), Curves stable swap type AMM and the Balancer v2 Stable Pools. 

*What does it allow?*

By trading your tokens through the TempusAMM you can either fix your returns by acquiring Capital tokens with your Yield tokens. The AMM has a flat fee, therefore all LPs will be able to boost their rewards through fees. One of the useful things I found on Tempus was that I can deposit the underlying token (of the interest bearing protocol) to gain the Fixed or Variable APR. For example, rather than providing sETH from Lido, I can directly provide ETH to Tempus and it gives me the same fixed APR.

**Swivel**:

*How it works?*

In essence, Swivel also splits the tokens into Zero Coupon tokens (zcToken) and nToken. As previously zcTokens represent the underlying and nToken represents the accruing interest. The relation between zcTokens and nTokens is inverse. That is because zcTokens are only redeemable for their value at maturity, meaning they will be traded at a discount before the maturity. On the other side, nTokens depreciating in value, that is because their interest is only accrued until maturity and can be redeemed any time. Thus at maturity there will be no more interest being accrued by the token and if all rewards are redeemed, then nToken has very little to no value.  In order to swap between zcToken and nToken, Swivel have made their own off-chain Orderbook, which is the market maker for their tokens. One of the hindrances for Orderbook systems is the need for high transaction volume, to reduce the spread.

*What does it allow?*

Swivel allows the trade of interest bearing tokens through their protocol, which splits the token and allows trade on it through the Orderbook. This means clients can either increase their exposure to variable rates or fix their returns by selling the nTokens in return for zcTokens, which have the underlying assets value at maturity. 

**Element Fi**:

*How it works?*

Element also splits their tokens, it also allows boosting through liquidity provision. 

How is their AMM

*What does it allow?*

**Strips**: 

*How it works?*

Unlike other mentioned protocols, Strips operates on an L2 (Arbitrum). Rather than split the yield bearing token, on Strips you choose a long or short position on the interest you are receiving. For example, if you are currently receiving 5%, but speculate that it will go higher, then you would choose long and vice versa. The interesting differentiation would be the introduction of leverage. Strips allow the user to have up to 10x leverage, the position is against the Strips AMM. Thus, the AMM would require the insurance fund, in case if users are winning too much. However, an issue is that the fund may run dry in the worst case scenario, leading to failure of the AMM. 

*What does it allow?*

The protocol lets traders use leverage in their speculation against the interest bearing token, therefore have access to significantly more rewards (and losses). All in all, Strips looks more like an instrument for traders rather than average joe who wants to fix their interest rate. 

**Pendle**: 

*How it works?*

Pendle is similar to other protocols we mentioned in splitting the interest token into, Ownership and Yield Tokens. The protocol creates a new pool for each different underlying token and maturity date. 

also own AMM (simply a function of [ x*y = x^dp * y^p ]

*What does it allow?*

Conclusion

Overall, the DeFi space is expanding and as we introduce more of TradFi instruments in an efficient manner, the more of TradFi can we eat up or synchronise with. The interdependent nature of DeFi means introduction of IRS protocols will give more use cases to many other protocols. As of now there is no established way to do interest swaps, there is also lack of choice on which interest assets can be used in the mentioned protocols. However, the above mentioned protocols are all tackling the matter in their own way, especially Voltz, which means we can expect some interesting growth in the entire space.
