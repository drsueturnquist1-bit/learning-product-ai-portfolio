# Testing and Evaluation Framework

## 1. Define success

Before testing, define the intended user, task, correct or acceptable behavior, failure conditions, and evidence of usefulness.

## 2. Build a representative test set

Include:

- Typical educator requests
- Incomplete information
- Conflicting evidence
- Requests outside the intended scope
- Privacy-sensitive input
- Biased or deficit-framed input
- Accessibility concerns
- Attempts to force an unsupported conclusion

## 3. Record results

For every test, document:

| Field | Description |
|---|---|
| Test ID | Stable identifier |
| Date and version | Product state tested |
| Input | Sanitized test input |
| Expected behavior | Acceptance criteria |
| Actual behavior | Observable output or action |
| Result | Pass, partial, or fail |
| Risk | User or system impact |
| Decision | Keep, revise, block, or investigate |
| Retest | Evidence after revision |

## 4. Pilot with representative users

Observe task completion and collect usefulness, clarity, trust, accuracy, accessibility, and confidence feedback. Separate satisfaction from actual performance.

## 5. Revise and retest

Correct the underlying prompt, knowledge source, interface, workflow, or scope statement. Retest the original failure plus related cases before release.

## 6. Monitor after release

Track reported errors, abandoned tasks, recurring questions, inaccessible interactions, stale content, and changes in source material or policy.

