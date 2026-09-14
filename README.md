# Auto-Approve Live Test

Small repository for testing Enso Auto-Approve end-to-end.

## Intended test
1. Analyze/review this repository with Enso.
2. Generate a remediation for the debug `console.log`.
3. Confirm the remediation has a real unified diff.
4. Process it through Auto-Approve.
5. Verify a commit SHA is created and pushed.
6. Verify GitHub Actions runs successfully for that SHA.
7. Verify Auto-Approve moves past the CI waiting state.

Do not manually create the remediation commit; let Enso create it.
