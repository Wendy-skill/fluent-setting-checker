# Optional v3 Research-Group Interface

Use only for a real cross-Skill handoff. Standalone use remains the default.

## Scope and routing

- **Own:** Compare manuscript-reported solver settings against supplied Fluent setup, journals and logs.
- **Do not replace:** Claiming an actual solver setting was checked without the underlying file.
- **Chinese triggers:** Fluent 设置核查、求解器参数对照、仿真设置一致性.
- **English triggers:** Fluent settings cross-check, solver manuscript consistency.
- **Do not trigger:** unrelated writing polish, generic research planning, or an all-Skill audit when only a narrow task was requested.
- **Optional recipients:** ai-quality-inspector for document-level contradictions; simulation-paper-auditor for numerical method credibility. Route only if available and useful; never claim a named Skill was run merely because it is mentioned.

## Handoff schema

Use `ID | owner | document/version/location | issue | located evidence | source status | assessment | local consequence | proposed action | author decision | workflow state`.

Source status: `Reported / Documented / Independently checked / Not available`. Assessment: `Confirmed / Reasoned inference / Unverified` (specify what was verified). Workflow state: `Open / Waiting for evidence / Awaiting author / Resolved / Recheck needed`. Scientific reviewer **Severity** and inspector **Impact** are distinct; do not force a shared score.

## Ledger and loops

When authorised and helpful, reuse `Claim ID, Data ID, figure/table, units, case conditions, baseline, dataset/script version, document version, evidence status and linked issue ID`. It is not automatically shared or saved. One issue owner; another specialist handles only a separate question. Default loop: literature → approved execution → scientific review → editing → final QA; send changed evidence to the responsible member and rerun only affected checks. No invented delegation, calculations, sources or persistent storage. Author approval is required for meaning-changing edits or new execution.
