<!-- Decorative wordmark; the following H1 supplies the accessible project name. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/edgeloom-wordmark-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/edgeloom-wordmark-light.svg">
  <img alt="" src="assets/edgeloom-wordmark-light.svg" width="240">
</picture>

# EdgeLoom

**Open tools and reviewable evidence for smart-home edge-driver artifacts.**

EdgeLoom is an active, pre-1.0 open-source toolchain for auditing, validating,
patching, restoring, translating, and discovering smart-home edge-driver
artifacts. It complements platform-native ecosystems by making device profiles,
capability mappings, and transformation evidence easier to inspect, compare,
and review.

[Project website](https://edgeloom-oss.github.io/edgeloom/) ·
[Get started](https://github.com/edgeloom-oss/edgeloom#install) ·
[Documentation](https://github.com/edgeloom-oss/edgeloom/tree/main/docs) ·
[Python package](https://pypi.org/project/edgeloom/) ·
[Project discussions](https://github.com/edgeloom-oss/edgeloom/discussions)

## Evidence snapshot

These are public research and project-health signals, not adoption metrics.

| Evidence | Current public state |
| --- | --- |
| Research basis | **119** hidden attributes · **31** devices · **16** manufacturers — [CCS 2025 study sample](https://ittc.ku.edu/~bluo/pubs/xu2025ccs.pdf), not EdgeLoom coverage. |
| Product release | [**v0.2.0**](https://github.com/edgeloom-oss/edgeloom/releases/tag/v0.2.0) · [PyPI **0.2.0**](https://pypi.org/project/edgeloom/0.2.0/) · Python 3.11+ |
| Engineering | [**6** CLI workflows](https://github.com/edgeloom-oss/edgeloom#commands) · [passing `v0.2.0` release-commit CI](https://github.com/edgeloom-oss/edgeloom/actions/runs/36372151093) · [Apache-2.0](https://github.com/edgeloom-oss/edgeloom/blob/main/LICENSE) |
| Project structure | **2** active implementation repositories — [core](https://github.com/edgeloom-oss/edgeloom) + [bootstrap catalog](https://github.com/edgeloom-oss/edgeloom-catalog); excludes profile infrastructure and the archived predecessor. |

*Project status checked 27 September 2026; refresh these rows at release milestones.*

## Projects

- **[EdgeLoom](https://github.com/edgeloom-oss/edgeloom)** — the active core
  command-line toolchain and its versioned artifact and evidence schemas.
- **[EdgeLoom Catalog](https://github.com/edgeloom-oss/edgeloom-catalog)** — a
  bootstrap repository for a reviewable, evidence-backed mapping catalog. It
  currently contains scaffolding and synthetic examples, not verified pilot
  data or adoption claims.

## Participate

We welcome bug reports, device reports, design discussions, and pull requests
from developers, maintainers, smart-home users, device manufacturers,
integrators, security researchers, and standards communities.

[Contributing guide](https://github.com/edgeloom-oss/edgeloom/blob/main/CONTRIBUTING.md) ·
[Governance](https://github.com/edgeloom-oss/edgeloom/blob/main/GOVERNANCE.md) ·
[Security reporting](https://github.com/edgeloom-oss/edgeloom/blob/main/SECURITY.md) ·
[Support](https://github.com/edgeloom-oss/edgeloom/blob/main/SUPPORT.md)

**[HA2ST-Translator](https://github.com/edgeloom-oss/HA2ST-Translator)** is
archived; its translation work and history continue in EdgeLoom.
