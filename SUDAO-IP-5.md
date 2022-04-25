## SUDAO-IP-5: Proxy Tokens for Tipping

## Rationale
So far we have been using our actual KPI Option tokens loaded into Tip.cc Bot to distribute tips, and have been doing so on Ethereum. This means we have been paying Ethereum gas fees for loading Tip.cc Bot, and recipients have been spending Ethereum gas fees (as KPI Options) for withdrawal.

More importantly, each time we add a new KPI Options token to the Tip.cc Bot we have to pay a $1000 fee (currently, 6 months ago it was $500).

## Content of the Proposal:

To tackle these points I’m proposing that for tipping, in place of our actual KPI Options token, we use:

- A blank token
- Minting on Polygon
- A limited in supply to ensure 1:1 matching, this epoch, with actual KPI Options minted for use as tips
- This blank token added on Tip.cc Bot only one time

We would then tip as we normally would, and for redemption follow this approach:

- Recipients can claim the actual KPI Options, at any point or at the end of an epoch, by sending their accumulated blank tokens to their team leads
- Given that the KPI Options are almost certainly going to be on Polygon it would be easy and cheap for (batch) sending KPI Options from Treasury
- At the end of an epoch, all team leads send the tokens back to Operations and/or Treasury team, for redistribution next epoch
- A tally would be done to ensure as much of the original token amount distributed that epoch is returned
- We can always mint more blank tokens to match KPI Options needs over time
- In the next epoch, to further reduce the chance of gaming the system, we could hike the equivalence to 10 blank:1 KPI option (TBD next epoch)

## Additional Notes:

1. Polygon has extremely low gas fees, normally around $0.01 or less - reduces loading costs
2. As we are using the token for a single purpose it makes sense to only have to add it the one time on tip bot
3. Recipients no longer need to be taught how to withdraw from Tip.cc Bot, only how to tip
4. By using a blank token we resolve any security & financial concerns of having actual tokens locked in Tip.cc Bot, in case it goes down/withdrawals are not working
5. This adds a bit of operational overhead, but it eases the experience for end-users and could promote more widespread tipping
6. We can institute this as soon as Teams have their budgets allocated to their multi-sigs, without having to wait for suINT (SU Epoch 1 KPI Options) to be minted

## What on-chain actions might this proposal entail:

None at this time
