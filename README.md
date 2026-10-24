# 明道云项目落地 Skill

面向明道云应用搭建工程师，从稀少需求开始，逐步完成业务分析、模型与流程设计、搭建、检查、交付和迭代。重点是客观引导、变更追踪与经验沉淀。

版本：0.1.0，2026-10-24。已生成安装文件；结构检查与业务行为验证分别记录，尚未开展实际项目案例验证。

## 安装

将本仓库的 `skills/hap-project-delivery` 整个目录复制到 Codex 的 skills 目录（通常为 `~/.codex/skills/`），随后在新会话中调用 `$hap-project-delivery`。仓库中的 `design/` 是设计来源，不需要安装。安装后由当前环境提供文件工具及可选的 HAP/Git 工具；本 skill 不捆绑账号或连接配置。

## 使用

例如：

> 使用 $hap-project-delivery，帮我从一个模糊想法开始规划应用。先分析需求，并将项目资料保存在当前工作区。

> 使用 $hap-project-delivery，继续 projects/某项目；我修改了业务规则，请分析对字段、流程和已有检查结论的影响。

> 使用 $hap-project-delivery，将指定项目资料上传到已配置的 GitHub 仓库。

阶段 0～7 可以反复进入，不要求冻结所有需求后才开始。默认协助工程师手动搭建；自动操作需有明确范围、环境及相应工具。资料拉取不会自动改动 HAP。

## 文件

- [Skill 入口](skills/hap-project-delivery/SKILL.md)
- `skills/hap-project-delivery/references/`：阶段方法、引导、代码块规范、变更与同步、正式资料来源。
- `skills/hap-project-delivery/assets/project/`：最小项目模板。
- `design/`：设计过程资料，与可安装包分开。

真实业务项目资料建议保存在专用项目仓库的 `projects/<项目目录>/`，多个项目分目录管理。该仓库保存 skill 本身；不用把实际客户项目资料写入 skill 安装目录。目录仅是逻辑划分，不提供独立访问权限。

本版不包含培训、旧数据迁移及上线陪跑。代码块优先中文说明与注释，输出技术键按官方兼容性提示默认英文。平台能力和限制必须结合实际环境核实。
