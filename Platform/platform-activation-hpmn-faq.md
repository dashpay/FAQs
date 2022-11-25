# Decision around how to activate Platform and High Performance Masternodes FAQ

This is an Open FAQ managed by the DCG team. While we have done our best to provide answers as accurate as possible we are not infallible. Contributions to this FAQ can be done either by raising issues or by opening pull requests on Github. If you would like to have DCG answer a question that is not yet in this FAQ please add it as an issue on Github starting with the title "[New Question]:".

# Answered Questions

## General

1. **Why has DCG launched this poll?**

As development for the release of Dash Platform nears completion, certain drawbacks of the original plan that every Masternode would host Dash Platform have come to light. Voices of concern started forming this year that can be grouped into five main categories:

* The approach of forcing Masternode owners to run Platform.
* The performance of the system.
* The safety of the system (it not going down).
* The cost of the system to the network (ROI).
* The fee cost to users.

We took these concerns seriously and thought about the best way to remedy them with solutions that would be relatively easy to implement. We came up with a solution called High Performance Masternodes that will be explained in this FAQ. While the advantages are many, the main drawback of this solution is that it requires the creation of a new type of Masternode with a higher collateral. We will be polling the Masternode network as we want to ensure that this potential move, which differs from the original plan, is aligned with what the community as a whole wishes. Hence this vote is necessary for us as a project in order to coalesce around a plan for Platform activation.

2. **What are the solutions that DCG is proposing to be voted on?**

DCG is proposing 2 categories of solutions to the network:

* The first is that every Masternode must run Platform.
* The second is one of multiple solutions in a category called “High Performance Masternodes”.

The High Performance solutions that will be proposed by DCG would require a new type of Masternode that uses between a 4K to 10K collateral, instead of the standard 1K collateral. The system is designed in such a way that standard Masternode operators should over time see an increase in ROI.

3. **Does the solution that wins the vote stay in place forever?**

No, as time goes by the needs of the network are going to change. There are two main approaches to scaling: vertical and horizontal. Vertical scaling is when you make the individual nodes more powerful. Horizontal scaling in Dash would mean adding sharding to the network. For example if at some point Platform begins to gain very high usage and it can no longer scale vertically we will need to introduce horizontal scaling. Horizontal scaling can only work to a certain degree with the amount of nodes in the 4K or 10K solutions, hence we would need to reduce the collateral at that time. This can not be done now since sharding has not yet been built for Platform, nor does the network yet have the usage required to rationalize the much more costly infrastructure.

4. **How will the vote take place?**

We will be making the following proposals to the network in the December voting cycle:

* Every node must run Platform.
* The 4K High Performance Masternode Solution
* The 10K High Performance Masternode Solution

We expect community proposals to also be made.

 \
If there is no resounding winner (a resounding winner would have over two times the absolute votes of the runner-up), the top two proposals will then go to a runoff in the January cycle. However, if the 4K and 10K HPMN solutions are the two top-voted solutions, we will instead perform a secondary vote where we add proposals for 6K and 8K. The winner would then be the highest voted in the second round between 4K, 6K, 8K and 10K.

The winner of each multiple choice round is determined by the number of YES votes minus the number of NO.

For the second round if there are only two choices there might be only one proposal depending on the winners of the first round.

5. **Is there consensus inside DCG on which solution to go for?**

On October 20, a poll inside DCG was made. The results were that the developers and non-devs overwhelmingly believed that the usage of HPMNs would be a far superior plan compared to running Platform on every node. The result of the internal poll is shown in the table below.

| Solution | Number of votes
| - | - |
| Every masternode must run Platform | 2 votes (1 dev, 1 non-dev)
| 4k or 10k HPMN (doesn’t matter) | 4 votes (4 dev)
| 4K HPMN solution | 4 votes (3 dev, 1 non-dev)
| 10K HPMN solution | 0 votes
| All masternodes or HPMN 4k | 1 vote (1 non-dev)
| All options are good for me | 1 vote (1 dev)

## Economic

6. **What is the estimated return on investment (ROI) in each solution?**

