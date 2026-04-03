Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Build the 'Pilot Site Mapper' in src/docs/site-survey-gen.js. [span_15](start_span)[span_16](start_span)This tool must generate a technical layout for a 1-km stretch of highway, detailing where sensors, edge nodes (Jetson Orins), and cabinets will be placed[span_15](end_span)[span_16](end_span). [span_17](start_span)constraints: Include cost-per-lane quantifications as required for NHAI negotiations[span_17](end_span). Output the report as a "Sovereign Infrastructure Prospectus."

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