Branch: simba/create-the-national-rollout-blueprint-generator-
Title: Create the 'National Rollout Blueprint' generator in src/docs/rollout...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Create the 'National Rollout Blueprint' generator in src/docs/rollout-architect.js. [span_18](start_span)[span_19](start_span)This tool compiles the 'Reference Architecture' for extreme-climate AI, including edge-inference cost benchmarks and the 40% blowout prevention statistics.[span_18](end_span)[span_19](end_span) [span_20](start_span)[span_21](start_span)constraints: Ensure the output is formatted as a formal government prospectus, highlighting the successful pilot results from the NHAI 1-km site and Deendayal Port.[span_20](end_span)[span_21](end_span)

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.