Using the following parameters and assumptions, we’re able to provide estimates of what the ROI would likely be for each existing potential solution:

* Cost to host a MN: 25$/Month
* Cost to host a HPMN: 100$/Month
* Rewards have stabilized between MNs and HPMNs (see question 31 for an explanation of the yield equilibrium between MNs and HPMNs)
* No fees generated by Platform (at start)
* 3.8M Dash locked in either Masternodes or HP Masternodes
* 45$ Dash price

| DCG-proposed Solutions | ROI
|-|-|
| Current ROI (for comparison) | 6.70%
| Every masternode must run Platform | 4.70%
| 4K HPMN solution | 6.69%
| 10K HPMN solution | 6.88%

| Community-Proposed Solutions | ROI
|-|-|
| 1K HPMNs with 20% given to Platform rewards. All nodes get Core rewards. Rewards based on the estimation that 50% of all nodes will run Platform. | 5.09% MN - 5.77% HPMNs
| 1K Dash MN, 1K Dash HPMN (HPMN does not get Core rewards) 50% given to platform | 5.69%
| 1K Dash MN, 1K Dash HPMN (HPMN does not get Core rewards) 20% given to platform (Insecure due to centralization concerns) | 6.38%
| 250 Dash MN, 1K Dash HPMN | 4.68%
| 500 Dash MN, 1K Dash HPMN | 5.36%

7. **What are the estimated Platform fees in various solutions?**

The estimated fees for various operations using each solution are shown in the table below.

These fees are accurate as of November 15th 2022, but are subject to change as we Tweak various processing costs.

| Solution | Send Dashpay Contact Request | Create Dashpay Profile |  Register Identity on DPNS |
|-|-|-|-|
| Every masternode must run Platform | $0.231 | $0.102 | $0.142
| 1K Optional with 1900 Nodes (just for comparison) | $0.110 | $0.048 | $0.067
| 4K HPMN solution | $0.026 | $0.011 | $0.016
| 10K HPMN solution | $0.011 | $0.005 | $0.006

The ratio of fees between each solution would be the same for any operation.

8. **Is DCG a proponent of the HPMN solutions solely because they lower fees on Platform?**

Lower user fees is an attractive advantage of the High Performance Masternode solutions, however DCG would still be in favor of these solutions even if fees were not a factor. The reasons for this become apparent later in this FAQ.

9. **Could we subsidize fees to lower them?**

For Platform to be sound in the long term, we should treat it as a business. Treating it as a business means it should be able to support itself through revenue instead of being subsidized through the block reward. In the first major version release following the initial Mainnet release, we will allow Masternodes running Platform to be able to collectively set their fee multiplier level. At this point the network will be able to choose to subsidize fees or raise them to gather more revenue variably.

The main advantage of the 10K solution is that a higher profit can be achieved while maintaining low user fees.

## Technical

10. **What are the advantages of requiring every Masternode to run Platform?**

The main advantage of requiring every Masternode to run Platform is that it is the most decentralized option in light of the higher node count. However, higher node count is just one of many factors that go into achieving safety of the overall system, and DCG largely believes that while this is the most decentralized solution it is also one that carries many safety risks. If Masternode operators don’t update their hardware to the much more onerous requirements, the whole system will be sluggish and less responsive. We believe that if this solution is chosen the Platform chain can be more easily halted by an attacker, as stopping the network only requires DDOSing 34 nodes of a 100 quorum set. There are also more disadvantages such as reduced ROI and increased user fees.

11. **What are the advantages of not requiring every Masternode to run Platform?**

The advantages of having only a subset of Masternodes support Platform are the following:

* The stability of Core would be further ensured - if all Platform nodes went offline, Core would still run; Chain Locks would still form, InstantSend would still lock transactions.
* It’s an opt-in solution - Masternode owners don’t need to support Platform if they don’t want to.
* User fees would be cut by up to around 20x as overall network costs go down, depending on the solution chosen.
* Network ROI would stay stable (4K) or even increase (10K) as the total hardware cost of the network goes down.

12. **Why are collaterals higher than 1K necessary?**

