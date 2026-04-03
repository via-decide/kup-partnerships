Branch: simba/build-the-partner-case-study-generator-in-srcdoc
Title: Build the 'Partner Case Study' generator in src/docs/nvidia-case-stud...

## Summary
- Repo orchestration task for via-decide/kup-partnerships
- Goal: Build the 'Partner Case Study' generator in src/docs/nvidia-case-study.js. This module must pull hardware-in-the-loop (HITL) metrics-specifically power efficiency, GPU utilization, and accuracy under 48°C heat-and format them for an NVIDIA DeepStream/Jetson case study.

## Testing Checklist
- [ ] Run unit/integration tests
- [ ] Validate command flow
- [ ] Validate generated artifact files

## Risks
- Prompt quality depends on repository metadata completeness.
- GitHub API limits/token scope can block deep inspection.

## Rollback
- Revert branch and remove generated artifact files if workflow output is invalid.