Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Create the 'Blowout ROI Calculator' in src/docs/roi-calculator.js. [span_17](start_span)[span_18](start_span)This tool must use real-time TPM data to calculate the "Blowouts Prevented" and "Cost-Per-Lane" savings for NHAI[span_17](end_span)[span_18](end_span). [span_19](start_span)constraints: Specifically highlight the 40% safety improvement metric from the Strategic Framework[span_19](end_span). [span_20](start_span)[span_21](start_span)Format the report as an "Executive Summary for NHAI/Gujarat State"[span_20](end_span)[span_21](end_span).

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