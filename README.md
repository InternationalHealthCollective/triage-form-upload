# Triage Form Upload

TJP clinic triage form v2: the triage lead photographs the paper form on a phone, the scanner reads the
checkboxes and bubbles (fixed geometry, no AI), the lead confirms, and the row is saved to the clinic tracking sheet
with labs chosen by the Triage Lab Protocol rules.

| | |
|---|---|
| Owning team | _fill in_ |
| Leads | _fill in_ |
| Status | Active |
| Stack | Google Apps Script (Sheets web app), Python and Node tools for the form and tests |
| Where it runs | _fill in_ |
| Non-code files | IHC Google Drive (link: _fill in_) |

> **This repository is public.** Anyone on the internet can read everything committed here, including old commits.

## Layout

```
triage-form-upload/
├── README.md        this file: what it is, how to run and deploy
├── HANDOFF.md       current status and next steps
├── src/             the code
├── docs/            design notes, protocols, sign-off records
├── examples/        synthetic sample data only
└── .github/
    └── pull_request_template.md
```

## How to run

_fill in_: setup steps, where the code is deployed, and how to deploy a new version.

## Rules

- **No real patient, applicant or staff data**, in code, examples, tests, screenshots or logs. Use invented records.
- **No secrets** (API keys, passwords, service-account files, sheet IDs that grant access). Keep them in a
  git-ignored `.env` or in script properties, and share them through the team's password manager or Drive.
- Work on a branch and open a pull request into `main`; someone else reviews before merging.
- Changes to clinical logic (triage rules, lab thresholds, patient-facing wording) need a clinical lead's sign-off,
  recorded in `docs/`.
- Update `HANDOFF.md` when you stop working on this or hand over your role.

New to Git? Start with the [Onboarding](https://github.com/InternationalHealthCollective/Onboarding) repository.
