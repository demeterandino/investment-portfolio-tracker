# User Story – Simulated Impact Before Rebalancing (US 3.3)

## Story
As an investor, I want to see the simulated impact so I know how my portfolio will change.


## Problem
Users hesitate to rebalance due to uncertainty about how trades will affect allocation, drift, and risk.  
A simulation preview is needed before committing changes.


## Business Value
- Increases user trust  
- Reduces errors  
- Boosts adoption of the rebalancing feature  


## Acceptance Criteria
Given the user's portfolio has drift
When the user opens the "Simulate impact" view
Then the system must calculate the new allocation state
And show a before/after comparison
And no portfolio changes must occur until the user confirms


## Scenarios
- Drift > 5% → simulation shows recommended trades  
- Drift < 1% → simulation indicates no significant change  
- User cancels → original state restored  
- User confirms → triggers real rebalancing workflow  


## Out of Scope
- Tax impact simulation  
- Brokerage execution modeling  


## Dependencies
- Drift calculation engine  
- Rebalancing logic  
- Portfolio snapshot module  


## Labels
`story` `auto-rebalancing` `high-value`