Increasing the collateral for Platform nodes is necessary so that an equilibrium between Platform and Core node yields can be achieved while also creating market incentives for a lower number of Platform nodes without setting a hard cap. It also makes it more difficult for individual entities to gain control of enough nodes to cause harm to the network or significantly centralize block validation.

As Masternodes seeking to run Platform must also provide Core services it makes the most sense to keep rewarding them for doing so. See next questions for more information on why 1k collaterals are not DCG-proposed solutions.

13. **Would it be possible to reward Platform nodes for Core services and keep collateral at 1K Dash while maintaining ROI parity between Core Masternodes and Platform+Core Masternodes?**

No, it’s not possible to do this while also maintaining parity. Let’s imagine 50% of rewards are sent to Platform in this scenario. In this case, a node running Platform+Core would receive on average twice that of what a node just running Core would.

14. **Would it be possible to reward Platform nodes for Core services and keep collateral at 1K Dash without maintaining ROI parity between Core Masternodes and Platform+Core Masternodes?**

There have been solutions proposed that give only 20% of rewards to Platform, however this solution is plagued by the same issue where a Masternode running Core would just receive 20% less than a Masternode running Platform + Core. In such a scenario we would be left with an insecure system in the case if few masternodes chose to run Platform. The market equilibrium in this solution happens when close to all nodes run Platform, as they would always receive more revenue by doing so. If we assume this to be the case this solution would require really high user fees to offset high network hardware costs, coupled with a reduction of ROI for Masternode Owners.

15. **Would it be possible to not reward Platform nodes for Core services and keep collateral at 1K Dash for running Platform?**

Yes, this is possible. However, there are a few major downsides. First, to reach the same level of security on Platform as the 4K HPMN solution, there would need to be approximately 2100 Platform nodes with 1K collateral. Second, there would be significantly fewer nodes participating in Core-servicing quorums. InstantSend performance is optimal when the node count is over 1920; in this scenario, we would only have around 1700.

16. **Would it be possible to reward Platform nodes for Core services but not directly through Core Masternode payments and keep collateral at 1K Dash for running Platform?**

Yes, this is possible and is most likely the best solution that can keep a 1K collateral. DCG however does not recommend it as there are still major downsides and it would introduce a delay for release of Platform.

The first is that work being done on the Core payment chain would not be rewarded on that Chain. DCG would need to develop a more complicated mechanism in order to prove on the Platform chain that Masternodes are properly servicing the Core chain. Then we would need to implement a different proposer selection mechanism that ignores specific nodes not servicing the Core chain. A quick estimate would be that this extra effort would take 1-2 months.

The second downside is that this system only becomes secure with about 2100 Platform nodes. This would significantly lower the ROI for the network (including for normal MNs). At the same time user fees would be significantly higher than the HPMN solutions.

17. **Why not just put a ‘hard’ maximum on the number of nodes and leave the collateral at 1k?**

Setting a hard cap on the number of Masternodes running Platform would disallow some MNOs to run a Platform node even if they wanted to. Furthermore such a solution would likely threaten the stability of Platform by introducing a point of unsafe centralization.

Currently, the biggest whale is estimated to own about 270 masternodes. Say we set the hard cap to 1000 total Platform nodes. There would be a 6.35% chance that this owner alone could shut down a validator set each time a new set is chosen by taking their participating nodes offline, therefore halting the chain. There would be a 79.29% chance of them having the opportunity to do so each day with 24 quorums a day.

We would need to set the hard cap to at least 2100 in order to achieve a similar level of security in this regard as the 4k HPMN solution.

18. **How does higher collateral enforce higher performance nodes?**

The higher collateral requirement does not enforce higher performance. Rather, Masternodes have an economic incentive to follow the specs recommended by DCG: if a node wasn’t performing sufficiently, it would start lagging behind the rest of the network, fail to produce blocks, and miss out on rewards. Thus a HPMN will be required to be stronger than the current average standard masternode in order to receive rewards. A second point is that higher collateral shows a higher stake in the project which should push HPMN owners to have a higher incentive to have more performant hardware servicing Dash Platform.

