# Project Structure

```
.
├── .github/              # GitHub configuration (templates, workflows)
│   └── ISSUE_TEMPLATE/   # Issue templates
│       ├── config.yml    # Template chooser config (blank issues disabled)
│       └── story.yml     # User story issue template
├── .kiro/
│   ├── hooks/            # Agent hooks for automated actions
│   ├── specs/            # Feature specs
│   └── steering/         # AI assistant steering rules
├── .gitignore
├── GITHUB.md             # Documentation for shared GitHub templates & workflows
└── README.md
```

## Directory Conventions

- `.github/ISSUE_TEMPLATE/` — Issue templates for the organization
- `.github/workflows/` — Reusable CI/CD workflow files go here (not yet created)
- `.github/` root — PR templates and other GitHub config (e.g., `CODEOWNERS`, `FUNDING.yml`)

## Notes

- `GITHUB.md` at the repo root documents the available GitHub templates and workflows.
- This repo is meant to be referenced by other HersRD repositories, so changes here can have organization-wide impact.
