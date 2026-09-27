# Awesome-Editorial-Workflow

# 顶级编辑工作流平台生态系统



**精选 SaaS 产品与开源 GitHub 项目列表**

*聚焦新闻编辑流程、任务分配、内容规划与多渠道发布*

**最后更新：2026 年 9 月**



本仓库追踪**编辑工作流**领域的知名 **SaaS 平台**与**开源项目**。这些工具帮助新闻机构、出版社和企业内容团队管理从选题策划、任务分配到编辑审核、多渠道发布的完整内容生命周期。



**示例**包括 Desk-Net、Avid iNEWS、Arc XP、WoodWing Studio、ContentFlow、CUE、Shorthand、Kontent.ai 和 Desk-Net（该领域的领先者）。



**开源重点**：编辑工作流领域有一个**极其突出的开源领导者**——**Superdesk**。这是全球新闻机构广泛采用的生产级开源新闻室管理系统，被挪威通讯社（NTB）、比利时通讯社（Belga）、加拿大通讯社（The Canadian Press）和澳大利亚联合通讯社（AAP）等主要新闻机构用于实际生产。与此同时，**Wagtail** 等开源 CMS 通过自定义开发可以构建编辑工作流功能（如 Ubyssey 报社的 Stove 项目）。本列表重点收录这两类可自托管的方案。



欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。



## 目录



