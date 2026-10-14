# AI-use and independent verification log

## AI assistance
- Tool: ChatGPT.
- Task: project structure, code scaffolding, method descriptions, report/checklist templates.
- Suggestions accepted: [state which code/design suggestions you used].
- Suggestions rejected or changed: [state any, or write “none” only if accurate].
- Your decisions: [justify meaningful-effect threshold, sample-size grid, and counterexample].

## Independent verification — complete only after performing it
| Quantity/claim | Independent method | Notebook value | Independent value | Agreement/tolerance |
|---|---|---|---|---|
| Mean difference | Recalculate `np.mean(b)-np.mean(a)` | [fill] | [fill] | [fill] |
| CI | Check interval calculation or compare bootstrap/Welch intervals | [fill] | [fill] | [explain expected differences] |
| Power | Recompute rejections / repetitions from CSV | [fill] | [fill] | [fill] |
| Counterexample | Compare rejection and coverage rates across distributions | [fill] | [fill] | [interpret] |

Do not mark a check complete until you personally run it and inspect the evidence. Retain any failed runs or surprising results.

## Execution record for this prepared package
The notebook was executed top-to-bottom in the preparation environment and produced the CSV and figure files included in this package. This is not a substitute for the student's independent verification or for checking that the results reproduce in the student's own environment. The independent verification table above remains intentionally incomplete until the student performs those checks.
