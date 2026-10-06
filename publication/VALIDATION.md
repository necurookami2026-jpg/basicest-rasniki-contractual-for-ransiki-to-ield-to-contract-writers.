# Lair of Lairs publication validation

*6 October 2026 · Current combined edition*

The final combined bootstrap passed and retained all immutable source bytes. Its receipt and command logs are stored locally under ignored `.publication-build/bootstrap/`; generated reading artifacts are under `publication/edition/`.

| Check | Observed outcome |
| --- | --- |
| Pinned sources | Four complete tracked-file snapshots, 254 source records, 9,342,556 bytes; every size and SHA-256 matched. |
| Current lab and publication tests | 33 Python tests passed, including tree membership, stable IDs, explicit parents, traversal bounds, source-preservation, malformed inputs and deterministic outputs. |
| Pinned contractual parent | 19 Python tests passed in its own temporary source copy. |
| Guardian | 14 Python tests passed against the retained source. |
| Rasnikism full bootstrap | 16 Python tests and 12 JavaScript suite files passed; quilt/program/publication outputs rebuilt in a temporary copy. |
| Ministry | Node smoke checks passed for mirrored HTML, local anchors, seven terms, search/reset and four rotating seeds. |
| Desktop JavaScript | Syntax check passed. |
| Output repeatability | All six named publication outputs rebuilt byte-for-byte; locked sources remained unchanged. |
| Browser reader | Network-disabled HTML and loopback-hosted reader passed nested navigation, root/parent returns, Markdown selection, inert binary metadata, seven chambers, search/reset and mobile width checks. |
| Ministry browser | Glossary filtering, empty/reset states and four-seed cycling passed. |
| Local desktop integration | Links to the new reader and ministry were visible; the session started normally. |
| Archive download | The complete local HTTP response matched the generated ZIP bytes. |

The lair index has 287 nodes: the collection, source/editorial containers, directories and leaves. Every pinned source file has a leaf. Six current editorial documents have their own lair. The reader contains 40 unique Markdown documents, deduplicated by source digest while retaining all references.

The cloud-managed Chromium policy blocked direct `file://` navigation. The self-contained HTML was instead loaded as document content with every network request disabled; its navigation and search passed. The same reader also passed through the local HTTP route. This record does not claim that the blocked direct-file launch was executed successfully.

Mobile validation initially found overflow in nested rows and long source headings. The generated layout was corrected and the final width check passed. The standalone reader and hosted reader produced no page errors in the final browser workflow.

These are named finite checks. They do not establish public application hosting, a native bootable OS, firmware execution, real finance, sovereign status, universal scientific correctness or freedom from all malware. Source publication and an environment snapshot remain separate actions.
