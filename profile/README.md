# Seedlands

## A customizable agent living-world runtime, built on an open voxel game engine.

**Seedlands** is building runtime infrastructure for persistent worlds in which agents can live, perceive, act, collaborate, and change shared state under explicit world rules. The goal is not one fixed game or setting, but a customizable foundation for creating different agent societies, simulations, and playable experiences.

To make those worlds concrete and inhabitable, we are also building the voxel game engine capabilities the runtime depends on: deterministic world generation, authoritative simulation, chunk streaming, editing, physics, rendering, persistence, and developer tooling. Agents and human players should participate through the same inspectable world systems, rather than treating agents as an external control layer added after the fact.

The current sword-and-magic survival experience is our first playable MVP and reference world. It helps us validate the runtime and engine end to end; it is not the boundary of the project or its final product definition.

[Play the Web Sandbox](https://seedlands-game.github.io/seedlands-web-sandbox/) · [Browse the source](https://github.com/seedlands-game/seedlands-web-sandbox) · [Join the discussion](https://github.com/seedlands-game/seedlands-web-sandbox/issues)

---

## Seedlands：可定制的 Agent Living World Runtime 与开放体素游戏引擎

**Seedlands** 的核心目标，是构建可定制的 Agent Living World Runtime：让 Agent 能够在明确的世界规则下生活、感知、行动、协作，并持续改变共享世界状态。我们不是只打造一款固定游戏或一种题材，而是为不同的 Agent 社会、模拟系统和可玩体验提供基础设施。

为了让这些世界真正可进入、可交互，我们也在构建 Runtime 所依赖的体素游戏引擎能力，包括确定性世界生成、权威模拟、Chunk 流式加载、编辑、物理、渲染、持久化与开发工具。Agent 与人类玩家应通过同一套可观察、可验证的世界系统参与其中，而不是把 Agent 作为事后外挂的外部控制层。

当前的剑与魔法生存体验只是第一个可玩 MVP 和参考世界，用于端到端验证 Runtime 与引擎；它不是项目的产品边界，也不是最终愿景本身。

[试玩 Web 沙盒](https://seedlands-game.github.io/seedlands-web-sandbox/) · [浏览源代码](https://github.com/seedlands-game/seedlands-web-sandbox) · [参与讨论](https://github.com/seedlands-game/seedlands-web-sandbox/issues)

---

## What exists today / 当前进展

**Seedlands Web Sandbox** is the first playable vertical slice and the current engine proving ground.

- A voxel engine foundation with deterministic terrain, climate, biomes, rivers, lakes, trees, editable voxels, and optimized chunk meshes.
- A Web living-world runtime foundation with authoritative state, explicit world/worker/physics/rendering/persistence boundaries, and a small deterministic ecology.
- A local single-player sword-and-magic survival and exploration MVP with crafting, combat, water, a macro map, and browser persistence.
- An end-to-end reference experience used to discover the runtime, engine, and tooling required by future customizable agent worlds.

**Seedlands Web Sandbox** 是首个可玩垂直切片，也是当前用于验证引擎的试验场。

- 体素引擎底座：确定性地形、气候、生物群系、河湖、树木、可编辑体素与优化后的 Chunk 网格。
- Living World Runtime 底座：权威状态、清晰的世界/Worker/物理/渲染/持久化边界，以及小型确定性生态。
- 本地单人剑与魔法生存探索 MVP：包含合成、战斗、水体、宏观地图与浏览器持久化。
- 一个端到端参考体验，用于发现未来可定制 Agent 世界真正需要的 Runtime、引擎与工具能力。

## The long view / 长期愿景

We are working toward a reusable, customizable stack for agent living worlds:

- A persistent world runtime with explicit rules, time, state, events, history, and lifecycle boundaries.
- Agent-native perception and action interfaces that let autonomous inhabitants share the same world model as human players.
- A modular voxel game engine and toolchain for building, operating, observing, and extending those worlds.
- Reference experiences that validate the stack without defining or limiting what can be built with it.

The sword-and-magic world—including essence and magic, autonomous societies, persistent history, longevity, reincarnation, and the six realms—is one ambitious reference direction. These are not features we claim are complete today, and that setting is not the only experience the platform should support.

我们的长期目标是一套可复用、可定制的 Agent Living World 技术栈：

- 具备明确规则、时间、状态、事件、历史与生命周期边界的持久世界 Runtime。
- Agent 原生的感知与行动接口，使自主居民与人类玩家共享同一世界模型。
- 可模块化扩展的体素游戏引擎与工具链，用于构建、运行、观察和演化这些世界。
- 用参考体验持续验证整套技术栈，但不让任何一种玩法反过来限定平台边界。

剑与魔法世界——包括源质与魔法、自主社会、持久历史、长生、转生与六界——是其中一个有野心的参考方向。这些能力尚未全部交付，这一题材也不是平台唯一需要支持的体验。

## Build in the open / 开源共建

We welcome contributions to the living-world runtime, voxel engine, developer tooling, and reference MVP. Please start with the [contribution guide](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/CONTRIBUTING.md), search existing issues, and open an issue before proposing a large feature, public-contract change, persistence migration, world-generation change, or rendering-architecture change.

欢迎参与 Living World Runtime、体素引擎、开发工具与参考 MVP 的共建。请先阅读[贡献指南](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/CONTRIBUTING.md)，检索已有 Issue；对大型功能、公开契约、存档迁移、世界生成或渲染架构变更，请先发起 Issue 讨论。

Source code and documentation are licensed under [Apache License 2.0](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/LICENSE). Assets and the Seedlands brand have their own terms; please review [ASSETS.md](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/ASSETS.md) and [TRADEMARKS.md](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/TRADEMARKS.md) before reuse.

源代码与文档采用 [Apache License 2.0](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/LICENSE)；素材与 Seedlands 品牌另有适用条款，复用前请阅读 [ASSETS.md](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/ASSETS.md) 与 [TRADEMARKS.md](https://github.com/seedlands-game/seedlands-web-sandbox/blob/main/TRADEMARKS.md)。
