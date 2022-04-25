## SUDAO-IP-7: Mechanics of suINT KPI Options

## Rationale

This is a one time proposal intended to solve the blockers on distribution of our suINT 1st epoch KPI Options. Any future distribution of KPI Options will need a new proposal.

SuINT KPI Options has passed full quorum on [snapshot](https://snapshot.org/#/superumans.eth/proposal/0xc50c401d462f4503abdfda1e30d800273ef53eee7aa60dea0cb7fc280577bfca), this proposal only applies to the mechanics of minting and distribution of said tokens.

The need to define the mechanics arises from the inability of the main SU safe to complete the necessary steps. This comes as a result of removing all signatories from the main safe, now controlled solely through a snapshot vote.

A snapshot vote is unable to trigger the SU safe into the actions of approving contract collateral or minting the Long / Short tokens. We require an alternate method.

It is hereby put forth that the Ambassador team’s Gnosis MultiSig safe handles the steps described in ‘Proposed Mechanics’ below to enable the final distribution of our suINT KPI options.

## Content of the proposal

**Proposed Mechanics**

- Temporarily add gruad and poopster as backup signatories to the ambassador’s gnosis safe and change the gnosis safe to a 3 out of 5 signature requirement. Once the steps described in this proposal are carried out, the Ambassador team will remove Poopster and Gruad as safe signatories.
- The main SU Treasury safe will be authorized by a successful vote of this proposal to send the UMA tokens required to mint suINT KPI options, per our [ratified compensation plan](https://discourse.superumans.xyz/t/sudao-ip-3-superuman-dao-budget-and-compensation-plan-passed/567), to the Ambassador Gnosis MultiSig.
- The Ambassador MultiSig will then approve the contract collateral ($UMA) and mint the ratified amount of Long / Short tokens.
- Immediately following the minting of said tokens, the Ambassador Gnosis MultiSig will send all the suINT Long / Short tokens to the main SuperUMAn DAO safe.
- A following snapshot vote will be required to send out the ratified distribution of the Long tokens. The main SU safe will hold the Short Pair until expiry and redemption of the contract.

**Security Considerations**

It is recognized by the DAO as well as the Ambassador signatories that the above proposal carries certain risks. It would require only a short period of time for the Ambassador team to perform the process described above.

A two of three MultiSig makes for a quick and smooth mechanical process. It also requires an amount of trust by the wider DAO that the Ambassador signatories will indeed carry out the steps as described above. We are switching to a 3 of 5 multisig temporarily to ensure we have enough signers as the 2 backups are active members and leaders of the DAO as well. The signatories on the Ambassador team consist of @inalittlewhile, @arcology, and @coach. If this proposal is approved the signatory roster will include gruad and poopster as backups.

## What on-chain actions might this proposal entail:

Ratification of this proposal via quorum on a snapshot vote would trigger the main SU safe to send 45,000 UMA tokens to the Ambassador Gnosis MultiSig.
