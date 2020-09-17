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
This is a very interesting article. The paper seems to be to me an extension of
his older paper with Milgrom. Glosten seesm to allow traders a larger action
space (they can decide not only whether to buy or sell at a given bid and ask
but also how much). Suppliers of bid and asks therefore seem to find it optimal
to provide a schedule of bids and asks at different prices. The traders have
superior information and take the schedule (limit order schedule) of bid and
aks as given. The traders receive (potentially) private information and when it
is (stochastically) they turn to decide to trade, their trading decisions are
maximizing their expected utility. Liquidity suppliers take the behaviour of
the traders as given and can provide bid and aks spreads. *A description of the
behaviour of the liquidity providers follows later*

Kyle (1985)
-----------
I should have a look at this paper again. 

*Questions*
-----------
- I am not sure why there are two types of agents
- What is the horizon of the bid and ask spreads? How long are they in the
  order book?
- I do not understand if, from a modelling perspective, it makes sense to
  combine the liquidity providers and the traders in one agent (as we have done
  it in the double aution market) or whether these should be separate agents.
- I also have not understood the role of budget constraints here