19. **Can we increase the number of Masternodes inside a quorum?**

Yes, but the hardware requirements would increase and the block consensus and validation times would be slower. Currently we have a quorum member count at 100. As quorum member size increases so does the performance requirements as well as the time required to reach consensus. Cosmos hub has recently increased their validator count to 175 from 125, however their minimum hardware requirements for being a validator is 32GB of RAM. Since we have not yet launched the final system it’s hard to know the definitive and exact impact of using a larger quorum size. However, it would be safe to say that the more we want the validator count increased the stronger we need our validator Masternodes to be.

20. **Are there many or just one active Platform quorum?**

There are currently 24 active Platform quorums. A new Platform validator set is chosen from these 24 every 15 Platform blocks. There is a high probability that these parameters will change during our testing phase before Mainnet release.

21. **Can we reduce the number of active quorums per day?**

Yes, but the more we reduce the number of active quorums, the lower the chance of individual validators getting paid every epoch. Keeping the active quorum count relatively high and the total Platform Masternode count relatively low increases the probability that all nodes will be in at least one quorum per epoch. The worst approach that we could take is to have very few quorums servicing Platform that are chosen from a very large pool of Masternodes.

In a future version of Dash Core we will stabilize Platform quorum Masternode selection to allow for smoother payouts, but this is not a feature we will have at release. Currently the quorum member selection is completely random.

22. **What about sharding? Could this be a good solution?**

Sharding would take at least four, and likely six to twelve months to implement without an increase to our development capacity. Our view on the matter is that we should get everything working in our system first, release Platform to mainnet, and then at the right time when usage is sufficiently high implement sharding.

Below is a list of the technical challenges associated with implementing sharding in Platform:

* We would need a robust PoSe solution to know which MNs aren't properly participating or not participating at all.
* We would need to have a way to prove this information securely to our core software which currently has the responsibility of creating quorums.
* We would need to alter the selection mechanism of quorums.
* IBC needs to work (it’s currently planned for post-release).

23. **Would it be possible to run an optional Platform node on a different server using the same Masternode key?**

Platform uses Core services and needs them locally with low latency. Without serious effort this is not possible.

24. **Can Tenderdash support delegated proof of stake?**

No, one of the tradeoffs for supporting efficient proofs using threshold cryptography is that all validators must be of the same weight in the system. As such, this breaks the delegated proof of stake model. Since all Masternodes running Platform would hold the same collateral this is not a problem.

# HPMN Questions

## General

25. **What is a High-Performance Masternode (HPMN)?**

A High Performance Masternode is a proposed new type of Masternode which would be used to serve the network by participating in consensus on both the Dash Platform chain and the Dash Payment (Core) chain. In the solutions that use HPMNs the standard Masternode would continue serving only the Dash Payment chain. HPMNs would have greater requirements than a standard Masternode regarding collateral amount and would require higher performance specs as they would be running two chains instead of just one.

26. **What are the main advantages of choosing one of the High-Performance Masternode solutions?**

The main advantages are:

1. Increased safety for the Core payment chain due to the supermajority of nodes not running the Platform chain. If every node running the Platform chain was to go offline, the Core payment chain would only be minimally affected.
2. Hosting Platform is optional, so you can still run a Core node and not have to participate in Platform if you don’t want to.
3. A market equilibrium allowing ROI to vary based on difficulty/desire to run Platform or not.
4. Decreased fees on Platform due to the decrease in total nodes hosting the network. They are estimated to be cut by up to around 20 times depending on the chosen solution.
5. Compared to a 1k optional solution there is increased safety due to the decrease of variability in quorum selection allowing big whales a lower to null chance to either maliciously or inadvertently stop the platform chain.
6. Increased yield for the entire network compared to non-HPMN solutions.
7. Estimated stronger nodes, leading to higher transactions per second.
8. Estimated stronger nodes, leading to higher resilience against malicious attacks.

27. **What are the drawbacks of the HPMN solutions?**

