# 6. Retrieval Determinism

Retrieval determinism means: given the same input anchor, constraints, and graph snapshot, compliant agents return the same bounded set.

## 6.1 Deterministic pipeline
1) Mirror: resolve anchor → normalize text → hash
2) Water: fetch link neighborhood under fixed policies (depth, link types, review filters)
3) Fire: generate interpretation only within constraint profile

## 6.2 Determinism controls
- pinned graph snapshot version
- pinned schema version
- explicit filtering rules (e.g., “review_status=approved only”)
- fixed depth/limit parameters