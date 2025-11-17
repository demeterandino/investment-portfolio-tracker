# User Story – Auto Categorization of Assets (US 1.2)

## Story
As a user, I want the system to auto-categorize my assets so that I don’t waste time classifying them manually.


## Problem
Users currently need to manually assign categories such as ETF, stock, bond, or crypto.  
This is slow, error-prone, and causes incorrect portfolio analytics downstream.


## Business Value
- Faster onboarding  
- Higher data accuracy  
- Enables correct allocation, drift, and dashboard insights  


## Acceptance Criteria 
Given an asset is imported into the portfolio
When the system reads its metadata
Then the asset must be automatically assigned a category
And if the asset type cannot be determined
Then it must be labeled as "Uncategorized"


## Scenarios
- Known asset → correct category applied
- Unknown ticker → "Uncategorized"
- Manual override persists after re-import
- Re-importing does not overwrite overrides


## Out of Scope
- AI-based categorization  
- Multi-category assets  


## Dependencies
- Asset metadata API  
- Portfolio import module  


## Labels
`story` `asset-categorization` `medium-priority`
