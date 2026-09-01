## 欢迎来到 Koishi-CE

**Koishi-CE** 是 [Koishi](https://koishi.chat) 的 **Bun-first 社区再分发组织**。我们将 Koishi 核心（koishi）与控制台前端（webui）合并重构为单一 monorepo，尝试以更现代的工具链重新组织这个项目。

> 本组织与 [Koishijs](https://github.com/koishijs) 组织**无隶属关系**，只是一个独立的社区维护分支。

### 我们尝试做什么

- **现代化工具链**：Bun 运行时与包管理、ESM-only 产物、TypeScript 7 类型检查、vite 8 前端构建、biome 2 代码规范、`bun test` 测试体系
- **尽量保持生态兼容**：npm 包统一发布到 `@koishi-ce` 作用域，同时通过 shim 与 npm alias 占位上游包名，让下游项目尽量兼容既有 Koishi 插件生态
- **社区再分发**：插件经发布链统一发布，`create-koishi-ce` 脚手架可生成纯 `@koishi-ce` 项目

### 主要仓库

- **[Koishi-CE/koishi](https://github.com/Koishi-CE/koishi)** —— 核心 monorepo（运行库、插件、控制台前端、脚手架与网站）

### 许可证

- 大部分代码为 **MIT** 许可；源自 webui 的部分（控制台插件、online 网站等）为 **AGPL-3.0**，详见各仓库的 `NOTICE`。