The biggest drawback of the HPMN solutions are the reduction in the total number of nodes hosting Platform, which is both a good and bad thing. It is a good thing because of lower user fees and various other reasons already mentioned. It is a bad thing because the max network query-able load is reduced as there are less nodes to query data from. This however is offset by nodes having a greater capacity to respond to queries. We do not expect this to be an issue in the first few years of Platform activation as we do not expect to come close to the network limit.

Another downside is that compared to forcing every node to run Platform we do have more centralization in the HPMN solutions. However we believe that the slight increase in centralization versus all the benefits of the HPMN solutions are worth the tradeoff especially since the overall HPMN solutions have increased safety.

Another aspect which may be seen as a drawback is the higher barrier to entry for hosting an entire Platform node as it would increase collateral.

28. **Would the decrease of Masternodes servicing the Core payment chain stemming from HPMNs be worrying?**

No, even though we would see a decrease in total Masternode count as collateral moved into HPMNs we would still have more than enough nodes to efficiently serve the payment chain.

29. **Would implementing HPMNs delay Platform?**

We anticipate that the implementation of HPMNs would add only a few hours of development compared to the original plan of having every node run Platform.

30. **What would the governance voting power of a HPMN be compared to a regular masternode?**

HPMNs would have an increase in governance voting power proportional to the increase in the amount of collateral. For example, a HPMN requiring a 4000 DASH collateral would have 4 votes while a standard masternode would still have 1.

## Economic

31. **How do HPMNs get their rewards?**

The Masternode part of the block reward would be split into two parts, one allocated for Platform services and one for Core services. Each is then split equally among all HPMNs and standard Masternodes. HPMNs would get rewards both from the Platform chain and from the Core payment chain. All Masternodes, standard and high performance, would be equivalent from Core’s perspective. Hence we can consider that the first 1K of collateral would be logically associated with Core while the remainder is associated with Platform. Therefore a 4K HPMN would get 75% (¾) of its rewards from the Platform chain and 25% (¼) of its rewards from the Core payment chain. A 10K HPMN would get 90% (9/10) of its rewards from the Platform chain and 10% (1/10) from the Core payment chain.

31. **Would the yield of HPMNs be higher than that of normal masternodes?**

We expect it to be just slightly higher. As this is a market solution giving people the choice to run or not run Platform it is not possible to be sure of the outcome. If there are less HPMNs then the system equilibrium would require then HPMN rewards will be higher than that of Masternodes. If there are too many HPMNs then Masternode rewards would be higher.

If at some given time, HPMNs are receiving much higher yields than standard Masternodes, there will be an incentive to combine existing MNs to create HPMNs. This drives the total number of MNs down and the number of HPMNs up. The yield of HPMNs therefore will go down and the yield of masternodes up until the equilibrium is reached.

32. **Would the 4k or 10k HPMN solutions lower standard Masternode rewards?**

Standard Masternode rewards are expected to stay roughly the same: the rewards will be smaller each time, but will occur more often. The average ROI should even increase in the case of 10K HPMNs as the total infrastructure cost to the network would go down. As this is a market solution giving people the choice to run or not run Platform it is not possible to be completely sure of the outcome. The yield equilibrium referred to in question 24 ensures that every bit of money put in masternodes would yield the same percentage of return as HPMNs, and more money entering the system from Platform fees means all nodes will have increased yields.

33. **Will HPMNs generate revenue from Platform fees?**

Yes, fees will generate revenue except in one extreme case. If the price of Dash were to go below half the average price that was paid in Dash per byte for all bytes stored in the Platform state, revenue generation would be lower than storage hosting costs. Adjustments to the fee multiplier (originally set to 2) could cause this to fluctuate to more than or less than the "half" from the previous statement.

Satoshi’s vision for Bitcoin was that the source of system revenue would transition from block rewards to network fees. The same applies to Dash. Dash has the opportunity to become a business where users and enterprises pay for the service and the Dash network actually makes money on every transaction.

34. **In the HPMN solutions would standard Masternodes generate revenue from Platform fees?**

They are expected to generate revenue indirectly from Platform because the equilibrium described in question 24 that exists between HPMN rewards and normal MN rewards would be driven higher as more Platform fees are generated.

