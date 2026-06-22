# Roadmap

This roadmap starts with governance only. Evaluation harness content starts
after Milestone 0 is complete and validation exists.

## Milestone 0: Project Governance

Goal: establish a small, reviewable operating model for the evaluation harness
repository.

### Issues

1. [#1 Create evaluation harness governance documentation](https://github.com/Shoko-official/llm-eval-harness/issues/1)
2. [#2 Add issue and PR templates](https://github.com/Shoko-official/llm-eval-harness/issues/2)
3. [#3 Add minimal validation, CI, and folder structure](https://github.com/Shoko-official/llm-eval-harness/issues/3)

### Execution Order

1. Complete issue #1 before templates or validation.
2. Complete issue #2 before content changes.
3. Complete issue #3 before evaluation content.

No evaluation implementation should be added during Milestone 0.

## Acceptance Criteria

Milestone 0 is complete when:

* repository role is documented;
* roadmap exists;
* contribution and review rules exist;
* issue and PR templates exist;
* minimal validation commands exist;
* minimal CI exists;
* initial folders exist;
* no metrics, datasets, or benchmark code has been added.

## Later Milestones

Expected sequence:

1. Define a minimal evaluation harness skeleton.
2. Define neutral metric placeholders.
3. Define dataset placeholder policy.
4. Add validation for evaluation files.
5. Add real metric code only after minimal datasets exist.

Any change to metrics, datasets, evaluation schemas, or figures must happen in a
dedicated issue.
