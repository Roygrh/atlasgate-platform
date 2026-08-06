# AtlasGate Agent Guidance

- Write every tracked artifact in English. Treat `atlasgate_project_master_plan.md` as private, untracked context: read it when relevant, but never modify, stage, commit, quote extensively, translate, or copy it into tracked files.
- Inspect the repository, Git status, applicable guidance, and affected files before modifying anything. Preserve user work and make small, scoped, reviewable changes without unrelated refactoring.
- Keep the product direction explicit: AtlasGate is an enterprise API platform with a control plane and a data plane. The future control plane is a modular monolith with hexagonal boundaries per module; the gateway runtime is component-oriented.
- Introduce patterns, abstractions, and dependencies only for concrete requirements. Prefer repository wrappers and pinned tooling over unnecessary global dependencies.
- Handle secrets and configuration security-first. Never commit credentials, disclose environment values, or embed sensitive defaults.
- Validate changes in proportion to risk with automated tests and negative-path checks where applicable. Compilation alone is insufficient.
- Every iteration must update the Build from Zero documentation and `docs/project-history/iteration-ledger.md`. Update documentation and diagrams whenever behavior or architecture changes; do not create speculative diagrams.
- Report commands run, results, validation coverage, and limitations truthfully.
- Do not commit, push, stage files, perform destructive operations or external writes, or materially expand scope without explicit instruction.
- Work on the current branch. Do not create, switch, rename, or delete branches unless explicitly instructed. The default project workflow uses `main`.