## Technical

35. **What are the targeted specs for HPMNs?**

| | Every node must run Platform | High Performance 4k | High Performance 10k
|-|-|-|-|
| RAM | 16GB | 16GB | 16GB-32GB
| Storage | 200+ GB | 200+ GB | 200+ GB
| CPU | 4 Cores (2.8GHZ) | 4 Cores (2.8GHZ) | 4-8 Cores (2.8GHZ)
| Network Throughput | 1GB/s | 1GB/s | 2GB/s

Note: during Platform’s launch, nodes will be able to run with 8GB of RAM due to the low initial usage anticipated. However, we do not recommend this amount except in that period of low usage.

36. **How many nodes are expected to be supporting Platform for each set of values?**

It depends on the total number of nodes in the system when Platform launches as well as the HPMN masternode block reward allocation. The following values are for a 50/50 allocation scheme.

| Solution | Number of nodes
|-|-|
| All masternodes | All masternodes
| 1K solution | All masternodes / whatever the fixed maximum limit is
| 4K HPMN solution | ~460 nodes
| 10K HPMN solution | ~180 nodes

37. **How does each DCG-proposed solution fare in terms of security?**

The main security concern for Platform is a single entity controlling more than a third of the nodes in a Tenderdash validator set (34+ out of 100). It would allow them to halt the chain either by malice or a stroke of bad luck if they were to take their nodes offline while they were comprising over a third of the set.

In the tables below we provide our calculations of the security of each solution in this regard. The calculations were made assuming there would be a total of 450 HPMNs in the 4K system and 200 HPMNs in the 10K one, and that the current top whale would upgrade _all_ their current nodes (in reality they likely won’t).

| Considering the current top whale’s current number of nodes | Percent chance of the top whale gaining the ability to halt the chain per set | Percent chance of the top whale gaining the ability to halt the chain per year | Expected number of times the top whale would gain the ability to halt the chain per year
|-|-|-|-|
| All masternodes | 0 *  | 0 * | 0 *
| 4K HPMN solution | 1.74E-06 | 0.0152 | 1.52E-04
| 10K HPMN solution | 0 ** | 0 ** | 0 **

| Considering the current top whale increases their node count by 20% | Percent chance of the top whale gaining the ability to halt the chain per set | Percent chance of the top whale gaining the ability to halt the chain per year | Expected number of times the top whale would gain the ability to halt the chain per year
|-|-|-|-|
| All masternodes | 2.57E-11 | 2.25E-07 | 2.25E-09
| 4K HPMN solution | 7.04E-04 | 5.98 | 0.0617
| 10K HPMN solution | 0 ** | 0 ** | 0 **

| Considering the current top whale increases their node count by 40% | Percent chance of the top whale gaining the ability to halt the chain per set | Percent chance of the top whale gaining the ability to halt the chain per year | Expected number of times the top whale would gain the ability to halt the chain per year
|-|-|-|-|
| All masternodes | 2.73E-09 | 2.39E-05 | 2.39E-07
| 4K HPMN solution | 0.0346 | 95.2 | 3.03
| 10K HPMN solution | 7.04E-07 | 6.17E-03 | 6.17E-05

\* value is so small it’s in machine error range

** top whale would have less than 34 nodes

38. **Would quorum selection change with the new masternode type?**

In the HPMN solutions, regardless of their increased collateral, a HPMN would be treated the same as a standard Masternode in the quorum selection process. For Platform quorums only HPMNs would be chosen.

39. **How would one set up a HPMN?**

As far as registration goes, setting up a high performance masternode would be very similar to setting up a normal masternode, except for the higher collateral.

# Voting

40. **What is the threshold required for a proposal to be implemented by DCG?**

As this is a poll, we will go with the proposal that has the best chance of being activated by the network.

