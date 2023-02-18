# options-pricing-tools-and-trading-strategies

In this repositiory, I'll include scripts that can be used for performing analysis on options for spreading/hedging strategies. 

<br>

## Black-Scholes-Merton Model ("BSM") - Part 1
[<Link to notebook\>](https://github.com/kevinhhl/options-pricing-tools-and-trading-strategies/blob/main/Black_Scholes_Merton_Model_Part1_Screening_YF_for_theoretical_edges.ipynb)
<br>
This script will allow us to obtain options data provided by Yahoo Finance, and then for each quoted contract we will compute the theoretical value of it by applying the BSM. The goal is to find the difference between each contract’s quoted price and its theoretical value to allow us to ask further questions with regards to whether there will possibly be theoretical edges, especially with contracts associated with having the largest theoretical price discrepancies.

<br>


## Black-Scholes-Merton Model (“BSM”) - Part 2

[Work in progress]

In the next update, position analysis will be the focus. We will find ways to present multi-legged spreads in table formats to summarize the common Greeks.
