# 01 - Repository Bootstrap

## Purpose

This chapter reconstructs the completed repository governance baseline from committed files and observable Git state. It does not require a particular editor or agent tool.

## Prerequisites

Use Git in a working copy of `atlasgate-platform` and review [00 - Prerequisites](00-prerequisites.md). Work on `main` unless a later documented workflow explicitly changes that rule.

## Reconstruction

1. Check out the repository at or after root commit `f434ead2d5e950f6eeabc49cfabd0f9c9a3d2cff` (`chore: bootstrap repository governance`). Commit `4fb4195` subsequently normalizes file endings.
2. Read root [README](../../README.md), [agent guidance](../../AGENTS.md), and the [documentation index](../README.md).
3. Verify `.editorconfig` and `.gitattributes` define the repository text conventions.
4. Verify `.gitignore` contains the anchored rule for the private root file `atlasgate_project_master_plan.md`. The private file is local context and is not needed to reconstruct tracked governance.
5. Review the [iteration ledger](../project-history/iteration-ledger.md) and [portfolio evidence map](../portfolio/target-role-evidence-map.md) for factual delivery and evidence rules.

## Validation

Run from the repository root:

```powershell
git branch --show-current
git status --short --branch
git check-ignore -v atlasgate_project_master_plan.md
git ls-files -- atlasgate_project_master_plan.md
git diff --cached --name-only
```

Expected observations are branch `main`, no staged files, and no tracked match for the private plan. `git check-ignore` reports the anchored ignore rule when the private file exists. A clean checkout need not contain that private file.

## Limitations

This baseline provides governance and documentation structure only. It does not reconstruct application, build, runtime, test, infrastructure, deployment, or architecture behavior.
