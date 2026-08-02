# Common Agent Operating Rules

## Core Principle

Do not rely on self-reporting. Use files, verified sources, and generated artifacts as evidence. 본문의 사실 주장은 확인된 출처로 뒷받침한다.

## Work Cycle

1. Read `AGENTS.md`, `CODEX.md`, and `harness.md` when the task touches project setup or workflow.
2. Read `강의계획서.md` (정본) for chapter scope; read `.ai/context.md`, `.ai/todo.md`, `.ai/gotchas.md` when the task spans more than a local edit.
3. For a chapter: plan (`schema/chap{N}.md`) → sources (`content/research/ch{N}-sources.md`) → draft (`docs/ch{N}.md`) → cross-check.
4. Modify only the requested scope.
5. Update memory files only when there is real new state.
6. Report changed files, source coverage, and remaining risks.

## Completion Criteria

- Requested change is implemented.
- Every number, indicator score, ministry name, and legal citation in the draft maps to a verified entry in `content/research/ch{N}-sources.md`.
- Unverified values are marked "확인 필요", not asserted.
- Any skipped verification is explicitly reported.
