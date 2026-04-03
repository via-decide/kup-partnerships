Branch: simba/build-the-kistler-hardware-bridge-in-srcintegrat
Title: Build the 'Kistler Hardware Bridge' in src/integration/kistler-valida...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Build the 'Kistler Hardware Bridge' in src/integration/kistler-validator.js. Develop a calibration service that compares raw data from physical Kistler sensors against the Digital Twin's ground truth.

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.