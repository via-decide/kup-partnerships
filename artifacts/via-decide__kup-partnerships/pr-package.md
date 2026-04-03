Branch: simba/implement-the-b2b-anomaly-dashboard-in-srcwebinf
Title: Implement the 'B2B Anomaly Dashboard' in src/web/infra-alpha.js. Crea...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Implement the 'B2B Anomaly Dashboard' in src/web/infra-alpha.js. Create a real-time view that filters out the "Scenario 2" noise and only displays "Validated Anomalies" (High-probability blowout risks).

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.