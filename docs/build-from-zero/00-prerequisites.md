# 00 - Prerequisites

Verified on 2026-08-05 in the local Windows/PowerShell environment. This page records availability, not future technology selection.

## Required now

| Tool | Verified result | Purpose |
| --- | --- | --- |
| Git | `2.47.1.windows.1` | Repository and branch operations |
| Codex CLI | `0.146.1` | Local agent-assisted repository work |

## Optional and verified

| Tool | Verified result | Current status |
| --- | --- | --- |
| Java runtime | OpenJDK Temurin `21.0.10` LTS | Available; no Java project exists yet |
| Java compiler | `javac 21.0.10` | Available; no Java compilation is required yet |
| Docker CLI | `29.1.3` | Available; no container definition exists |
| Docker Engine | Server `29.1.3`, Linux/x86_64 | Reachable through Docker Desktop; no project container is defined |
| Docker Compose | `v2.40.3-desktop.1` | Available; no Compose definition exists |
| Node.js | `v24.11.0` | Available; no frontend or Node project exists |

## Limited or deferred

| Tool | Observed result | Treatment |
| --- | --- | --- |
| npm | Literal `npm --version` was blocked because PowerShell script execution is disabled | Not required in this iteration; package-manager selection and use are deferred |
| Maven | Not checked because no Maven project exists | Maven will be provided through Maven Wrapper when Java projects are created |
| Spring and Spring Cloud | No versions selected | Deferred until a concrete application requirement exists |
| Kubernetes, Helm, and infrastructure components | No versions or tooling selected | Deferred until deployment requirements exist |

No installation is required for the governance bootstrap.

