Branch: simba/implement-the-service-intent-gateway-in-srcbridg
Title: Implement the 'Service Intent Gateway' in src/bridge/ondc-booking.js....

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Implement the 'Service Intent Gateway' in src/bridge/ondc-booking.js. When the 'Hysteresis Machine' confirms a CRITICAL anomaly, generate a signed ONDC "Request for Quote" (RFQ) for the 3 nearest tyre repair facilities in Anjar/Kutch.

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.