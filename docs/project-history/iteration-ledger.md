# Iteration Ledger

## Purpose and update rules

This ledger is the chronological, factual record of AtlasGate delivery. Every iteration must add or update an entry together with the relevant Build from Zero chapter. Entries must describe observed starting state, scoped changes, commands, validation, limitations, and the next expected prompt. Never invent commit, pull-request, test, or tool results.

## Reusable entry template

### `<iteration-prompt>` - `<title>`

- **Date:** `YYYY-MM-DD`
- **Objective:**
- **Starting state:**
- **Files created or modified:**
- **Commands executed:**
- **Validation results:**
- **Known limitations:**
- **Commit / pull request:** Not created unless explicitly recorded.
- **Next expected prompt:**

## I00-P01 - Repository governance bootstrap

- **Date:** 2026-08-05
- **Verified commit:** `f434ead2d5e950f6eeabc49cfabd0f9c9a3d2cff` - `chore: bootstrap repository governance` (commit date 2026-08-06). This is the root commit; `4fb4195` later normalized file endings.
- **Objective:** Establish minimum repository governance, agent guidance, documentation entry points, reconstruction records, and portfolio evidence framing before discovery or application development.
- **Starting state:** The repository had no commits or tracked files, was on `main`, and contained only the untracked private planning file `atlasgate_project_master_plan.md`. The `origin` remote was configured. The private plan was read as context and not changed.
- **Branch:** The prompt initially moved HEAD to `chore/iteration-00-governance-bootstrap`. Before the first commit, HEAD was reset to `main` to match the project workflow.
- **Files created or modified:** `.gitignore`, `.editorconfig`, `.gitattributes`, `AGENTS.md`, `README.md`, `docs/README.md`, `docs/build-from-zero/README.md`, `docs/build-from-zero/00-prerequisites.md`, `docs/project-history/iteration-ledger.md`, and `docs/portfolio/target-role-evidence-map.md`.
- **Commands executed:** Working-directory inspection; `git status --short --branch`; `git branch --show-current`; `git remote -v`; `rg --files`; private-plan read; `java --version`; `javac --version`; `git --version`; `docker --version`; `docker compose version`; `docker info`; `node --version`; `npm --version`; `codex --version`; `git switch -c chore/iteration-00-governance-bootstrap`; and the final validation commands recorded below.
- **Validation results:** Java/Javac, Git, Docker CLI/Engine, Compose, Node.js, and Codex CLI were available at the versions recorded in the prerequisites chapter. Final ignore, whitespace, status, content, and scope checks are recorded after file creation.
- **Final validation commands:**
  - `git check-ignore -v atlasgate_project_master_plan.md`: passed; the private plan is ignored by the anchored `.gitignore` rule.
  - `git diff --check`: passed with no whitespace errors reported.
  - `git status --short --branch`: confirmed the repository is on `main` with only the expected untracked governance files.
  - `git diff --cached --name-only`: returned no files; nothing was staged.
  - `git ls-files -- atlasgate_project_master_plan.md`: returned no result; the private plan is not tracked.
- **Known limitations:** The literal npm check was blocked by the local PowerShell execution policy. No application, build, container, CI, or architecture implementation exists. There is no commit or pull request.
- **Commit / pull request:** Not created.
- **Next expected prompt:** `I00-P02`, limited to discovery records and architecture decision framing without application implementation.

## I00-P02 - Discovery foundation and decision governance

- **Date:** 2026-08-06
- **Objective:** Establish the fictional business-discovery context, stakeholder model, engagement plan, uncertainty and risk records, terminology, and architecture-decision governance before simulated interviews or technical implementation.
- **Starting state:** The repository was on `main`, aligned with `origin/main`, and had no changes reported by `git status --short --branch`. The ignored private planning file existed, was read silently for context, and remained outside tracked content. The repository contained governance and documentation bootstrap artifacts only.
- **Files created or modified:** Created `docs/discovery/README.md`, `docs/discovery/01-company-profile.md`, `docs/discovery/02-stakeholder-map.md`, `docs/discovery/03-discovery-plan.md`, `docs/discovery/04-assumptions-and-open-questions.md`, `docs/discovery/05-glossary.md`, `docs/project-management/risk-register.md`, `docs/architecture/README.md`, `docs/architecture/decisions/README.md`, `docs/architecture/decisions/adr-template.md`, `docs/build-from-zero/01-repository-bootstrap.md`, and `docs/build-from-zero/02-discovery-artifacts.md`. Modified `docs/README.md`, `docs/build-from-zero/README.md`, this ledger, and `docs/portfolio/target-role-evidence-map.md`.
- **Commands executed:** `Get-Location`; reads of required guidance and existing documentation; silent private-plan read; `git status --short --branch`; `git branch --show-current`; `git log --oneline -5`; `git remote -v`; `git show -s`; `git check-ignore -v atlasgate_project_master_plan.md`; `rg --files`; directory inspection and creation; documentation patches; link, language-boundary, scope, whitespace, staging, tracking, and final status validations recorded below.
- **Validation results:** `git diff --check` passed. A repository-relative Markdown-link scan reported no broken links. The scope scan found no application source, build manifest, dependency manifest, container or Compose definition, CI workflow, infrastructure definition, API contract, database artifact, or diagram. Case-insensitive content scans found no prohibited employment-related topics and no claim that a planned interview or workshop had been completed. Portfolio claims were reviewed against existing files and remain limited to documentation and governance evidence. `git status --short --branch` confirmed `main` with only the expected documentation changes; `git branch --show-current` returned `main`; `git diff --cached --name-only` returned no files; `git check-ignore -v atlasgate_project_master_plan.md` resolved to the anchored `.gitignore` rule; `git ls-files -- atlasgate_project_master_plan.md` returned no match; and `git diff --name-only` listed only the four expected modified tracked documentation files (new files remain untracked until explicitly added in a future authorized operation).
- **Known limitations:** The scenario, participants, assumptions, risks, and planned activities are fictional. No simulated interview or workshop has occurred; no findings, hypotheses, requirements, architecture baseline, technology choices, ADR decisions, diagrams, application behavior, tests, build, infrastructure, deployment, security control, observability, or performance evidence exists.
- **Commit / pull request:** Not created; no files were staged or pushed.
- **Next expected prompt:** Conduct the first fictional simulated executive kickoff and business-context discovery. Capture attributed stakeholder statements and unresolved evidence without implementation, technology selection, or premature requirement approval.
