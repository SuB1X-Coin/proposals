## Requested funds:

**100,000** RUPX coins, **13%** of the monthly governance budget.
It will be paid to the `7KT6fvNDEZTF9hTPGVPjAnHdgR8Fj5FdeN` address when we reach block 129,600 (around May 13, 2018) if MasterNode owners support it with `Yes` votes.

## What are the funds for:

The idea is to reward community governance participation, which will increase adoption and reduce the risk of governane being misused by investors that control lots of MasterNodes, whales or shared masternode operators.

The funds will be split between MNs addresses that have been used to vote during the budget cycle. Payment will be sent to the public address where normal MasterNode rewards go.

Say there are **1000** MasterNodes in the network. To keep it simple, **320** of them vote on all proposals. **20** of these have a "red" port on `mn.rupx.io`, meaning they don't help the network. These will not receive vote rewards. So, we are left with **300** MasterNodes, each getting a **332** RUPX "good citizen" reward. For this proposal, we are not going to consider how many votes a node has placed. One vote is enough to get a chunk of this proposal budget.

The distribution of the funds will be done via a script that calls the `mn.rupx.io` API, loops over each masternode that has voted at least once and sends the voting reward.
The `Voting` column on http://mn.rupx.io indicates if your MasterNode has voted or not. Keep those little 🚀 🚀 🚀 coming.

## Proposal creator Discord user:
`mn.zone_dev#7125`

## Proposal discussion forum:
[Rupaya Github Proposals Issue 1](https://github.com/rupaya-project/proposals/issues/1)
