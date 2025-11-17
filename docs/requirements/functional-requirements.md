# Functional Requirements Document (FRD)
## Investment Portfolio Tracker — Automation Features


## 1. Data Import & Categorization
### Requirements
- Users must be able to import portfolio data via:
  - CSV upload
  - API integrations (Yahoo Finance, broker export)
- The system shall auto-categorize assets by:
  - Asset class (ETF, Stock, Bond, Crypto)
  - Sector
  - Region
  - Risk level
- Users may manually override categories.


## 2. Portfolio Analytics
### Requirements
- The system shall calculate:
  - Current allocation %
  - Target allocation %
  - Deviation from target
  - Volatility (30/90 day)
  - Risk score (0–100)
- The dashboard must highlight:
  - Overweight assets
  - Underweight assets
  - High-risk exposures
  - Missing diversification areas


## 3. Smart Alerts Engine
### Requirements
- Alerts must be triggered when:
  - Allocation deviates beyond threshold
  - Price movements exceed X%
  - Volatility exceeds user-defined limits
  - Earnings reports or macro events occur
- Alerts must be:
  - Bundled by theme
  - Ranked by importance (High/Medium/Low)
  - Explainable (“Why this matters”)


## 4. Automation Engine — Rebalancing
### Requirements
- The system shall:
  - Detect deviations from target portfolio weights
  - Recommend rebalancing actions
  - Simulate impact (risk ↓, diversification ↑)
  - Suggest buy/sell proportions
- Users must approve actions manually.
- Rebalancing logic must align with:
  - User’s risk profile
  - Minimum transaction threshold
  - Market volatility filters


## 5. Monthly Automation Report
### Requirements
- The system shall generate:
  - Summary of alerts
  - Automation performance (“Stability Score”)
  - Portfolio allocation changes
  - Top deviations corrected
- Reports must be exportable as PDF.


## 6. User Profiles & Settings
### Requirements
- Users can adjust:
  - Risk tolerance
  - Alert filtering
  - Rebalancing thresholds
  - Supported asset types
- System must store settings securely.
