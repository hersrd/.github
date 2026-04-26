# Project Structure

```
.
├── .github/              # GitHub configuration (templates, workflows)
│   ├── workflows/        # Reusable GitHub Actions workflows (YAML)
│   ├── ISSUE_TEMPLATE/   # Issue templates
│   └── PULL_REQUEST_TEMPLATE.md  # PR template
├── .kiro/
│   └── steering/         # AI assistant steering rules
├── .gitignore
└── README.md
```

## Directory Conventions

- `.github/workflows/` — All reusable CI/CD workflow files go here
- `.github/ISSUE_TEMPLATE/` — Issue templates for the organization
- `.github/` root — PR templates and other GitHub config (e.g., `CODEOWNERS`, `FUNDING.yml`)

## Notes

- The `.github/` directory is currently empty. As templates and workflows are added, they should follow the standard GitHub directory layout shown above.
- This repo is meant to be referenced by other HersRD repositories, so changes here can have organization-wide impact.
