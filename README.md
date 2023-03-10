# options-pricing-tools-and-trading-strategies
In this project, I'll be developing scripts that can be used for performing analysis on options for spreading/hedging strategies.

The objective is to build tools to draw plots so that we can better visualize risk parameters associated with options. 

<br>  

**In this repository:**


Strategy builders:
|Section| File (Link) | Remarks |
|--|--|--|
|Strategy builder |[Short Strangle](https://github.com/kevinhhl/options-pricing-tools-and-trading-strategies/blob/main/Notebooks/Strategy_Builder_Short_Strangle.ipynb) | Short strangle. Selling calls and puts at a 1:1 ratio. |
|" |[Long Butterfly](https://github.com/kevinhhl/options-pricing-tools-and-trading-strategies/blob/main/Notebooks/Strategy_Builder_Long_Butterfly.ipynb) | Long Butterfly is similar to a Short Strangle but it has protection against the downsides.  |


Building blocks:

|Section| File (Link) | Remarks |
|--|--|--|
|Black Scholes Model (BSM)| [BSM Part 1](https://github.com/kevinhhl/options-pricing-tools-and-trading-strategies/blob/main/Notebooks/Black_Scholes_Merton_Model_Part1_Screening_YF_for_theoretical_edges.ipynb) | Options screening. Criteria (A) strike price is within a reasonable range, and (B) sorting down output according to theoretical edge values. |
|" |[BSM Part 2](https://github.com/kevinhhl/options-pricing-tools-and-trading-strategies/blob/main/Notebooks/Black_Scholes_Merton_Model_Part2_Position_Analysis.ipynb) | Implementation of data structures for storing Contracts, Legs, and Positions.|
|Implied volatility studies |[Volatility_Surface](https://github.com/kevinhhl/options-pricing-tools-and-trading-strategies/blob/main/Notebooks/Volatility_Surface.ipynb) | Observing volatility smiles. |
