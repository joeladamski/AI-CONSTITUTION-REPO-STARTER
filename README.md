# AI-CONSTITUTION-REPO-STARTER

Governance-first repository starter for building AI systems, automations, agents, and platform integrations under the AI Constitution Framework.

## Core Doctrine Source
Canonical source documents are stored in:

- `docs/source-framework/`

These files are preserved as the doctrine layer and should be referenced when creating governance or architecture decisions.

## Starter Structure

```text
.ai-constitution/
.github/
docs/source-framework/
templates/
README.md
```

## Governance-First Workflow
1. Start from doctrine in `docs/source-framework/`.
2. Apply controls in `.ai-constitution/`.
3. Use templates in `templates/` to keep changes auditable and reviewable.
4. Enforce governance checks in pull requests via `.github/PULL_REQUEST_TEMPLATE.md`.

## Core Thesis
AI does not become trustworthy because it is powerful.
AI becomes trustworthy when it is governed.

## Using This Template

1. Click **Use this template** on GitHub to create a new repository.
2. In your new repository, keep `docs/source-framework/` as canonical doctrine (source reference), and operationalize project-specific controls in `.ai-constitution/`.
3. Replace `TBD` owners in `.ai-constitution/CHANGE_AUTHORITY.md` before any production use.
4. Use artifacts in `templates/` to seed decision logs, governance checklists, and review records.
5. Keep pull requests governance-mapped with `.github/PULL_REQUEST_TEMPLATE.md` and ensure `.github/workflows/governance-check.yml` passes.
