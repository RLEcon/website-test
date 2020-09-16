************************************************
Different Approaches to Model the Bid-Ask Spread
************************************************

Duffie (OTC Markets)
--------------------
Bid-ask spreads are described via a search model with three participatens.
Potential buyers and seller are randomly matched and bargain about the price
for a trade. That bargaining process is influenced by their outside options.
Interestingly, the autcome of this bargaining process is not a bid-ask spread
but only a price, in the same way as it was in the example Joao showed. The
investor are motivated to buy and sell the asset by exogenous shocks. Besides
trading with another investor, the traders might also be matched with a
marketmarker. The marketmaker can both buy and sell an asset and therefore be
considered as "investory" for a seller and source of asset for a buyer. The
``Bid`` is the price at which the marketmaker buys from the seller, and the 
``Ask`` is the price at which the marketmaker sells to an investor. Crucially,
bid and ask only exists because of the marketmaker. The anaylsis in the paper
shows that if the marketmaker has zero bargaining power, the bid-ask spread
collapses to zero. Similiarly, if the direct meeting technology between
investors improves, the bid-ask spread falls. 

Gloston and Milgrom
-------------------
Bid-ask spreads are also result in an interaction with marketmakers, this time
it is explained by asymmetric information. The marketmeter sets the bid and ask
prices so that he makes zero profit in the face of tradining with superior
informed traders. The ask price, for example, is such that the marketmaker has
no incentive to revise his valuation of the asset, if the next investor is a
buyer. (I do not understand why the ask does not exceed the bid, that doesn't
make sense though).


Glosten: (Electronic Limit Order Book)
--------------------------------------
This is a very interesting article, and one that describes the existence of
bid-ask spreads even in the absence of marketmakers. The set-up of the economy
very much resembles a realistic set-up we could use, but I have to undersand
the entire paper much better to say something meaningful about it.
Nevertheless, there are two types of agents in the economy. A continuous of
risk aversve buyer and sellers which take a schedule of bids and ask prices as
given. This function describe the marginal costs of buying (selling) a
particular quantitiy of assets. These agents buy and sell assets in order to
maximize their expected utility. The other types of agents are randonly
arriving liquidtiy providers, which provide bids and asks. These types of
agents are risk-neural and take the behaviour of the buyers as given. The
liquidity providers seem to trade on private information. Based on these two
groups of agents and equilibrium is characterized. There seems to be a
parmanent bid and ask spread but I have not yet understood the reason for it.

*Questions*
-----------
- I am not sure why there are two types of agents
- What is the horizon of the bid and ask spreads? How long are they in the
  order book?
