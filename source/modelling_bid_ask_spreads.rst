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
While the bid-ask spread in the paper of Duffie et al was expalained by a
marketmaker's bargaining power, Gloston and Milgrom explain the spread through
asymmetric information. The spread is necessary for an uniformed marketmaker to
just break even in the face of trading with superior informed traders. 
Gloson and Milgrom postulate a model with two types of agents, (Potentially)
informed traders and uniformed marketmakers. The agents trade in an
(stochastic) asset which yields a payout at some future data. Traders have
private information about the final payout, but also have some liquditiy motive
for trading. Marketmaker hold inventory over the asset, do not have private
information about the asset, but can discern the trader's valuation from their
decision to buy or sell an asset. The marketmaker can set a bid and and ask
price. Note, that in Gloston and Milgrom's paper, Bid and Ask prices are
reversed: The bid price is the price at which the marketmaker is willing to buy
an asset, and the ask price is the price at which he is willing to sell. Thus,
ask prices exceeds bids. The bid price is then set to be the marketmakers
valuaton of the asset conditional on the trader wanting the sell the asset:
Suppose so far, the marketmaker thinks the valuation of the asset is $V$, and
the markemaker would be willing to buy the asset at $P=V$. If the next trader
however would be willing to sell the asset at that price, the markemaker might
be tempted to revise his valuation of the asset downwards. Thus, the bid price
equals the markemakers valuation of the asset condtional on the next traders
electing to sell the asset.


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

Kyle (1985); Continuous Auction Trading
---------------------------------------


Ho and Stoll (1981)
-------------------
Inventory Costs?



*Questions*
-----------
- I am not sure why there are two types of agents
- What is the horizon of the bid and ask spreads? How long are they in the
  order book?
- I do not understand if, from a modelling perspective, it makes sense to
  combine the liquidity providers and the traders in one agent (as we have done
  it in the double aution market) or whether these should be separate agents.
- I also have not understood the role of budget constraints here
