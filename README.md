# Data Science Campus Project Template

This is a template repository for creating new projects in the Data Science Campus. When you create a new repository from this template, it will automatically generate placeholder content for key governance and project files.

## ONS GitHub Policy

All repositories in the ONS GitHub organisation must comply with the [ONS GitHub Usage Policy](https://github.com/ONSdigital/software-engineer-community/blob/master/Software%20Engineering%20Principles_Policies_Guidelines_Templates_Plans%20and%20more/Software%20Engineering%20Policies/GitHub%20Usage%20Policy.pdf). Key principles:

- **Repositories should be public by default**, unless there is a specific reason for them to be private or internal.
- **LICENSE is required** for all public repositories. This template includes an MIT License by default; customise it as appropriate for your project.
- **CODEOWNERS is required** by ONS organisational policy. This should point to a team (preferably), or an individual if this is a personal project or experimental repository.
- **PIRR (Private/Internal Repository Reasoning Record) is required** for any repository with private or internal visibility. This documents why the repository cannot be public and includes assessments of sensitivity, access control needs, security, and compliance considerations.

## Using This Template

To create a new project from this template:

1. Click the **Use this template** button on GitHub
2. Choose a name and owner for your new repository
3. Set the repository visibility to **Public** (unless there's a documented reason in PIRR to make it private/internal)
4. The bootstrap workflow will automatically:
   - Generate a `README.md` with project structure guidance
   - Create placeholder files for `CODEOWNERS` and `PIRR.md`
   - Remove the bootstrap workflow itself

You can then customize these placeholder files for your specific project and update the repository visibility and ownership as needed.


## Template Contents

This template includes:

- **README.md** — Starter template with sections for project description, installation, usage, and workflows
- **CONTRIBUTING.md** — Guidelines indicating unsolicited PRs are not accepted
- **CODE_OF_CONDUCT.md** — Community standards for respectful interaction
- **SECURITY.md** — Responsible vulnerability disclosure guidelines
- **CODEOWNERS** — Placeholder for project ownership configuration
- **PIRR.md** — Private/Internal Repository Reasoning Record template
- **Pre-commit hooks** — Security-focused checks for common issues (passwords, API keys, large files, merge conflicts)
- **Project structure** — Standard directories for `data/`, `docs/`, `outputs/`, `src/`, and `tests/`

## Contributing to the Template

We do not accept unsolicited pull requests to this template. If you have suggestions or feedback, please open an issue.

For information on reporting security issues, see [SECURITY.md](SECURITY.md).

