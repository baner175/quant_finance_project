# Quant Finance Project

This repository contains the final project for a Quantitative Finance course, developed by Aritra Banerjee. It comprises four modules covering core topics in financial modeling, portfolio analysis, and options pricing.

## 📁 Project Structure

The project is divided into four main components:

### 1. Portfolio Optimization
- Constructs and compares low-risk and high-return portfolios using Apple, Microsoft, Netflix, and NVIDIA.
- High-risk portfolio is constrained to outperform Google's return from 2019–2022.
- Optimization is performed using historical daily returns.

### 2. Normality of Log-Returns
- Tests for normality in the daily log-returns of selected stocks (e.g., Tesla, Amazon, Meta).
- Applies outlier removal using the 1.5 IQR rule.
- Visualizes return distributions and assesses deviation from Gaussian behavior.

### 3. Option Price Sensitivity
- Analyzes how European call and put option prices respond to changes in input parameters.
- Sensitivity explored across strike price and time to expiration.

### 4. Stochastic Volatility Modeling
- Simulates stock paths under the Heston model.
- Evaluates delta-hedging strategies with different rebalancing frequencies.
- Compares mean of simulated call values with those from the Black-Scholes and Heston models.

## 📊 Key Findings

- High-risk portfolio outperforms Google’s returns while maintaining reasonable volatility.
- Log-returns show significant deviation from normality, justifying more robust risk modeling.
- Option pricing is highly sensitive to parameter changes.
- Under stochastic volatility, the Black-Scholes model underperforms compared to Heston-based pricing.