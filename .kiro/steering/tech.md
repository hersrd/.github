# Tech Stack

## Primary Technologies

- **GitHub Actions**: CI/CD workflows defined in YAML
- **Python**: The `.gitignore` is Python-oriented, suggesting workflows or scripts may use Python tooling

## Key Tools & Ecosystem

- **GitHub reusable workflows**: Workflows in `.github/workflows/` can be called from other repos
- **GitHub templates**: Issue and PR templates in `.github/` directories

## Common Commands

This is primarily a configuration/template repository. There are no build or test commands at this time. If Python scripts are added, expect:

- Linting: `ruff check .`
- Formatting: `ruff format .`
- Type checking: `mypy .`

## Conventions

- GitHub Actions workflows use YAML syntax
- Follow GitHub's documented schema for reusable workflows and templates
- Pin action versions to specific SHAs or tags for security (e.g., `actions/checkout@v4`, not `actions/checkout@main`)
