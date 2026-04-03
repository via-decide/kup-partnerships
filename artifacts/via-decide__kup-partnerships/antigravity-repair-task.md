Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Build the 'Partner Case Study' generator in src/docs/nvidia-case-study.js. This module must pull hardware-in-the-loop (HITL) metrics-specifically power efficiency, GPU utilization, and accuracy under 48°C heat-and format them for an NVIDIA DeepStream/Jetson case study.

RULES
1. Audit touched files first and identify regressions.
2. Preserve architecture and naming conventions.
3. Make minimal repairs only; do not expand scope.
4. Re-run checks and provide concise root-cause notes.
5. Return complete contents for changed files only.

SOP: REPAIR PROTOCOL (MANDATORY)
1. Strict Fix Only: Do not use repair mode to expand scope or add features.
2. Regression Check: Audit why previous attempt failed before proposing a fix.
3. Minimal Footprint: Only return contents for the actual repaired files.

REPO CONTEXT
- README snippet:
# kup-partnerships
- AGENTS snippet:
not found
- package.json snippet:
not found