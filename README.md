# Financial analysis of oil field

## Overview

This repository contains a financial analysis model used to assess the viability of developing an oil field, based on the Net Present Value (NPV) under various oil price scenarios. The analysis includes both fixed input models and a Monte Carlo simulation to handle uncertainty in future oil prices.

## Project Structure

The project covers two main areas:

1. **Fixed input model**:  
   A fixed input model assumes that the oil price is $60 per barrel in the base year and grows at 2.25% annually. The NPV of the oil field is calculated both pre- and post-tax.

2. **Monte Carlo simulation**:  
   A Monte Carlo simulation is performed to assess the risk associated with oil price uncertainty. The simulation uses two models:
   - **Uniform Distribution**: Simulates oil prices between $20 and $100 with equal probability.
   - **Log-normal Distribution**: Models historical oil price data from 1974 to 2024, with simulations run on both nominal and inflation-adjusted prices.

## Key Results

- **Fixed Input Model**:  
  Under the base scenario, the project is viable with a positive NPV. Sensitivity analysis shows that only a significant drop in oil prices would make the project unviable.
  
- **Monte Carlo Simulation**:  
  - **Uniform Distribution**: Shows a 78% probability of a positive NPV.
  - **Log-normal Distribution**:
    - **Nominal Prices**: 40% probability of a positive NPV.
    - **Inflation-Adjusted Prices**: 87% probability of a positive NPV.

## How to Use the Model

1. **Input Data**:  
   Update the `Inputs` sheet with your own assumptions for oil prices, development costs, etc.

2. **Run the Calculations**:  
   The model will automatically calculate NPV based on the inputs provided.

3. **Scenario Analysis**:  
   You can run the scenario analysis by modifying the inputs (e.g., oil price reduction) to see the impact on NPV.

4. **Monte Carlo Simulation**:  
   Modify the parameters of the Monte Carlo simulation to test various distributions and probabilities of success.

## Key Features

- **Automated Calculations**: Calculate key financial metrics such as NPV and IRR based on your input data.
- **Scenario Analysis**: Easily simulate the effect of different input assumptions.
- **Monte Carlo Simulation**: Run probabilistic simulations to assess the likelihood of different outcomes.

## Contribution Guidelines

Contributions are welcome! Please feel free to submit a pull request or raise an issue if you have any suggestions.
