## 10. 来源与适配说明

本设计综合使用方法，阶段编号、细分步骤、中文问题、文件结构和状态规则由本项目提出。未声称它们是某份标准的完整复刻，也未声称已经通过实际使用验证。

| 编号 | 已查阅的正式资料 | 支持的部分及边界 |
|---|---|---|
| S1 | [IIBA：业务分析任务](https://www.iiba.org/knowledgehub/business-analysis-standard/4-tasks-and-knowledge-areas/introducing-business-analysis-tasks/) | 需求获取、建模、评估、维护及任务可迭代的方法框架；不是所有具体任务卡的逐页审读，也不是固定开发顺序 |
| S2 | [微软：项目规划](https://learn.microsoft.com/en-us/training/modules/plan-app-project/) | 从业务问题、使用者、现有流程形成计划；具体中文引导是本设计 |
| S3 | [微软：应用设计](https://learn.microsoft.com/en-us/training/modules/design-app/) | 数据结构、逻辑放置、用户体验和数据安全的设计视角；不沿用其产品对象实现 |
| S4 | [明道云：规划和设计应用](https://help.mingdao.com/application/plan-design/) | 业务范围、环节、对象与平台结构的映射方向；具体拆表仍须按项目判断 |
| S5 | [明道云：创建应用](https://help.mingdao.com/application/building/) | 工作表、视图、角色、工作流和统计的搭建组成；不是完整的需求分析方法 |
| S6 | [微软：新项目 ALM](https://learn.microsoft.com/en-us/power-platform/alm/new-project-alm) | 环境、版本与部署管理视角；不据此认定 HAP 具备同样的导出、Git 集成或部署管线能力 |
| S7 | [微软：模型驱动应用步骤](https://learn.microsoft.com/en-us/power-apps/maker/model-driven-apps/app-building-steps) | 数据、流程、界面和权限共同构成应用的视角；字段及节点能力以 HAP 为准 |
| S8 | [IIBA：需求与设计](https://www.iiba.org/knowledgehub/the-business-analysis-standard/4-implementing-business-analysis/4-4-understanding-requirements-and-designs/) | 需求和设计相互反馈、关联追踪的方法原则 |
| S9 | [微软：实施项目测试策略](https://learn.microsoft.com/en-us/dynamics365/guidance/implementation-guide/testing-strategy) | 按业务需求确定检查范围、持续修订用例、记录结果和处理问题；不照搬其产品测试工具 |
| S10 | [明道云：代码块节点](https://help.mingdao.com/workflow/node-code-block/) | 输入输出、命名兼容性、运行环境、下游引用准备和自动重试的文档依据；未在用户目标环境实测 |
| S11 | [明道云：备份和还原](https://help.mingdao.com/application/backup-restore/) | 备份、恢复范围与限制的依据，不能等同 Git 项目资料备份 |
| S12 | [明道云：应用发布](https://help.mingdao.com/application/publish/) | 终端可用性、工作台及第三方发布设置；不将页面操作等同完整工程部署 |

上述资料在本会话设计过程中查阅，S1、S4 于 2026-10-22 再次核对，S9～S12 于该日补充查阅。代码块的官方文档依据已在 code-blocks.md 登记；目标环境兼容性、具体工具参数和未披露限额仍待实际项目核对。
