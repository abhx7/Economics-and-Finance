# Options Theory for Professional Trading

**Introduction to Options**
- Price can move in 3 ways - increase, decrease or stay the same
- In example, person A pays a non refundable fee person B bounding him to an obligation of selling the land in 6 months time if he decides to buy it (if the road project happens, land becomes more valuable) ; if land price increases, he will want to buy at decided price; if price decreases, he will not buy it and forfeits the premium paid; if price doesnt change, he will not buy and again premium paid is a profit to buyer; this is exactly
- Options are leveraged instruments
- While trading options, a buyer pays a small amount of money (premium) to controls a large amount of position
- Timing, speed and direction of the trade needs to be right in order to make money
---
**Options Jargons**
- For example,  SBIN OCT 460 CE
  - stock under consideration or underlying  (SBI)
  - expiry, is last Thursday of the month
  - strike price is price that deal would be made on settlement day
  - option type  is call (CE is European)
  - premium (Rs 17.75)
  - lot size
- Risk? Worst Case Scenario? Break Even Point? Maximum Gain?
---
**Long Call Payoff and Short Call Trade**
- profitability of a call option for a buyer and seller
- 3 cases to consider - stock price rallies, remains the same and declines
- Stock price rallies is only situation for profit, if price remains same or declines, buyer will lose the premium paid and will be in a loss
- Buy call option when you are bullish on the underlying until expiry
- Long call payoff chart, max loss is restricted to premium paid, breaking point is when there is no loss or profit (= strike pric + premium paid)
- max loss of buyer is max profit, but breaking point stay same; the payoff chart is inverted so loss can keep on increasing if price drops for seller
---
**Put Buy and Put Sell**
- to have the right to sell a stock at a higher price than market price is called put option buyer
- if market price decreases, realised profit is strike price minus current price, after removing premium from this is net profit
- if market price increases, we let go off the right to sell but also lose the premium paid
- if market price stays flat, no sense in exercising right so we walk away and loose the premium
- hence, you make money is market falls and lose money is it stays flat or increases; keeping expiry in perspective
- payoff structure for put option buyer payoff shows loss is restricted to the premium paid; similarly for put option seller payoff is inverted/upside-down
- break even point for buyer is fall in market price should be equal to premium paid and for seller is the same but market should increase
---
**Summarizing Call and Put Options**
- Buy a call option or sell a put option when your POV is bullish and buy a put option ot sell a call option when your POV is bearish
- options selling margin (similar to futures margin) is span + exposure
- options are pretty complicated
- options you can exit as when you want to; premium changes with time along with underlying so exit as and when you decide is appropriate
- who sets the premium? which strike prace to trade? what are the influences that drive the premium?
---
**Moneyness of option**
- Moneyness of option indicates how an option by expiry will end up in a favourable outcome to the buyer
- For Call option buyer favourable, it is price of underlying should increase
- For Put option buyer favourable, it  is price of underlying should decrease
- Look at all strike prices available to trade from the " " sheet and the last traded price
- At the money (ATM) option means it is favourable to call option buyer when strik price is same as underlying price at the current time , not expiry
- In the money (ITM) option means it is favourable to call option buyer when strik price is above underlying price at the current time , not expiry
- Out of  the money (OTM) option means it is not favourable to call option buyer when strik price is below underlying price at the current time , not expiry
- Option chain is the sheet for call option, same thing for put
- ITM has higher premium than others and activtiy is higher at ATM, regardless of call or put
---
**The Option Greeks - Delta**
- Factors that influence the premium of an option are option greeks (gamma, delta, vega, theta)
- if underlying price increases, premium also increases and if underlying decreases than put option premium increases.
- load few option strikes and observe how premium changes with underlying prices
- delta of an option helps us understand the likely change in premium wrt underlying; varies from 0 to 1 for call option and -1 to 0 for put option
- cheatsheat for delta
  - call
    - OTM : 0 to 0.5
    - ATM : 0.5
    - ITM : 0.5 to 1
  - put
    - ITM : - 0.5 to -1
    - ATM : - 0.5
    - OTM : - 0.5 to 0
- use delta to evaluate the probability of a strike expiring in the money
- choose option that has low delta for call option so that u can pocket your entire premium buyer paid (go back to vid and lectures; explain more in detail)
- same company if you have long and call, you can add the delta for total delta
- what makes the delta move?
---
**Gamma**
- retail trader does not need gamma
- gamma is the rate of change of delta wrt rate of change of underlying of option; it is also called the curvature of an option
- usually expressed in term of deltas gained or lost per point change in the underlying
- review the example again
- gamma is highest at ATM option so rapid and high change in delta but is slow and low for ITM or OTM options
- never short ITM and ATM in expectation of otpions expiring worthless; but always choose an OTM option to sell'
---
**Theta**
- more time means higher chance of something happening in that time
- transition from OTM to ATM to ITM of an option is likelier with more time
- high premium for high expiry time and vice versa due to risk/chance factor; this is based on expectation of option sellers
- theta is rate of change of premium wrt time
- try to break down valaue of an option into intrisic value and time value
- difference between spot and strike is what you will relise if you exercise the option right now, this is intrinsic value; the remaning from premium is time value
- theta increases closer to expiry; so its referred to as a deprecciating asset; always works in favour of seller and against the seller
---
**Vega**
- Read chapters to understand volatility
- volatility is like speed at which stock price is rising, so high volatility means that stock might expire ITM so higher premium and vice vera
- rate of change of premium wrt change in volatility is captured by vega of an option
- as an option seller you want to sell it when volatility high and should decrease after selling and vice versa for an option buyer
- all these options greeks act simultanesously so it is a complex phenomenon
---
**Margins**
- Options M2M and P&L calculation
- For buying Options, you pay premium equal to lot size into premium into lots you want to buy
- For selling options, you need to pay a margin and it is released when you square off; margin is higher with higher risk
- volatility is also a measure of risk so high volatility means higher margin required
- margin can be altered by reducing risk of portfolio for example if going long in one stock and if it decreases then also have a put option buy to offset the loss, if the reverse happens the maximum loss through put option is the premium but lots of profit for sell/long option
- options strategies or spreads
---
**Physical settlement of futures and options**
- all itm are subjected to physical settlement
- implies give or take of delivery of stocks
- market conditions call will have long call or short call and same for put; itm call long and itm put short you have to take delivery of stock and for itm call short and itm put long you have to give delivery of stock
- option buyer should have enough money to buy the stock and the seller should have enough stocks to sell
-  margin requirements towards the end of the expiry increases in case the trader has stock option position
-  make sure you buy the stocks 2 days prior to the expiry
-  stock options are physically setlled, index options are cash setlled
-  brokers charge a brokerage on physical delivery
-  offsetting a position, when net obligation are zero so no physical setllement (read details)
---
**Bull call spread**
- a naked option position, carries an extreme amount of overnight risk
- spreads are usually multi legged options strategies involving 2 or more options contracts
- bull call spread is executed when you are moderately bullish on a stock/index in which we buy a atm call option (first leg) and sell otm call option (second leg); same underlying and same expiry
- difference between the strikes is called spread, bull call spread usually results in net debit
- irrespective of up and down of market, we can visualise maximum losses or gains in the bull call spread 
---



## FAQ
