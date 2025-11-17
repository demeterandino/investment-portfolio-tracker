# User Story – Alerts Grouped by Importance (US 2.1)

## Story
As a user, I want alerts grouped by importance so I’m not overwhelmed.


## Problem
Users receive many alerts from drift checks, market volatility, and portfolio events.  
Without grouping, the alert center becomes cluttered and difficult to prioritize.


## Business Value
- Reduced cognitive load  
- Clearer alert prioritization  
- Improved usability and engagement  


## Acceptance Criteria 
Given alerts are generated
When multiple alerts occur within the same theme
Then they must be grouped
And prioritized by importance.


## Scenarios
- User receives >10 alerts → collapsed view  
- New Critical alert → moves to the top immediately  
- All alerts are Info → single group  
- Collapsed/expanded view persists on refresh  


## Out of Scope
- AI-based alert prioritization  
- Automatic dismissal of stale alerts  


## Dependencies
- Alert engine  
- UI alert components  


## Labels
`story` `alerts` `ui-ux` `medium-priority`
