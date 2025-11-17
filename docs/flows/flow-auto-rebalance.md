# Flow: Automated Rebalancing Process

1. User imports or syncs portfolio
2. System calculates current allocation %
3. System retrieves target allocation (based on risk profile)
4. Check deviation vs. threshold
5. If drift < threshold → no action
6. If drift > threshold:
    - Calculate recommended trades
    - Simulate impact:
        - New allocation %
        - Risk delta
        - Diversification change
7. Generate Rebalance Suggestion Card
8. User chooses:
    - Approve
    - Edit
    - Snooze
9. System logs action + updates dashboard
