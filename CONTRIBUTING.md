# Contributing to Campus Notes

Keep this repo easy to review by following a few small conventions.

## Branches
- Work on a branch, never directly on `main`.
- Name feature branches `feature/<your-name>-<short-change>`, e.g. `feature/vedant-deadlines`.

## Commits (Conventional Commits)
Start the subject with one of these types, keep it under ~70 characters, and
write the *why* in the body when it is not obvious:

| Type | Use for |
| --- | --- |
| `feat:` | a new note, file or capability |
| `fix:` | correcting wrong or missing content |
| `docs:` | README, notes or other documentation |
| `refactor:` | restructuring without changing behaviour |
| `chore:` | housekeeping (cleanup, tooling, metadata) |

Examples:
```
docs: add class schedule for semester 3
fix: correct the VCS due-date in the notes file
```

## Pull requests
- One logical change per PR.
- Title: same conventional prefix as the main commit.
- Description: what changed, why, and a link to the issue it fixes.
- Self-review: re-read the diff before asking for a review.

## Pull-request review checklist
Before requesting review, tick each item:
- [ ] One logical change per PR
- [ ] Conventional-commit messages (feat/fix/docs/refactor/chore)
- [ ] Self-reviewed the diff
- [ ] Linked the related issue
- [ ] Tests (if any) pass
