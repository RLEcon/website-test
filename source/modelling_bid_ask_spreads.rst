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
Kyle describes an economy with three types of agents trading a claim to an
asset with publically unknown liquidation value. A trader with private
information about the liquidation value of an asset, a noise trader, and an
uninformed market maker who sets price to equate supply and demand. Kyle
thereby was able to coin a very influential measurement for the asset's
liquidity: Kyle's lambda. The action spaces of the agents are very interesting:
Both the informed and the uninformed (noise) trade submit market orders, that
is they specify the number of assets they want to trade. However, they do not
know the resulting price at which their orders are fulfilled. The market maker
set the price such that his expectations about the asset's liquidation value,
conditional on the sum of the market orders, equals the price of the asset.
Kyle's lambda specifies how much the price of an asset reacts as a function of
the sum of the market orders. The parameter essentially describes how much the
market maker adjusts his expectations about the asset's liquidation value after
observing the order flow. An illiquid market is said to be characterized by a
high lambda. 

Ho and Stoll (1981)
-------------------
This is an interesting classic paper. The paper derives the bid-ask spread
throguh the utility maximizing behaviour of a single dealer. The dealer has a
personal private opinion about a true value of a asset he trades and is exposed
to random matches with a buyer and a seller of the stock. The likelihood of
matches is influenced by the bid-ask spread set by the dealer. For me, the
paper was similar to the profit maximizing behaviour of a monopolist who takes
the demand curve as give. The optimal bid ask spread equals the optimal bid-ask
spread of a risk-neural deal given the exogenous demand, plus adjustments for
uncertainty in transcation volumne, flucuations of the underlying asset, and
risk preferences.
