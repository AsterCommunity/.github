<p align="center">
  <strong>AsterCommunity</strong>
  <br />
  Connect the Cosmos. Accelerate Everything.
  <br />
  <a href="https://www.astercosm.com/">astercosm.com</a>
</p>

## Why AsterCommunity exists

Self-hosted infrastructure has a gap. On one side there are full private-cloud suites that try to do everything and end up heavy, opaque, and hard to modify. On the other side there are single-purpose tools that do one thing well but don't compose into a coherent system.

AsterCommunity builds the middle layer: a set of focused, self-hosted services that share one Rust runtime foundation ([AsterForge](https://github.com/AsterCommunity/AsterForge)) and one set of operational conventions. Each service does one job, is meant to be read and modified, and deploys without an enterprise stack. Because they share the same kernel — configuration, storage, observability, background tasks, audit logging — operating three Aster services feels like operating one, not three.

Everything here is MIT-licensed. Everything is built to be deployed, audited, and hacked on by small teams.

## Projects

### Active

| Project | What it is |
|---|---|
| [AsterDrive](https://github.com/AsterCommunity/AsterDrive) | Self-hosted file infrastructure for small teams: reliable uploads, storage policies, S3 / remote-node backends, WebDAV / WOPI, and ops tooling. The flagship service. |
| [AsterForge](https://github.com/AsterCommunity/AsterForge) | Shared Rust runtime foundation and infrastructure kernel for all Aster services — configuration, storage, WebDAV/XML machinery, observability, scheduled tasks. |
| [AsterYggdrasil](https://github.com/AsterCommunity/AsterYggdrasil) | Self-hosted Minecraft skin site and Yggdrasil / authlib-injector authentication server. |

### Early stage

| Project | What it is |
|---|---|
| [AsterPulse](https://github.com/AsterCommunity/AsterPulse) | Distributed uptime monitoring system. |

### Planned

| Project | What it is |
|---|---|
| [AsterMail](https://github.com/AsterCommunity/AsterMail) | Sovereign mail system. |
| [AsterDriveClients](https://github.com/AsterCommunity/AsterDriveClients) | Native clients for AsterDrive. |

### Supporting

| Project | What it is |
|---|---|
| [AsterDriveMigration](https://github.com/AsterCommunity/AsterDriveMigration) | Migration tooling for AsterDrive. |
| [www.astercosm.com](https://github.com/AsterCommunity/www.astercosm.com) | The AsterCosmos root webpage. |

## Status

AsterDrive is under active development (`v0.4.x` line). AsterForge and AsterYggdrasil are actively maintained. AsterPulse is in early development; AsterMail and the native clients are on the roadmap.

In the `0.x` series, expect minor versions to carry compatibility and scope changes.
