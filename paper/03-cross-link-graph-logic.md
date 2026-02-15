# 3. Cross-Link Graph Logic

## 3.1 Why a graph
A concordance becomes agent-ready when links are explicit, typed, and auditable.

## 3.2 Link types (examples)
- lexical: shared lemma/root
- thematic: shared motif (tagged)
- citation: explicit quotation or reference
- narrative: sequence continuity
- doctrinal: *only if labeled as interpretive and constrained*

## 3.3 Water Phase outputs
Water outputs a bounded link set:
- each link includes `from_anchor`, `to_anchor`, `link_type`, `evidence`, `confidence`, `review_status`
- links can be proposed by agents but must be reviewable by humans/maintainers

## 3.4 Anti-hallucination requirement
No link without:
- an anchor on both ends
- evidence field (quote, scholarly reference, or defined rule)