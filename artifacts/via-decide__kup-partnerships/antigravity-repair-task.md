Repair mode for repository via-decide/kup-partnerships.

TARGET
Validate and repair only the files touched by the previous implementation.

TASK
Implement the 'Partner Validation Portal' in src/integration/partner-portal.js. [span_2](start_span)[span_3](start_span)Create a secure, read-only interface for NVIDIA and Kistler to review 'Scenario 2' recovery logs and HITL (Hardware-In-The-Loop) performance data.[span_2](end_span)[span_3](end_span) [span_4](start_span)[span_5](start_span)constraints: The portal must show real-time temperature drift correlations ($20-48^{\circ}C$) to prove the robustness of the Vora model on the Jetson Orin NX hardware.[span_4](end_span)[span_5](end_span)

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