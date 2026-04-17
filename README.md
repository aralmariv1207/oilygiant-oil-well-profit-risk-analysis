# OilyGiant: Oil Well Profit Risk Analysis

## About

Identifies the most lucrative geographic region for OilyGiant to develop 200 new oil wells. By combining predictive modeling with financial simulations, its goal is to find a region where the risk of loss is less than **2.5%** while maximizing potential profit.

## Technical Highlights

· **Model Implementation**: Trained Linear Regression models for three distinct regions to predict reserve volumes.

· **Reserve Evaluation**: Calculated a break-even threshold of **111.11 units** per well and compared it against the average predicted reserves per region.

· **Bootstrapping Technique**: Performed **1,000 iterations** of bootstrapping to simulate profit distributions and define the **95% confidence interval**.

· **Risk Mitigation**: Quantified the probability of loss for each region, recommending the only region that met the strict **2.5% maximum risk** requirement.
