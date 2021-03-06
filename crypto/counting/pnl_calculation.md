---
title: Profit and Loss Calculation
author: serinko
header-includes: |
    \usepackage{amsmath}
Abstract: Basic formulas to understand % price movement 
---
# Introduction
For anyone moving in finance/crypto, is completelly vital to understand and calculate % movement of assets, and their reflection in the value of the holdings - PnL.


# PROFIT and LOSS CALCULATION

* **n** - *Initial investment*
* **Pen** - *Entry price*
* **Pex** - *Exit price*
* **PnL** - *Profit & Loss*


## BUY/LONG

**Formula to calculate profit:**

```latex
$$
PnL = (Pex/Pen*n) - n
$$
```

Example. Kawa bought Bitcoin for $1000 at a cost of $40000 and sold on $60000. 
What is Kawa's profit?

* *n* = $1000
* *Pen* = $40000
* *Pex* = $60000
* *PnL* = ?

```latex
$$
PnL = (60000/40000*1000) - 1000
PnL = (1.5 * 1000) - 1000
PnL = 1500 - 1000
PnL = 500
$$
```
Kawa made $500 proft on this investment/trade.


## SELL / SHORT

**Formula to calculate profit is reversed**
```latex
$$
PnL = n-(Pex/Pen*n)
$$
```
Example. Kawa sold his Bitcoin in the profit at Bitcoin price $60000 and had $1500 in cash. 
He held onto it as the Bitcoin felt down and decided to re-buy same ammount of Bitcoin he had at $60000, at $40000. 
What's the profit he made in comparison he would kept money in Bitcoin?

* *n* = $1500
* *Pen* = $60000
* *Pex* = $4000
* *PnL* = ?

```latex
$$
PnL = 1500-(40000/60000*1500)
PnL = 1500-(40000/60000*1500)
PnL = 1500-(0.6666*1500)
PnL = 1500-1000
PnL = 500
$$
```
Kawa made $500, while Kawa's Bitcoin ammount is the same.
Such way Kawa of making profit on volatily is often refered to as - buying low, selling high.

### Shorting

What if Kawa never had any Bitcoin and heared about it only at $60000 when every friend talked about it, 
and Kawa thought that when even black smiths re-tweed about trading, the market my be on it's peak and decided tp *SHORT* Bitcoin. 
That means that Kawa borrows Bitcoin worth of $1000 and immediately *SELLs* it. When Bitcoin drops to $40000 price, Kawa *BUY* Bitcoin, and returns the loan. 
The difference will be his profit in $.

* n = $1000
* Pen = $60000
* Pex = $4000
* PnL = ?
* PnL = 1000-(40000/60000*1000)
* PnL = 1000-(40000/60000*1000)
* PnL = 1000-(0.6666*1000)
* PnL = 1000-666.66
* PnL = 333.33

Kawa made $333.33 profit on Borrowing and selling 1000 $Btc (1000USD worth of BTC) @60000$ and buying and returning - 
CLOSING POSITION - at 40000$.


**Percentage matters (not movement of units)**

We Can see something very interesting. However the price movement in between 40000 and 60000 is the same like in between 
60000 and 40000, meaning 20000, the profit of BUYing and SELLing an asset worth of $1000 is not the same. 

That's why we aren't so interested about the price movement in units (ie dollars), but about the CHANGE OF % in between Pen and Pex. 
That % is what we focus on, to count the profit or loss (PnL). From 40k to 60k we need to go 50% up. Therefore if those are our Pen and Pex, 
we made 50% profit, while the fall from 60k to 40k is only 33.3%, therefore we made 33.3% profit (or loss).

That means that if an asset you bought falls in price of 33.3%, you need 50% grow to get back to 0,-. However SELLing/SHORTing seems to give
smaller gains on the price movement, the benefit of SELLing high lies in the fact that instead of waiting to get back to 0 if not sold, in
this case, if re-bought on 40k, by the time it's back on 60k, you are not back on zero but 33% and 50% in profit. That is a big difference. 
So often selling is a way to get in cheaper, later.

## Disclaimers

Be aware that there is no an easy way to predict prices and to borrow assets in order to sell it and re-buy it later to pay the loan in profit, as well as buy any risky asset with the hope of getting up - 
the marjet may go against you and the mathematic of PnL applies reverse and you counting losses!!!

Disclaimer: Kawa is not so interested in speculating and trading in generall. Only market Kawa follows is to short $TRYB, while he never 
wants to put his hand on that coin. How to do that - to SHORT an asset, you do not want to handle - will be explained in another document.
