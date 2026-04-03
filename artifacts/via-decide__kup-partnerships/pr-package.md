Branch: simba/build-the-revenue-ledger-in-srcfinsettlement-eng
Title: Build the 'Revenue Ledger' in src/fin/settlement-engine.js. Automatic...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Build the 'Revenue Ledger' in src/fin/settlement-engine.js. Automatically calculate the "Economic Value Added" (EVA) for every confirmed anomaly.

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.