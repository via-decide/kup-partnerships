Branch: simba/implement-the-kutch-discovery-scraper-in-srcdata
Title: Implement the 'Kutch-Discovery Scraper' in src/data/local-discovery.j...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Implement the 'Kutch-Discovery Scraper' in src/data/local-discovery.js. Populate the ONDC mock-registry with the coordinates and service profiles of the first 50 tyre-repair stations along the NH-41 (Kutch/Anjar stretch).

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.