# 1. Canonical Anchoring

## 1.1 Definition
Canonical Anchoring is the practice of identifying a stable “anchor object” for any interpretive action. An anchor object is a machine-resolvable pointer to a primary text segment and its minimal metadata.

MWF Rule: **No interpretation occurs without an anchor.**

## 1.2 Anchor Object (minimal fields)
An anchor MUST include:
- `work_id` (canonical work identifier)
- `canon_family` (e.g., Hebrew Bible, NT, Ethiopic)
- `ref` (reference string or structured ref)
- `text_hash` (hash of the exact quoted/normalized text segment)
- `source_uri` (where it came from, if available)
- `license` / `usage_rights` (if applicable)

## 1.3 Mirror Phase output
Mirror outputs only:
- the anchor
- lexical notes (tokens, lemmas, transliteration where applicable)
- direct quotations limited by licensing rules
- *no* theological conclusion

Mirror is “indexing,” not preaching.