# Intrinsic-Value-Screener
AI-driven logic for Graham-Dodd fundamental analysis.

⚠️ Intellectual Property Notice
Software License: The source code in this repository is licensed under the MIT License.
Proprietary Logic: The underlying quantitative strategies, specific financial weighting algorithms (e.g., NNWC ratios), and architectural reasoning loops described in this documentation are the Proprietary Intellectual Property of the author.
While the MIT License permits the use and modification of the code, it does not grant rights to the unique financial 
strategies or mathematical models expressed herein for commercial reproduction or rebranding without explicit consent.

# Intrinsic-Value-Screener 📈
**AI-driven logic for Graham-Dodd fundamental analysis.**

This project bridges the gap between historical **Deep Value Investing** and modern **Agentic AI**. It automates the identification of "Margin of Safety" opportunities using the methodologies defined by Benjamin Graham and David Dodd.

---

## 🧠 Core Investment Logic: The "Net-Net" Formula
Most modern AI screeners focus on momentum. This logic focuses on **Asset Protection**. 

The primary filter is the **Net-Net Working Capital (NNWC)** model:

The engine calculates Net-Net Working Capital (NNWC) using proprietary risk-adjusted weightings based on asset liquidity. These coefficients are tuned to prioritize conservative valuations in volatile market conditions.
### 🛠️ Execution Strategy

1. **Data Acquisition:** AI agents parse SEC 10-K/10-Q filings for raw balance sheet data.
2. **Margin of Safety:** We only alert when the Market Cap is < $2/3$ of the calculated NNWC.
3. **Risk Mitigation:** Integrated checks for "Burn Rate" and "Dividend History" to ensure the company isn't just a value trap.

## 🚀 The AI Advantage
By utilizing **LLMs for financial data extraction**, this tool can read the *footnotes* of financial statements—where the real liabilities are often hidden—something standard technical screeners miss entirely.

---
*Status: Architecture Phase. Developing Python logic for automated data ingestion.* 
