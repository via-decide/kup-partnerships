Branch: simba/build-the-pilot-proposal-generator-in-srcdocsnha
Title: Build the 'Pilot Proposal' generator in src/docs/nhai-brief-gen.js. [...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Build the 'Pilot Proposal' generator in src/docs/nhai-brief-gen.js. [span_20](start_span)[span_21](start_span)This module must pull real accuracy and cost-per-lane metrics from the kup-ai-stack and format them into a formal NHAI technical brief[span_20](end_span)[span_21](end_span). [span_22](start_span)constraints: Specifically highlight the 40% reduction in blowout risk through under-inflation detection[span_22](end_span). [span_23](start_span)Ensure the document includes the "Reference Architecture" for extreme climates as specified in Research Output 3[span_23](end_span).

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.