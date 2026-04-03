Branch: simba/implement-the-partner-validation-portal-in-srcin
Title: Implement the 'Partner Validation Portal' in src/integration/partner-...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Implement the 'Partner Validation Portal' in src/integration/partner-portal.js. [span_2](start_span)[span_3](start_span)Create a secure, read-only interface for NVIDIA and Kistler to review 'Scenario 2' recovery logs and HITL (Hardware-In-The-Loop) performance data.[span_2](end_span)[span_3](end_span) [span_4](start_span)[span_5](start_span)constraints: The portal must show real-time temperature drift correlations ($20-48^{\circ}C$) to prove the robustness of the Vora model on the Jetson Orin NX hardware.[span_4](end_span)[span_5](end_span)

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.