At the beginning of Dash we used the BIP9 consensus mechanisms, now we use the [https://github.com/dashpay/dips/blob/master/dip-0023.md](https://github.com/dashpay/dips/blob/master/dip-0023.md) mechanism giving more power to masternode owners. This is the consensus mechanism we currently use on the network. The +10% supermajority that many might think is the required threshold is only required for funding decisions.

# Community Propositions

## Questions

41. **I think I have a better idea than the proposed solutions. How can I proceed?**

While DCG has already invested substantial effort into finding and evaluating all possible methods of hosting Platform, we are always open to hearing additional suggestions from our community, and anyone can always submit a proposal to the DAO.

A few solutions from non-DCG staff have already been informally proposed, which you can find in this section along with summaries of our reviews for each. These proposals either do not actually work, might work but would require a significant delay to the start of Platform, are unsafe due to introducing points of centralization, or cause ROI to significantly decrease as network costs increase.

If you think you have an idea that hasn’t already been suggested that would both work and achieve consensus in the community, feel free to send it to us for a review, or make a proposal to the network.

42. **Why isn’t DCG proposing other community solutions?**

DCG has done due diligence on all community proposed solutions, other solutions either lead to heavy centralization for Platform, heavily reduce the ROI of nodes, or are simply not feasible without significant delay for launch.

43. **Would DCG respect the vote if a non DCG proposal were to win the vote?**

DCG would respect the vote.

There are a few exceptions though:

* If the solution proposed isn’t technically possible.
* If the solution proposed is not clearly defined and in our best efforts we can not figure out a clear implementation plan. In this case we will ask the proposer for an implementation plan.
* If the solution proposed could lead to a level of centralization such that there would be a chance that just two entities could steal funds locked up in the Platform chain by having more than two thirds of Platform nodes.
* That the solution has a vulnerability leading to a loss of funds.

In the case of a proposal that would add a significant amount of additional work, DCG would estimate the delay incurred by the solution, and potentially make another vote confirming the intention of the network.

## Suggested Alternatives

### From Krilen ([Link](https://www.dash.org/forum/threads/distributed-platform-storage-avoids-high-performance-nodes.53400/))

**Summary**:

Shard Platform storage.

**DCG Thoughts and Review**:

This solution requires sharding and would take at least one and likely multiple years to implement. This is not a viable solution if we wish to release Platform in a timely fashion. We will likely introduce sharding at some time in the future once Platform usage has grown and can no longer scale vertically. See question 22 for some relevant details on sharding.

### From Rion Gull ([Link](https://www.dash.org/forum/threads/should-platform-run-on-all-nodes-or-should-platform-run-only-on-high-performance-nodes.53374/post-232537))

The proposal has changed from the original link. We are giving the updated summary here based on the information that DCG currently has. An updated summary with thoughts and review will be provided if the proposal changes.

**Summary**:

*Keep collateral at 1K.

*Reward Platform at 20%.

*Reward Platform nodes only through Platform.

*Require Masternodes that run Platform to lock their collateral for some period of time.

**DCG Thoughts and Review**:

By only sending 20% to Platform there wouldn't be enough incentive for enough Masternodes to run Platform. This would lead to a small enough subset that could cause Platform to be dangerously centralized. (See question 17).

Rewarding Platform nodes only through Platform while they are still serving the Core payment chain is less than desirable. (See question 16).

There is no evidence that collateral locking would reduce the number of big whales on Platform. Hence we do not see a strong advantage of locking collateral.

Bonding/Unbonding periods are not the same thing as collateral locking. The former are used in delegated proof of stake where a user can bond/unbond their stake from a specific validator.

### From Denk ([Link](https://www.dash.org/forum/threads/should-platform-run-on-all-nodes-or-should-platform-run-only-on-high-performance-nodes.53374/post-232473))

**Summary**:

Keep collateral at 1K, set a hard cap on the number of Platform nodes, remove Platform nodes from receiving Core block rewards, and require proof of ownership of some number of non-Platform nodes to ensure decentralization.

**DCG Thoughts and Review**:

This solution relies on setting a hard cap on the number of Platform nodes, which again would introduce a serious security vulnerability and disallow some users to participate in hosting Platform even if they wanted and could afford to. See question 17 for more details on the issues with a hard cap.
