# Acceptance Criteria (Gherkin Format)

---

### AC for US 1.2 — Auto Categorization
Given I imported my portfolio  
When the system processes my assets  
Then each asset must receive a category  
And low-confidence items must be flagged  
And high-confidence items applied automatically.


### AC for US 2.1 — Allocation Display
Given I am on the dashboard  
When my portfolio loads  
Then I must see current vs. target allocation  
And deviations must be highlighted.


### AC for US 3.1 — Alert Grouping
Given alerts are generated  
When multiple alerts occur within the same theme  
Then they must be grouped  
And prioritized by importance.


### AC for US 4.2 — Rebalance Suggestion
Given my portfolio is out of balance  
When rebalancing logic runs  
Then I must receive trade suggestions  
And each suggestion must include explanation  
And I must be able to edit or approve.


### AC for US 5.1 — Monthly Report
Given the end of the month  
When the system generates the report  
Then I must see a summary of alerts  
And a summary of rebalancing actions  
And my portfolio stability score  
And month-over-month changes.
