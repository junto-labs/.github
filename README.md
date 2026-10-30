# Junto Labs

**Trusted hand-offs, whole products.**

Junto is an open-source platform for building software with people and AI agents working side by side, from customer signal to shipped fix.

Every step in the work is a clear contract that can be done by:

- a **Human**,
- a **Human with an agent assisting**, or
- an **Agent** working under a named human sponsor.

Agents start supervised and earn independence from evidence of good work. Nobody, human or agent, approves their own work.

## Components

Each component is a single tool that does one job. Use one on its own, combine a few, or run them all together on Kubernetes. Several work as Claude Code plugins.

| Repo | What it does | Status |
| --- | --- | --- |
| [baton](https://github.com/junto-labs/baton) | Workflow state: what happens next, who may do it, and when it's done | Early development |
| [knowtorious](https://github.com/junto-labs/knowtorious) | Knowledge with access control, so each actor sees only what it should | Early development |
| [crux](https://github.com/junto-labs/crux) | Runs and supervises AI coding agents | Fork of Hive Commons Crux |
| [junto-spec](https://github.com/junto-labs/junto-spec) | Shared schemas the components agree on | Early development |
| [junto](https://github.com/junto-labs/junto) | Puts the components together: Helm chart, plugin marketplace, examples | Early development |

## Credit

Junto builds on [Hive Commons](https://github.com/hivecommons). Crux, Baton and several smaller tools start from Hive Commons projects, used under the Apache-2.0 license.

## Get involved

Read [CONTRIBUTING](https://github.com/junto-labs/.github/blob/main/CONTRIBUTING.md) to get started. To report a security issue, follow our [security policy](https://github.com/junto-labs/.github/blob/main/SECURITY.md).

Docs and updates: [juntolabs.dev](https://juntolabs.dev)
