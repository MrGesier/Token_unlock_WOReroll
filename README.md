# Dynamic TVL Distribution Tool

This tool is designed to dynamically create and manage statistical distributions for simulating Total Value Locked (TVL) data. The application is built using Streamlit and provides a user-friendly interface for configuring parameters and visualizing distributions.

---

## Current Use Cases

### 1. Monitor Token Unlock & Sell Pressure
- **Real-time visualization** of token unlock schedules based on vesting parameters.
- Identify **key sell-off peaks** (e.g., team, seed investors, marketing).
- Compare unlock values with the token price to anticipate **high-sell zones**.

### 2. Simulating and Monitoring Token Prices (Black-Scholes)
- Predict token price movements based on **volatility (σ)** and **expected returns (μ)**.
- Visualize **ROI thresholds** that dynamically trigger increased sell pressure.

### 3. Managing Dynamic Liquidity (Market Depth Provisioning)
- Identify periods where **market depth** is insufficient to absorb token sales.
- Strategically allocate liquidity to counter potential overflow.
- Add liquidity to DEX/CEX during **potential unlock peaks**.
- Launch staking or incentive programs to **lock tokens** and reduce sell pressure.

### 4. Optimizing Staking or Lock-up Programs
- Deploy staking programs or lock-up mechanisms for specific investor categories (e.g., team, pre-seed).
- Offer incentives (e.g., rewards or higher APY) to retain tokens for longer periods.

### 5. Tracking Marketing Unlocks and Strategic Allocation
- Plan marketing campaigns: ads, promotions, events, and community growth.
- Quantify token budgets to align **marketing activities** with liquidity and price goals.

### 6. Managing Rewards Distribution and Incentives
- Strategically distribute reward tokens over time to incentivize community and project engagement.
- Prevent **oversaturation** of tokens in the market.

### 7. Overflow Scenario Analysis
- Visualize the overflow of tokens sold that exceeds **market depth**.
- Adjust liquidity provisioning or slow unlock schedules to balance supply and demand.

### 8. Dynamic Vesting Adjustments Based on Market Conditions (Bonding Surface)
- Adjust vesting parameters dynamically based on **real-time market conditions**.
- Increased volatility → Modify price simulations to account for market risks.
- ROI triggers exceeded → Dynamically adjust **sell pressure percentages (SP %)**.

---

## Upcoming Features & Use Cases

### 1. Evaluating ROI for Investors
- Display the **Return on Investment (ROI)** based on token price simulations.
- Provide visibility on **ROI thresholds** that trigger increased sell pressure (dynamic SP).

### 2. Real-time Investor Communication and Reporting
- Enhance **transparency** for investors and stakeholders.

### 3. Depletion Analysis for Treasury
- Visualize and predict treasury depletion scenarios to plan **long-term sustainability**.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the application:
   ```bash
   streamlit run app.py
   ```
2. Open the application in your web browser at `http://localhost:8501`.
3. Configure parameters using the sidebar and interact with the generated data.

---

## File Structure
- `app.py`: Main application script.
- `requirements.txt`: List of dependencies.
- `README.md`: Project documentation.

---

## Contributing
Feel free to open issues or submit pull requests for new features or improvements.

---

## License
This project is licensed under the [MIT License](LICENSE).
