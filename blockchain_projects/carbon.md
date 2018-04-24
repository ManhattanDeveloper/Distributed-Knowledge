# Carbon:
## General Information

* Online Presence: 
  * [Website](https://www.carbon.money/), [Whitepaper](https://www.carbon.money/whitepaper.pdf), [Telegram](https://telegram.me/carbon_money), [Medium](https://medium.com/@carbon_money), [Twitter](https://twitter.com/carbon_money),  

* Team Leads: 
  * Connor Lin (Co-Founder)
  * Gavin Mai (Co-Founder)
  * Miles Albert (Co-Founder)
  * Samuel Trautwein (Co-Founder)
  * Mike Miller (Designer & Developer)

Announcement Date: April 3rd, 2018

## Description
Carbon is a price-stable cryptocurency (stablecoin) aimed at the payments space. Carbon aims to provide blockchain powered payment solutions by providing a coin that holds stable value against the USD.  Carbon is built on the Hedera Hashgraph public ledger system, a platform aimed at providing more transaction throughput than currently existing networks.  

The Carbon protocol attempts to provide stability by incorporating an “elastic supply policy” that adjusts quantity supplied of the coin, attempting to maintain a price of $1/coin. Each day, Carbon utilizes a schelling point scheme to determine the exchange rate. Nodes on the platform submit a bid of what the exchange rate should be; after the submission of the exchange rate, the protocol takes a weighted average to determine a “true” exchange rate. Users who submitted values between the 25th-75th percentile of the “true” exchange rate are awarded coins based on a normal distribution relative to the mean. 

To account for changes in demand, Carbon features an Aztec Model to support expansionary and contractionary cycles. Based on the levels of demand for the coin, the Carbon protocol can prescribe contraction or expansion in the supply of the coin. When contraction occurs (coins trade < $1), users are incentivized to remove coins from circulation by purchasing Carbon Credit. This Carbon Credit is the demand altering mechanism of the system, while the Carbon Stablecoin is the USD stable coin component of the protocol. When contraction occurs, the protocol auctions Carbon Credits in a reverse dutch auction to participants in exchange for burning Carbon Stablecoin until the price appreciates. During expansion (coins trade > $1), coins are distributed to Carbon Credit holders to create greater supply of Carbon Stablecoin, and therefore reduce the price of the coin. 
