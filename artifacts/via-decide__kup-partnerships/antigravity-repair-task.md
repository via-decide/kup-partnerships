Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Build the 'Pilot Proposal' generator in src/docs/nhai-brief-gen.js. [span_20](start_span)[span_21](start_span)This module must pull real accuracy and cost-per-lane metrics from the kup-ai-stack and format them into a formal NHAI technical brief[span_20](end_span)[span_21](end_span). [span_22](start_span)constraints: Specifically highlight the 40% reduction in blowout risk through under-inflation detection[span_22](end_span). [span_23](start_span)Ensure the document includes the "Reference Architecture" for extreme climates as specified in Research Output 3[span_23](end_span).

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