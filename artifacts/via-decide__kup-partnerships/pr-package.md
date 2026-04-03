Branch: simba/build-the-integration-specialist-agent-template-
Title: Build 'The Integration Specialist' Agent Template in src/templates/in...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Build 'The Integration Specialist' Agent Template in src/templates/integration-specialist.json. Configure the prompt to act as the liaison API for NHAI highway pilots and Deendayal Port data ingestion.

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.