- [SaaS/托管平台](#saas托管平台)

- [开源 GitHub 项目](#开源github项目)

- [如何贡献](#如何贡献)

- [免责声明](#免责声明)



## SaaS/托管平台



- **[Desk-Net](https://www.desk-net.com/)**

  编辑工作流和故事规划平台，帮助新闻室管理选题、任务分配、截止日期和内容日历。广泛应用于德语区媒体机构。



- **[Avid iNEWS](https://www.avid.com/)**

  广播新闻室计算机系统，用于脚本编写、运行顺序管理和新闻制作工作流。深度集成 Avid 的媒体制作生态系统。



- **[Arc XP](https://www.arcxp.com/)**

  华盛顿邮报开发的云原生内容平台，提供编辑工作流、内容管理、多平台发布和分析。适合大型新闻机构。



- **[WoodWing Studio](https://www.woodwing.com/)**

  多渠道编辑管理和内容制作平台。支持印刷、数字和移动发布的统一编辑工作流。



- **[ContentFlow](https://contentflow.io/)**

  编辑工作流自动化平台，专注于内容规划、任务管理和团队协作。



- **[CUE](https://cue.group/)**

  新闻室规划和工作流工具，用于管理选题、任务和内容日历。



- **[Shorthand](https://shorthand.com/)**

  视觉叙事和数字内容创作平台，用于创建滚动式故事和交互式内容，常与 CMS 配合使用。



- **[Kontent.ai](https://kontent.ai/)**

  云端无头 CMS，提供结构化内容建模、编辑工作流、本地化和 API 驱动的多渠道发布。



- **[Desk-Net](https://www.desk-net.com/)**

  （同上述条目）



## 开源 GitHub 项目



- **[Superdesk](https://github.com/superdesk/superdesk)**  

  由 Sourcefabric 开发的**开源新闻室管理系统**，提供从内容创作、编辑审核到多渠道发布的完整端到端工作流。核心功能包括：**编辑工作流**（基于“Desk”概念组织团队，如新闻台、体育台、专题台，支持文章在台间流转和审批）、**内容规划**（编辑日历、任务分配、覆盖计划）、**多源内容聚合**（支持 NewsML-G2、IPTC 标准、RSS、FTP、邮件等多种来源）、**实时协作**（多编辑同时工作）、**多渠道发布**（网站、移动、印刷、社交媒体）、**Newshub**（客户端内容门户）、**分析模块**（跟踪新闻室效率指标）。技术栈：Python/Flask、MongoDB、Elasticsearch、AngularJS。被 NTB、Belga、The Canadian Press、AAP 等主要新闻机构用于生产环境。**AGPL-3.0** 。



- **[Wagtail](https://github.com/wagtail/wagtail)**  

  基于 Django 的开源 CMS，被 NASA 喷气推进实验室和 Google 等组织使用。虽然 Wagtail 本身不是专门的编辑工作流工具，但其灵活的页面模型、工作流系统和权限管理使其成为**构建自定义新闻室编辑流程的坚实基础**。例如，Ubyssey 报社在 Wagtail 之上构建了 **Stove** 系统，将任务管理器和手稿编辑器直接集成到 CMS 中，解决了 Google Docs + CMS 分离的工作流痛点。Wagtail 的工作流功能支持多阶段审批、草稿/发布状态管理和编辑协作。**BSD-3-Clause** 。



- **[Payload](https://github.com/payloadcms/payload)**  

  TypeScript 优先的开源无头 CMS，内置管理界面、草稿、访问控制和编辑工作流。73.1k stars，MIT 许可。适合需要**代码优先、可深度定制**编辑流程的团队。其块编辑器（blocks）和字段系统可用于构建结构化的内容规划和任务分配界面。



- **[Strapi](https://github.com/strapi/strapi)**  

  领先的开源无头 CMS，100% JavaScript，可扩展且完全可定制。提供内容类型构建器、角色权限和工作流管理。适合需要**完全控制数据模型和编辑流程**的开发团队。



- **[Directus](https://github.com/directus/directus)**  

  将任何 SQL 数据库转变为无头 CMS，提供管理应用、基于角色的访问控制和即时 REST/GraphQL API。37.7k stars。适合需要**在现有数据库之上叠加编辑工作流**的团队。



- **[Manuskript](https://github.com/olivierkes/manuskript)**  

  面向作者的开源写作工具，提供**结构化的写作规划环境**：雪花法（Snowflake method）从一句话扩展到完整大纲、角色管理、情节构思、索引卡和大纲模式、专注写作模式、故事线视图。虽然主要面向小说创作，但其**章节/场景组织、元数据标记和导出功能**（HTML、ePub、OpenDocument、DocX）可适用于长篇幅内容规划和编辑工作流。**GPL-3.0** 。



### 其他强开源选项



- **通用 CMS 基础**：**Wagtail**（Django，工作流系统）、**Payload**（TypeScript，深度定制）、**Strapi**（JavaScript，灵活性）、**Directus**（SQL 数据库叠加）。

- **写作规划工具**：**Manuskript**（雪花法，角色/情节管理）、**novelWriter**（纯文本写作，元数据语法）。

- **新闻室特定**：**Superdesk**（生产级，AGPL-3.0，主要新闻机构采用）。



**构建自定义系统的框架**：以 **Superdesk** 作为开箱即用的新闻室编辑工作流平台；或者以 **Wagtail**、**Payload** 或 **Strapi** 为基础，利用其工作流系统和权限管理构建自定义编辑流程（参考 Ubyssey 的 Stove 项目模式）。对于内容规划阶段，**Manuskript** 的雪花法和角色管理可作为辅助工具。



## 如何贡献



1. Fork 仓库。

2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。

3. 包含：名称、链接、1–2 句描述，以及是 SaaS 还是开源。

4. 提交 PR 并附简短说明。



如果你觉得这个仓库有用，请点星！



## 免责声明



- 这是一个**社区精选**列表——并非详尽无遗，也不构成认可。

- 编辑工作流平台处理可能敏感的内容草稿和内部沟通；确保适当的访问控制和数据保护。

- **开源现实**：**Superdesk** 是编辑工作流领域唯一成熟的生产级开源替代方案，被主要新闻机构实际采用。其他开源 CMS（Wagtail、Payload、Strapi）需要通过自定义开发才能实现新闻室级别的编辑工作流功能。对于追求“开箱即用”编辑工作流的团队，Superdesk 是最直接的起点。
