## SUDAO-IP-13: Budget and Compensation Plan Epoch 2(Q2’22)

This proposal is to define the budget and compensation plan for epoch 2 of the SuperUMAn DAO (April 1st, 2022 - June 30th, 2022).

## DAO Balance Sheet

Here’s the DAO balances across it’s [Polygon](https://gnosis-safe.io/app/matic:0x7C7a1407c35B695E4eE530D80d4bd4C1aF8569E5/balances) and [Ethereum safes](https://gnosis-safe.io/app/eth:0x7C7a1407c35B695E4eE530D80d4bd4C1aF8569E5/balances):

$UMA - 52,866
$USDC - 22,386.27
$MATIC - 1.97
$ETH - 6.57
$WETH - 1.61

**N.B:** 34,205 $UMA of the $52,866 is currently in 75,000 suINT-s & 2976.36 suINT-l as collateral with a proposal ongoing to unlock that collateral.

Here’s a [detailed breakdown](https://docs.google.com/spreadsheets/d/1ATblcDEqICQnrHgCSx6YRq1quxvtDjLLSOgQrtbV71Y/edit?usp=sharing) of the DAO’s balance sheet, this includes the $USDC balance across each team’s Msig including their budget for this current epoch.

## Executive Summary

As per the SU DAO Design Principles, a budget and compensation plan should:

1. Have sufficient stables to provide a level of stability for our members at all eligible tiers
2. Distribute KPI Options that’s similar to the framework of prev. epochs
3. Meet our pre-defined requirements for team budgets to enable operational costs to be covered
4. Have an allocation of funds for gas & transaction costs
5. Have sufficient reserves such that we can allocate to our defined emergency fund, while also considering additional tipping collateral, DAO actions, sponsorships, grants, bounties etc.

This Budget and Proposal plan proposes using our $UMA balance sheet ( 52,866 $UMA across our Polygon & Ethereum safes ) to compensate DAO members for #1 as defined in our DAO Design Principles. As well as making sure we have enough gas for transactions, an emergency fund in place, and all team’s multi-sigs topped up to at least $2500. KPI options are not within the scope of this proposal and will be dependent on approval of our long term funding grant to UMA DAO.

## Rationale:

Due to our original funding proposal getting taken down after feedback from UMA DAO/Risk Labs we are now trying to find a way to continue paying our active contributors, make sure we can cover all operational costs, top up team multi-sigs, maintain an emergency fund, have enough gas reserves for transactions, etc. This proposal will show we can continue our normal operations except for the minting of KPI options which would be dependent on our long term funding grant’s approval. The compensation part is based on a [discord poll](https://discord.com/channels/909933079181799524/914808444266115082/966066860074340392) vote to determine the runway length to be either 3, 6, 9, or 12 months long. With a supermajority of 72%, 3 months is the runway time length we are proposing.

## Content of the Proposal:

This budget and compensation plan proposes that the DAO uses 52,866 $UMA to compensate DAO members. We still have a sufficient amount of gas for our ethereum and polygon safes at 6.57 $ETH and $1.99 $MATIC. We have over $20,000 USDC sitting idly to top up all teams back to $2500 for this quarter and support initiatives like the POAP lottery which is $5000 USDC that the governance team manages.KPI options collateral, minting, and distribution for this quarter would be dependent on our long term funding grant’s approval.

DAO members will be compensated in $UMA tokens using a 7-day Twap of $UMA’s price at the time of monthly compensation distribution.

## UMA’s Floor Price

The floor price of 3.7$ per UMA was calculated as the price at which CoC = PfC. One of the [essential steps](https://docs.umaproject.org/oracle/econ-architecture#step-1-measuring-cost-of-corruption-coc) in securing UMA’s Optimistic Oracle is maintaining CoC > PfC where CoC is the cost of corruption and PfC is the profit from corruption. When that ratio becomes unbalanced, UMA uses the funds from the Store to perform “buy and burn” operations on the $UMA tokens to [maintain](https://docs.umaproject.org/oracle/econ-architecture#step-3-maintaining-coc--pfc) CoC > PfC.

**How we derived the price 3.7$**

`CoC = Cost of Corruption = Cost to buy 51% of total $UMA tokens
Total UMA circulating supply - 66,000,000 

UMA’s price at the time of calculation - 6.4$

Coc = 51% of 66,000,000 * 6,4$

= 33,660,000 * 6.4$

= 215M$

PfC = 125M$ at the time of calculation according to data from [UMAverse ](https://projects.umaproject.org/)

To calculate the floor price we need:

51% of 66,000,00 * floor price = 125M$

33,660,000 * Floor price = 125M$

Floor price = 125M$ / 33,660,000 = 3.71$ `

## TWAP Value

Stables compensation will be replaced with compensation in $UMA tokens contingent on SUDAO-IP-12 being ratified. In order to determine the number of $UMA tokens distributed at the time of monthly compensation a 7-day TWAP will be used to determine UMA’s price.

The 7-day TWAP value is calculated using the average of UMA’s closing price in the previous 7 days at the time of submitting the SCD proposal. UMA’s closing price is calculated using the [UMA/USD price identifier](https://github.com/UMAprotocol/UMIPs/blob/master/UMIPs/umip-57.md).

If the Twap Value falls below 3,7 $UMA then the price used to calculate the number of $UMA tokens distributed will be replaced with 3.7$.

## Additional Notes:

- Allocation for stable compensation will be ~$186,000 (97% of 52k $UMA).
- There’ll be no allocation for quarterly KPI Options as that will be determined by our funding proposal to UMA DAO.
- [Full timers](https://discord.com/channels/909933079181799524/959790106573701131/959798220706418708) will also be compensated.
- Top up all teams multi-sigs with the $USDC sitting in the treasury’s polygon safe back to $2500 and an extra $5000 USDC for the POAP lottery to the governance team’s multi-sig.

## The compensation details are below:

- 1506$/month for UMAsters
- 805$/month for Core SuperUMAns
- 421$/month for Basic SuperUMAns
- 4551$/month for Full Timers
- 
Values have been pulled from the final working documents that were presented on Discord prior to this vote.

[SU DAO - Compensation Structure (Epoch 2)](https://docs.google.com/spreadsheets/d/16mFdVp4CCJyKRmOMacoYQvFGph2hfYw55R3_xCCwkVE/edit?usp=sharing)

## Reasoning:

- This is a somewhat doomsday scenario accounting for if 1 $UMA were to be equivalent to $3.7 USDC. If UMA were to stay around $6 or go up we would have a decent amount of UMA left over at the end of this quarter.
- Going into this epoch there was an expectation that we would have a funding proposal approved by UMA DAO to be able to use for our compensation and budgets of Q2 ‘22. Our initial proposal has been taken down and we are now working on a more long term proposal but this also means we won’t be able to pay contributors if we are solely waiting on the next funding proposal to pass in order to do so.
- There should be an expectation that this is the last quarter we will be using this compensation structure as we plan on setting up a new infrastructure and revamping how contributors get compensated.
- There isn’t enough time to come up with a totally new compensation structure and continue paying contributors. Thus we decided to move forward with compensation based off of a runway of our current funds.
- The DAO currently doesn’t have enough funds to meet the predefined requirements in our DAO design principles. We’re unable to distribute KPI Options to members and also offer a sufficient stable amount to DAO members.

## Drawback / Risks:

- If we are unable to get our long term funding grant approved by at least the middle to end of July ‘22, ~3 months, we would potentially be unable to continue to pay contributors or have to significantly reduce the amount we can afford to pay out.

## What on-chain actions might this proposal entail:
None at this time.
