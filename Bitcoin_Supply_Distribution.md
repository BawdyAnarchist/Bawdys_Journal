Bitcoin Supply Distribution - A Basic Analysis

Egalitarian competion for creation of new blocks (mining), was a crucial design parameter for Bitcoin, as a monetary protocol. Most importantly - it secures censorship resistance by decentralizing the authority to update the ledger, and the minting of new supply (inflation).

The notion of fair play intuits that an open networking protocol aiming to achieve transnational monetary properties, ought to minimize barriers to participation in the minting of new supply.

Over 13 years, Bitcoin has empirically proven (at least) minimally viabile as a censorship resistant public ledger - attributable to a sufficiently distributed mining network. But what does the evidence suggest regarding fair play? Did the the design incentives and implementation, result in a somewhat even distribution of supply? 

Let's take a look at the basic data regarding conentration of coins.

Bitcoin is hard capped at 21M, of which, 19.1M (91%) have already been mined. [Prima facie, we can see that 18M of the 19M coins in existence, are concentrated in just 2% of addresses.](https://bitinfocharts.com/top-100-richest-bitcoin-addresses.html)

By comparison, 32% of US wealth is held by 1% of the population. So at first glance, BTC ownership appears highly centralized. However, there are two mitigating factors which must be considered, and our calculation adjusted. 

Now, because the situation appears so lopsided, I will err on the side of making the maximum adjustment possible. We will give all benefit of the doubt, and make the best possible case for maximum distribution of coin. 

1. Crypto exchanges hold BTC in custody; and a single address (UTXO) can represent millions of customers. So we'll subtract [all exchange-held BTC from the calculation. Currently: **2.3M BTC**](https://cryptoquant.com/asset/btc/chart/exchange-flows/exchange-reserve?exchange=all_exchange&window=DAY&sma=0&ema=0&priceScale=linear&metricScale=linear&chartStyle=line)

Of course this is an over-adjustement. Market makers and hedge funds keep large amounts on exchanges, but again, we're confering all possible benefit of the doubt.

2. Lost Bitcoin should be subtracted as well. [The estimate by Chainalysis](https://blog.chainalysis.com/reports/money-supply/) is between **2.8** and **3.7M**. This includes coin which has never moved (including Satoshi's coin), among other criteria. And again, confering most benefit of the doubt, we'll assum that all lost coin come only from the rich list.

3. Those lost Bitcoin are stored in UTXO which should not be tallied for the percentage of addresses on the rich list. I didn't find an exact number, but let's do this: We reduced the rich list from 17.95M to 14.25M, so proportionately we might say that reduces the UTXOs from 2.07% to 1.64%. Let's round that up to 1.8%. 

4. It's rarely the case that a person has only *one* UTXO. Most people have a handful, or even hundreds. But okay, maybe the rich list skews towards the practice of aggregating their funds. Let's say that each individual on the rich list has only **2** UTXOs. Almost certianly an underestimate, but again, benefit of the doubt. 

Math time:

17.95M (rich list) - 2.3M (exchanges) - 3.7M (lost)  =  11.95M BTC

11.95M ÷ 19.1M  =  62.6%

1.8% (UTXOs remaining after after removing lost coin) ÷ 2 (UTXOs per person) = 0.9%

**RESULTS:  0.9% of persons control about 63% of the supply**. 

Again, this is the absolute best possible case. The actual concentration of wealth is likely significnatly higher. So empirically, we can say that the design implementation was successful in achieving moderately high levels of censorship resistance thus far; but has resulted in a highly concentrated distribution of supply. 

The primary explanations seem obvious:  1) ASICs, and the highly dominant position of Bitmain in ASIC production; and 2) The largest block rewards were made during a time when the fewest people knew of, and participated in the network. 

It remains to be seen whether or not supply will become more distributed over time, what the mechanisms of that might be, and how long that might take. The realization of this heavy concentration of wealth in BTC, should give pause for consideration of a range of questions, such as:
- How has this effected the development of crypto exchanges and market/prices?   
- How has this affected the development and direction of the network?   
- How has this affected the development and direction of crypto in general?   
- How does it compare against other crypto networks?    
- Who are the players with the largest concentrations?
- What kinds of social, corporate, and governmental associations do these players have?   
- What kinds of design improvements could be made?

These questions are for another article. Suffice it to say, the implications are profound, and I hope that no matter your personal crypto persuation, readers will set aside the desire to frame the issue along personal bias, and genuinely reflect on the importance of this reality.
