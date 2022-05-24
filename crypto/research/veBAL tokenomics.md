## Introducing veBAL tokenomics
##### Summary of the article published on 
https://forum.balancer.fi/t/introducing-vebal-tokenomics/2512

### The core proposal 

Curve's tokenomics - To prevent spending additional time with non core development,
Balancer Protocol want to use the tokenomics used and battle-tested by Curve.

Curve will be used as all around solution for Balancer protokol tokenomics.

Aims to be a top LM protocol easy to build on top/ plug in.





#### Problems of the Balancer ecosystem
- BAL minting is not automated and the inflation schedule is not yet locked forever.
    This reduces predictability and trust in the overall system.
- BAL holders do not have any direct power over how BAL liquidity mining gets distributed.
- Lack of a mechanism for distribution of protocol level fees, 
    which have recently been approved by governance
    



#### Balancer Pool Token (BPT)

Instead of pure BAL, BPT of the 80/20 BAL/ETH pool[4] 17 will be locked into veBAL, 
similar to how CRV can be locked into veCRV. This has the big advantage of 
keeping BAL liquid as well as setting a precedent for other teams to do the 
same with their 80/20 Balancer pools.




### veBAL and governance power

The team wants to incentivize locking value.
All votes, onchain or on snapshot, will be done considering veBAL balances 
instead of BAL balances as happens today. This ensures long-term alignment as 
only users locking BPT will have a say in Balancer’s governance.


##### Locking duration
To get veBAL, BPT must be locked for chosen time in between 1 week to 1 year.



#### Balancer inflation schedule

Every 4 years the inflation should be halved, with gradual steps every year.

The final BAl supply will be about 94mil BAL. And the new inflation schedule
will be immutable.




#### Onchain gauge system

The new system liq. mining BAL minted will be distributed by on chain gauge system.
Gauges - contracts allowing LPs to stake their BPT and claim BAL from liq. mining.

Amount recieved by each LP depend on:

-    how much the pool they are providing liquidity to receives
-    what share of the pool’s liquidity they have
-    the boost applied to their LP share based on how much veBAL they hold

Each pool receives a share of the total BAL minted every week. 
That share is defined by how much veBAL voted for that pool.



#### Gauge types

1)  Liquidity Mining committee: 10% (14,500 BAL)
2)  veBAL: 10% (14,500 BAL)
3)  Ethereum mainnet pools: 56% (81,200 BAL)
4)  Polygon pools: 17% (24,650 BAL)
5)  Arbitrum pools: 7% (10,150 BAL)

New gauge types can be added and the weights/percentages of all gauge types
 can be changed by governance. 
 
 
#### Protocol revenue distribution

75% of protocol revenues collected by the protocol fee collector will be 
distributed to veBAL holders. The other 25% of the fees will be kept by the DAO treasury as a reserve.

Treasury subDAO concolidates fees from possible thousands of pools (* tokens)
in gass-eficient way. Will be replaced in future by Curve’s burner contracts type of smart contract.

#### The system is not upgradable

Alike curve. Only possibility is to abandon it and start a new one - one year delay implementation.


#### Benefits of this system

- Predictability
- Long-term alignment over short term speculation
- Plug&play compatibility with Curve’s ecosystem
- Developer time/effort saved for core Balancer work
- Motivation for other DAOs to take a position in Balancer beyond just token-swaps.



#### Risk assessment/mitigation 

- Immutability of the system will likely be a problem at some point in the distant future
- Platforms built on top (like Convex on Curve) can take over control with central points of failure.
   
    - only projects which let token holders vote directly with their voting power (instead of delegating all their power to a multisig) will be approved.
    ping    
    

