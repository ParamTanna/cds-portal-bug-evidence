# CDS Portal: reproduction screenshots

Screenshots taken while reproducing issues reported in the CS202 course repository
`iitgn-cs202-2026/cds-portal-test`, so they can be linked from issue comments.

Everything here was captured against a local stack
(`docker compose --profile e2e up e2e-web`) on `main` @ `2b1a043`, using only the
synthetic `example.edu` seed. No real student data appears in any image.

| File | Shows |
|---|---|
| `screenshots/879-admin-users-api.png` | Admin Users: active users carry "This user is already inactive." with `allowed: true` |
| `screenshots/908-discipline-ui.png` | Discipline roster listing the administrator account as a student |
| `screenshots/906-removed-outcome-tags.png` | Compliance outcome tags stored on removed memberships |
| `screenshots/906-approvals-ui.png` | The same removed rows in the Approvals screen |
| `screenshots/849-companies-api.png` | The company left inactive |
| `screenshots/849-external-api.png` | Its external offer, still editable |
| `screenshots/852-cancelled-job-api.png` | The cancelled job whose application stayed editable |
