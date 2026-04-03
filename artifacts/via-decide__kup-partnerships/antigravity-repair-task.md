Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Implement the 'Daxini Storefront API' in src/api/market-gate.js. Create a metered access point for the 'KUTCH-TIRE-ANOMALY-1M' dataset.

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