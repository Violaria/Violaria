<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="Nanako. DevSecOps, C++, Stardust Reverie Technology Co., Ltd." width="100%">
  </picture>
</p>

<p align="center"><a href="README.md">English</a> &middot; 中文 &middot; <a href="README.la.md">Lingua Latīna</a></p>

<p align="center">我做架构优先、能完全自持的软件，从 DevOps 平面到本地智能体和端到端加密笔记。</p>

---

## 价值观
### 开发
  - 我坚持架构尊严高于一切，交付速度和需求驱动都排在架构设计正确性之后。工程必须基于架构纹理，最讨厌把架构尊严让位给ticket闭环的奴性工程。
  - 比起在架构上打补丁/开架构上的例外，我更愿意为了未来长期设计而重构架构。我在设计上以 API 为先，重视 API 与 SDK 的工程质量。
  - 我支持开发者优先（Dev-First）。对"客户/市场需求优先"（Sales-First）和"消费者优先"不感兴趣，同理我厌恶追求短期交付、快速迭代、抢占市场窗口的价值观。
  - 我不反对过度设计，我讨厌以 YAGNI 和 KISS 为借口，让欠考虑、低抽象、泛用性差的劣质代码蒙混过关。
  - 我有工程洁癖，只设计和开发符合我自身代码审美的软件。我讨厌迎合式的用户体验，商业化变现更不在我的兴趣之内。我也不需要为赚钱而工作。
  - 我不喜欢 Vibe Coding，但我并不反对 AI。一切 AI Coding工程都应规范化，且生成的代码都须经过人类专家审计，至少人类必须审查测试代码。
  - Digital Sovereignty，自主数据主权，能本地就不上云，对All in 云服务持负面态度，我本地机房又不缺硬件条件和集群资源。
### 开源
  - 我不是开源运动的狂信徒。
  - 我反对开源价值观绑架。是否开源应是开发者的自由。开源与闭源只是两种同等价值的路线选择，且无需任何解释或理由。
  - 我反对未经授权的非法逆向工程，更反对把窃取行为包装成开源精神或互联网分享精神。
  - 我支持自由软件，但我关心的是开发者支配自己作品的自由，用户的自由我不感兴趣。
  - 软件是否安全，取决于设计、实现与审计。开源不等于安全，闭源也不等于不安全。

## 项目

### 平台与基础设施

| 项目 | 简介 | 主要开发语言 | 许可 | 状态 |
| --- | --- | --- | --- | --- |
| [**Astra**](https://gitlab.rothmary.com/Astra/Public) | 私人主权的统一 DevOps 平面，把软件工程管理与服务器运维收敛到一个平台。Qt、UE 和网页客户端共用同一套协议、权限与审计核心。 | C/C++ | 专有许可（EULA） | 开发中 |
| [**Aevum**](https://gitlab.rothmary.com/Aevum) | 可验证公共记录网络。极小的可审计内核从链上按内容寻址取回应用协议、数据模式和密码学套件，验证后在沙箱中执行。底层是许可制 BFT 账本。 | Go、Rust、Solidity | MIT | 设计阶段 |

### 智能体

| 项目 | 简介 | 主要开发语言 | 许可 | 状态 |
| --- | --- | --- | --- | --- |
| [**Armillary**](https://gitlab.rothmary.com/Armillary) | 本地部署的智能体运行时，提供 CLI、SDK 和 MCP 入口，内置工具与子智能体，同时支持 SaaS 式部署。 | TypeScript | 专有许可（EULA） | 开发中 |
| [**Gestalt Mind**](https://gitlab.rothmary.com/Gestalt) | 面向智能体的办公自动化系统：账号、职位、工作组、范围权限、共享文件与共同知识，以及邮件和公告，各智能体保留原生会话。 | Rust | 源码可读，只读许可（RSL） | 开发中 |

### 内容与笔记

| 项目 | 简介 | 主要开发语言 | 许可 | 状态 |
| --- | --- | --- | --- | --- |
| [**Pandectae**](https://gitlab.rothmary.com/Pandectae) | 以 Go 重新实现 WordPress 的通用 CMS，概念与数据兼容，任何 WordPress 站点都能无损导入。 | Go | Apache 2.0 | 开发中 |
| [**Eburnea**](https://gitlab.rothmary.com/Eburnea) | 在 Pandectae 上重建的个人博客。 | Go | 专有许可 | 立项中 |
| [**Tabularium**](https://github.com/Violaria/Tabularium) | 自托管的端到端加密笔记同步服务器，配套 Obsidian 插件，提供云笔记、分享、发送到 Kindle 和 AI 管理员。 | TypeScript | MIT | 已发布 |
| [**Litterae Anonymae**](https://gitlab.rothmary.com/Litterae) | 自维护的匿名提问箱：访客无需注册即可提问，站主公开回答。| Ruby、TypeScript | MIT | 运行中 |

所有仓库托管于自建 GitLab 实例。开源项目也许在该处公开源码；专有项目仅发布成品与文档。Tabularium 的源码同时公开在 GitHub。

## 技术

**语言**：C、C++、Rust、Go、TypeScript、Python、x86ASM

## 组织

Stardust Reverie Technology Co., Ltd.
