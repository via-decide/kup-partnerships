Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Create the 'National Rollout Blueprint' generator in src/docs/rollout-architect.js. [span_18](start_span)[span_19](start_span)This tool compiles the 'Reference Architecture' for extreme-climate AI, including edge-inference cost benchmarks and the 40% blowout prevention statistics.[span_18](end_span)[span_19](end_span) [span_20](start_span)[span_21](start_span)constraints: Ensure the output is formatted as a formal government prospectus, highlighting the successful pilot results from the NHAI 1-km site and Deendayal Port.[span_20](end_span)[span_21](end_span)

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