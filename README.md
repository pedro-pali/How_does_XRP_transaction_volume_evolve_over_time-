# **How_does_XRP_transaction_volume_evolve_over_time**

Since 2020 it has been becoming popular the transaction with cryptocoins as Bitcoin, Ethereum, etc. 

In this proyect we analisys one of the top ten usfull and popular: Ripple or XRP, but what is it? and hao is usfull for?
XRP is a fast, low-cost, and energy-efficient cryptocurrency designed for cross-border payments, operating on the open-source XRP Ledger (XRPL). It serves as a bridge currency for financial institutions to settle transactions in 3–5 seconds without mining, boasting high scalability.

**What I did here:**
**Libraries**:
- Pandas 
- Matplotlib

**Seteps**:

- EDA Analyst: I cleaned the titles, put it in minus and snake case, erased the column "Ignore", then convert the columns "Open time" and "Close time" to a datatime, spreaded the "open_time" in year, month, week and date.

- Create a bart chart: I used the next code to plot the bar chart:
plt.figure()
plt.plot(xrp['session_date'], xrp['quote_asset_volume'])
plt.title('XRP Transaction Volume Over Time')
plt.xlabel('Open Time')
plt.ylabel('Asset Volume')
plt.show()

**Coclusion**:
XRP has been years when the volume is for far more than others, staring 2021 reach almost the 4e7 just one year after the pandemic. the highest in the history asset volume was in 2024-12-02 with a quote of 68398157.907947.
We can say it has a lot of volatility. Can be a good asset for a professional traders.

