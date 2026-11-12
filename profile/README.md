# Nomisma Labs

Nomisma Labs is a software workshop for building trading systems from reusable C++
components. The work covers application composition, configuration, logging,
communication, and shared development tooling.

## Start here

- [Dev Journal](https://nomisma-labs.github.io/) : current implementation progress and related articles.
- [Handbook](https://github.com/nomisma-labs/handbook): purpose, architecture, decisions,
  and plans for the project.
- [assembly](https://github.com/nomisma-labs/assembly): static application composition,
  typed event routing, and callback delegates.
- [json_config](https://github.com/nomisma-labs/json_config): typed C++ application
  configuration with JSON loading and Python configuration generation.
- [asio_comm](https://github.com/nomisma-labs/asio_comm): asynchronous TLS WebSocket
  and HTTPS clients, timers, and cryptocurrency market-data examples.
- [MD capture](https://github.com/nomisma-labs/md_capture): collection of MD capture components.

## Architecture

| Layer | Responsibility | Roadmap |
| --- | --- | --- |
| Toolchain | Repository setup, builds, tests, and delivery tooling | [Toolchain plan](https://github.com/nomisma-labs/handbook/blob/master/master-plan/toolchain-layer.md) |
| Core | Common types, composition, configuration, and logging | [Core plan](https://github.com/nomisma-labs/handbook/blob/master/master-plan/core-layer.md) |
| Services | Communication, execution, and reusable runtime facilities | [Service plan](https://github.com/nomisma-labs/handbook/blob/master/master-plan/service-layer.md) |
| Applications | Trading workflows built from the shared components and services | [Application plan](https://github.com/nomisma-labs/handbook/blob/master/master-plan/application-layer.md) |

Component repositories document their current implementation, usage, and releases.
Each repository records its own license; the handbook explains the
[licensing policy](https://github.com/nomisma-labs/handbook/blob/master/master-plan/licensing.md).
