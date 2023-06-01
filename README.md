# Index-tracking
Using Least Squares Method and Quadratic Programming Method with different constraint to calculate optimal solution for index tracking

# What is index tracking?

Index tracking, also known as passive management, is a strategy used by investment funds that aims to generate returns similar to a specific market index. The fund will choose and manage its investments to mirror the holdings of the selected index. For instance, a fund tracking the S&P 500 index will hold the same 500 stocks in approximately the same proportions as they appear in that index.

# Why we choose index tracking?

- **Diversification:** Index funds are typically made up of a wide range of assets, which can provide investors with broad exposure to different segments of the market, thereby reducing risk.

- **Low costs:** Since index tracking involves simply replicating the holdings of an index, it doesn't require as much active management and thus has lower management fees than actively managed funds.

- **Performance:** It's difficult for active managers to consistently outperform the market over long periods. Therefore, simply tracking the market index tends to generate competitive returns over time.

# How we choose the components of portfolio?

We chosed 11 S&P indexs to run the index tracking. In the code, we will select each of the S&P index as the goal index, and try to find optimal weights for the other 10 indexs to minimize the varience between the goal index and the portfolio.

Here are the ten index:

1. SPXESFUT	
2. SPXESUP	
3. SPXETCT (Heavy)	
4. SPXETCT (Light)	
5. SPXETCT (Moderate)	
6. SPXETCT	
7. SPXELSUP	
8. SPRESUP	
9. SPMESUP	
10. SPSESUP	
11. S&P United States LargeMidCap ESG Index

# How to solve the optimal weights for components?
# Performance
