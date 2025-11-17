# Product Requirement Document: Automated Asset Categorization Feature
### Investment Portfolio Tracker


## 1. Summary
Automatically categorize all imported assets by asset class, region, sector, and risk group using rule-based mapping enriched with machine learning for ambiguous assets.


## 2. Goals
- Reduce manual cleanup of imported portfolios
- Improve accuracy of dashboard analytics
- Enable reliable automation and alerting


## 3. Non-Goals
- Predict long-term performance  
- Replace user’s manual overrides  


## 4. Problem Statement
Users spend significant time assigning asset categories manually after importing portfolio data. Inaccurate classification leads to broken analytics and bad alerts.


## 5. Requirements

### Functional
- Auto-detect category via:
  - Ticker lookup
  - ETF composition detection
  - Region & sector mapping
  - Risk model scoring
- Confidence scoring:
  - High confidence → auto-apply
  - Low confidence → flag for review
- Users can override category.

### Non-Functional
- Classification must complete in <2 seconds.
- Accuracy target: 90%+.


## 6. KPIs
- Auto-categorization success rate
- Manual overrides ratio
- Time saved per import
