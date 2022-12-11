## Overview of the Analysis: Financial-Planning
Using an Alpaca API and Monte Carlo simulation, this repository focuses on creating a financial plan for emergencies and retirement for a credit union company members. First part of this project is to create a financial planner for emergencies by estimating a member's monthly income and accessing current bitcoin and ethereum prices to help with the next step. After we get the cyrpto prices, we now need to evaluate, how much crypto, stock, and bonds they have in their portfolio. Technology that was used to get prices for both crypto and stocks/bonds were using by JSON and Alpaca API calls. Next, we now need to evaluate the emergency fund by setting it up in dataframe, and visualizing the portfolio using a pie chart. We then set the value of the emergency fund, which will be three times the value of the member's monthly income. The last part of this section will then need to create conditional statements to see if the total portfolio value will be enough to fund the emergency portfolio. In Part 2, we will now create the financial planner for retirement by using a
Monte Carlo simulation for thirty years (60/40 split for stock/bonds) and ten years (80/20 split). We will then determine which plan will better suit the client's financial goal. 

## Technology 
Pandas, Json, Alpaca Trade API, Monte Carlo Simulation, MatPlotlib


## Results and Summary
Savings(Crypto/Stock) Plot: 
https://github.com/simonab57/Financial-Planning/blob/929f264727c00c3ff28690e37f8f598442107ce1/Savings%20Plot.png

30-yr Monte-Carlo Similation of Cumulative Portfolio Return Trajectories: 
https://github.com/simonab57/Financial-Planning/blob/929f264727c00c3ff28690e37f8f598442107ce1/30-yr%20Monte%20Carlo%20Simulation.png

Probability of Distributions for 30-yr Monte-Carlo Simulation:
https://github.com/simonab57/Financial-Planning/blob/929f264727c00c3ff28690e37f8f598442107ce1/30-yr%20Probability%20Distribution.png

