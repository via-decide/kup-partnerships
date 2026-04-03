Branch: simba/implement-the-ondc-stress-test-in-srctestcommerc
Title: Implement the 'ONDC Stress-Test' in src/test/commerce-burst.js. Gener...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Implement the 'ONDC Stress-Test' in src/test/commerce-burst.js. Generate 10 simultaneous "Critical Under-Inflation" alerts and verify that the ViaDecide engine can find 10 unique, geolocated repair services within 5 seconds.

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.