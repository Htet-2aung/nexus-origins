# Nexus Origins 

**A unified desktop platform for cloud secrets management, access control, auditing, and developer tooling.**

Nexus brings project and environment management, secure secrets workflows, access administration, audit visibility, and Origins Forge into one desktop experience.

Designed for teams that need a centralized cloud control plane alongside local developer tooling, Origins Unified connects to the Origins Cloud API while keeping supported Forge operations on the local machine.

## Overview

Nexus combines a desktop interface with cloud-backed management capabilities to provide a consistent workspace for development and infrastructure workflows.

### Features

- **Project Management** — Organize projects and their environments in one workspace.
- **Secrets Management** — Manage environment secrets through the cloud service.
- **Access Control** — Manage authorized access to projects and environments.
- **Audit Trail** — Review recorded activities and security-relevant events.
- **API Token Management** — Manage supported API token workflows.
- **Origins Forge** — Access local developer tooling from the desktop application.
- **Cloud Integration** — Connect to Origins Cloud for authentication and centralized data management.
- **Desktop Experience** — A dedicated macOS application built around the Origins Unified interface.

## Distribution

Nexus aka Origins Unified is distributed as a **macOS disk image (`.dmg`)** through GitHub Releases.

Download the available DMG from the repository's [Releases](../../releases) page.

This repository is intended for product information and binary distribution. Development source code, internal implementation details, and private infrastructure configuration are not included in the public release.

## Security

Nexus is designed to separate local developer tooling from cloud-managed resources.

- Cloud authentication and authorization are handled by the cloud service.
- Cloud-managed data is processed through authenticated API requests.
- Secret storage and encryption remain under the control of the cloud service.
- Local Forge execution is separate from remote cloud operations.

Security capabilities depend on the deployed service configuration, account permissions, and the specific operations enabled in the installed release.

Please do not publish passwords, access tokens, secret values, private keys, or other sensitive information in GitHub Issues or public discussions.

## Proprietary License

**Copyright © 2026 Origins Software Limited United Kingdom All rights reserved.**

Nexus aka Origins Unified is proprietary software. It is not open-source software, and no rights are granted except as expressly authorized in writing by Origins Software.

Unless explicitly authorized in writing, you may not:

- Copy, modify, adapt, or create derivative works of the software.
- Redistribute, republish, sublicense, sell, rent, or commercially exploit the application.
- Reverse engineer, decompile, or disassemble the application, except where such restrictions are prohibited by applicable law.
- Remove or alter copyright notices, proprietary notices, or other rights-management information.
- Use the Origins Unified name, logo, trademarks, or branding in a way that implies endorsement or authorization.

Downloading or possessing a DMG does not transfer ownership of the software or grant rights to its source code.

All rights not expressly granted are reserved by Origins Software. Use of the application is subject to any applicable written license or agreement.

**License:** Proprietary — All Rights Reserved  
**Third-party components:** Remain subject to their respective licenses and notices.

## Support and Issues

For product issues, feature requests, or security concerns, use the repository's available contact channels. Avoid including credentials, secret values, private infrastructure details, or other confidential information in public reports.

---

**Origins Unified**  
*One desktop. One cloud control plane. A unified developer workflow.*
