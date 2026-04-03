Branch: simba/build-the-pilot-site-mapper-in-srcdocssite-surve
Title: Build the 'Pilot Site Mapper' in src/docs/site-survey-gen.js. [span_1...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Build the 'Pilot Site Mapper' in src/docs/site-survey-gen.js. [span_15](start_span)[span_16](start_span)This tool must generate a technical layout for a 1-km stretch of highway, detailing where sensors, edge nodes (Jetson Orins), and cabinets will be placed[span_15](end_span)[span_16](end_span). [span_17](start_span)constraints: Include cost-per-lane quantifications as required for NHAI negotiations[span_17](end_span). Output the report as a "Sovereign Infrastructure Prospectus."

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.