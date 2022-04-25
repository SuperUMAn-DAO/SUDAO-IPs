## SUDAO-IP-2.1 Expedited Governance
**Author:** arcology
**Status: Stage 3 - Formal Proposal**

## Changelog
**IP-2.1**
1. Changed poll to be public to allow to see who voted.
2. Additional text to be added to the [SuperUMAn DAO Design Principles Document](https://docs.google.com/document/d/14uWrupaMGi5JMDphwNI_IeT_TmwcchG2fDCidSqHZL0/edit#) , included below

## Executive Summary
This proposal adds an ‘expedited governance’ track to allow proposals which are important and under time pressure to be ratified more quickly, with some exclusions.

This proposal is not eligible for expedited governance (for obvious reasons).

## Rationale/Motivation
The [current governance process](https://docs.google.com/document/d/14uWrupaMGi5JMDphwNI_IeT_TmwcchG2fDCidSqHZL0/edit#) has a maximum timeframe of 21 days from start to finish for a prospective proposal to go through. This creates unnecessary overhead and time lost if the content of the proposal is important to the functioning of the DAO, and/or if the proposal in question is under time pressure to be executed.

An example is the delay of the enactment of Compound’s code tweaks to patch the [overcompensation token incident](https://rekt.news/overcompensated/) due to the typical governance process timeframe, where an expedited governance track can help reduce the effects of loss.

## Content of the Proposal/Specification:
The expedited governance process overrides the existing governance procedure by removing the need for an optional temperature check and compulsory signal (Stage 1 and 2), by allowing a proposal to directly enter the formal proposal phase (Stage 3) for a shorter timeframe and also proceed to Snapshot phase (Phase 4), under a shorter timeframe given that the proposal passes up to this point.

There are additional requirements to allow proposals to proceed under the expedited governance track:

- The proposal in question must be eligible. As of this writing, eligibility is open for all with the following exclusions:
  - a. Proposals for membership status changes;
  - b. Proposals for compensation level changes.
- Authors must declare in the originating thread that they intend for the proposal to go through the expedited governance track.
- The quorum for the formal proposal (Stage 3) is limited and raised to 50% for all SUs and above (ie superUMAns and UMAsters), with a minimum endorsement from 5 UMAsters;
- The threshold for a Stage 3 passing vote needs to be a supermajority (67% and above);
- The quorum for the snapshot vote (Stage 4) is 75% of voters from Stage 3;
- The threshold for a Stage 4 passing vote is 80%.
- Stage 3 and Stage 4 timelines can be reduced to 48 hours each.
- If a vote fails in expedited governance at any point, the proposal in question cannot be placed again under expedited governance and is required to go through the normal governance process.

## Visual Guide
Please right click and open this image in new tab/window for full size.
https://discourse.superumans.xyz/uploads/default/original/1X/bc34e2839d978205c7ff26085f35387740d7df06.jpeg

## Proposed Amendments to the [SuperUMAn DAO Design Principle Document](https://docs.google.com/document/d/14uWrupaMGi5JMDphwNI_IeT_TmwcchG2fDCidSqHZL0/edit#)
The following will be added/amended under ‘Details of Governance Mechanism’, including the ‘Visual Guide’ above for posterity and clarify the differences and governance process for both tracks.

**Start**

The governance mechanism consists of 2 tracks:

1. **Normal Track / Regular Governance** for all proposals submitted, and;
2. **Fast Track / Expedited Governance** for eligible proposals that are of significant importance and under circumstances considered urgent to be ratified quickly.

**Normal Track / Regular Governance**
`Original text in the Principle document goes here.`

**Fast Track / Expedited Governance**
Under this track, proposals can be brought forward (expedited) for quicker deliberation, voting, and ratification, with an expected minimum time of 4 days from start to finish. Like Regular Governance, the platforms for governance (Discord, Discourse and Snapshot) will not change, but some stages can be omitted but with a higher criteria for quorum and passing vote.

**Exclusions**
Proposals which modify the following:
- a. Proposals for membership status changes;
- b. Proposals for compensation level changes.
These are not eligible for expedited governance.

**Stage 1 - Declaration**
The Optional Temp Check is omitted in this track. However, the author must declare in the beginning of the proposal that they intend to submit their proposal under the Expedited Governance track.

**Stage 2 - Signal**
This stage is omitted under Expedited Governance.

**Stage 3 - Formal Proposal**
A formal proposal shall be submitted on Discourse with a poll consisting of the following:

- Yes (or various proposed Options)
- More discussions needed
- No

There must be a minimum endorsement from 5 UMAsters, and;
The quorum of the proposal is raised to 50%, and is limited to active UMAsters and SuperUMAns only, and;
The passing vote needs to be a supermajority (67% or above).
The poll run length is reduced to 48 hours.
In the event that at the end of the poll run time the quorum, endorsement or passing vote requirements are not met, the proposal is considered Failed (see ‘Failed Proposals under Expedited Governance’).

**Stage 4 - Snapshot Proposal**
Provided that the criteria for passing Stage 3 of the proposal is met, then the proposal shall be posted on Snapshot following the same formatting guidelines as Regular Governance with the additional criteria:

The quorum for the Snapshot vote is 75% of the voters who have voted previously from Stage 3, and;
The threshold for a passing vote is 80%.
The Snapshot run length is reduced to 48 hours.
In the event that at the end of the poll run time the quorum or passing vote requirements are not met, the proposal is considered Failed (see ‘Failed Proposals under Expedited Governance’).

**Failed Proposals under Expedited Governance**
If the proposal has Failed at any stage, the proposal is not eligible to be resubmitted under the Expedited Governance track.

**End**
