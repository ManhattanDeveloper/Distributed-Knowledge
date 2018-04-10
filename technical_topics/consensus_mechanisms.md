# Consensus Mechanisms

## Introduction to Consensus Protocols

Consensus protocols dictate which block should proceed the current block and insure adversaries don’t compromise the integrity of the blockchain.

## Proof of Work

Miners compete in a cryptographic challenge for the ability to add the next block to the chain. For their efforts, they’re awarded newly minted coins and a transaction fee. Proof of Work is often criticised for its inefficiency and excessive power consumption.

## Proof of Stake

Proof of stake utilizes validators; in this consensus algorithm, validators stake coins in the system. This means they deposit the coins into the system with restrictions on when and how they can pull the coins out. Participants in this algorithm are called validators instead of miners since no new coins are usually created. These validators are paid in transaction fees. In this scheme your chances of being selected to create the next block are proportional to your percent ownership of stacked coins in the system. 

Ethereum plans to move to proof of stake. 

## Proof of Burn 

Proof of Burn is similar to Proof of Stake; however, instead of staking coins, a user would burn coins. Whereas with staking the user is able to retrieve their funds under certain conditions, with Proof of Burn, the coins are sent to an unused address, meaning they can never be retrieved. Your probability of being selected for the next block is proportional to the amount of coins you burned. For example if you burn 1000 coins and there were 1,000,000 coins total burned in the system, there is a 0.1% chance of you being selected for the next block. 

## Proof of Elapsed Time

Developed by Intel, Proof of Elapsed Time runs on their custom TEE (trusted execution environment). This means that you need to trust Intel and their TEE capable hardware. The TEE is used to ensure a user is selected for the next block on a lottery basis after an amount of elapsed time. By using the TEE, Intel provides a guarantee on the duration of time passed. Although this requires hardware investment, it is much more efficient than Proof of Work.  


