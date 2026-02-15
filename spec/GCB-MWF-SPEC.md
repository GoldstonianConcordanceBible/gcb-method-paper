# GCB-MWF-SPEC

## Purpose
Define the MWF framework as an agent-compatible concordance operating system.

## Phases
### Mirror (Anchor)
Inputs: work_id, canon_family, ref, text segment
Outputs: Anchor Object + lexical notes only

### Water (Graph)
Inputs: Anchor Object + link policies
Outputs: typed cross-links + evidence

### Fire (Interpretation)
Inputs: Anchor Object + Water neighborhood + constraints
Outputs: labeled interpretations bounded by safety guardrails

## Non-negotiables
- No anchor, no output
- No link without evidence + two anchors
- No Fire without explicit constraint profile