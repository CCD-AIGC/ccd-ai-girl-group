# Issue 表单维护说明

核对日期：2026-10-23。按 GitHub 官方 Issue Forms、表单 schema 与常见验证错误说明编写；仅使用 markdown、input、textarea、checkboxes 和必要校验字段。每个输入使用独立 ID/标签；附件文本域不设置 render。模板应提交到默认分支的 `.github/ISSUE_TEMPLATE/`，PR 使用单独的 Markdown 模板。

本项目关闭空白 Issue 入口，引导使用两类表单；不依赖尚未创建的标签、组织 Issue 类型、项目编号或自动分派。未新增 Actions，也不执行投稿代码。更改接收类型或自动化时须另行安全评审。

官方说明指出部分 required 校验只适用于公开仓库。即便表单允许提交，维护者也必须人工核对必填项、附件和授权；私有仓库尤其不能把界面校验当审核。公开可见性、文件安全、授权与内容质量都不是 YAML 能证明的。

本地 YAML/字段结构检查不等于 GitHub 网页实际渲染验收；仓库建立后维护者应分别打开两种表单，确认字段显示、附件输入、提交提示及 PR 模板。不要为了验收填造审核通过记录。

官方依据页面名称：

- GitHub Docs — Syntax for issue forms
- GitHub Docs — Syntax for GitHub's form schema
- GitHub Docs — Configuring issue templates for your repository
- GitHub Docs — Common validation errors when creating issue forms
