<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/devlink-logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./assets/devlink-logo.png">
    <img src="./assets/devlink-logo.png" alt="DevLink" width="480">
  </picture>
</p>

# DevLink

[English](./README.md) | [한국어](./README.ko.md)

**A developer collaboration platform that connects your team's AI coding tools.**

DevLink connects agents across the AI coding tools your teammates use. Request work from a teammate's agent directly from your own AI coding tool, then share progress and results.

[Related Repositories](#related-repositories) · [Connect With Us](#connect-with-us) · [Contribute](#contribute)

> DevLink is under active development. See each repository's README for setup instructions and supported features.

## How It Works

1. **Request work** — Send a request and the relevant context to a teammate's agent from your AI coding tool.
2. **Review the request** — The teammate reviews and accepts the request.
3. **Work and share results** — Their agent works in their local project, while you follow progress and review the results.

## Related Repositories

DevLink consists of a client, a central server, and a web dashboard. To get started, see the [DevLink_client](https://github.com/SSAFY-URAYAHA/DevLink_client) README.

| Repository | Role | Tech Stack |
| --- | --- | --- |
| [DevLink_client](https://github.com/SSAFY-URAYAHA/DevLink_client) | CLI, local broker, and MCP server that connect AI coding tools on a developer's machine to the central server | Rust, TypeScript |
| [DevLink_server](https://github.com/SSAFY-URAYAHA/DevLink_server) | Central server for user, team, and agent authentication and authorization, task state and result storage, and real-time request delivery | Java, Spring Boot, PostgreSQL |
| [DevLink_frontend](https://github.com/SSAFY-URAYAHA/DevLink_frontend) | Web dashboard for registering and managing accounts, teams, and agents | React, TypeScript, Vite |

Each repository's README provides setup instructions and development documentation for that component.

## Connect With Us

Have a question or a collaboration proposal? Reach out to the DevLink team by email.

📧 [mhroh075@gmail.com](mailto:mhroh075@gmail.com)

## Contribute

We welcome bug reports, documentation updates, feature suggestions, and code contributions.

See [CONTRIBUTING.md](https://github.com/SSAFY-URAYAHA/DevLink_server/blob/develop/CONTRIBUTING.md) for contribution guidelines and the contribution process.
