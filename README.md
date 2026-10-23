# C.C.D · CCD女团

> 歌自己写，号自己养。

**非官方 AI 拟人共创企划**。C = ChatGPT 龙娘，C = Claude 大小姐，D = DeepSeek 鲸鱼娘「鲸鲸」。角色称呼不代表任何公司的官方形象、授权、合作或真实模型参与记录。

这里集中保存**练习生图片参考、新歌歌词提案、分期创作参考及来源记录**，不存放模型权重、API 凭据、生产环境或未经许可的对标素材。

## 先看第一期

《一盏灯，也要开场》：全部出道预算只有三元，三个人最终共享一盏灯。

- [首期目录与预览](episodes/ep01/README.md)
- [DeepSeek 鲸鲸：演出参考](episodes/ep01/references/deepseek/whale-performance-v7.png)
- [DeepSeek 鲸鲸：预算反应参考](episodes/ep01/references/deepseek/whale-reaction-v7.png)
- [第一期歌词原文 · v2](episodes/ep01/lyrics/one-light-v2.txt)
- [来源、版本与 SHA-256 清单](episodes/ep01/asset-manifest.json)

**当前图片为 V7 待审候选，歌词为创作参考，不是最终成片或已经开放商用的素材包。** 图片文件与歌词均保留原内容；没有上传对标原视频、第三方抽帧、旧版歌词、歌曲音频或内部日志。

## 怎么投稿

仓库开放给你后，从 **Issues → New issue** 选择「练习生图片参考」或「新歌歌词提案」。不会 Git 也可以填表。技术贡献者可按目录规范提 PR；提交不等于入选，也不等于同意商用。

| 入口 | 要交什么 | 规范 |
|---|---|---|
| 练习生图片参考 | 静态 PNG/JPEG/WebP、角色辨识点、一个本事、一个坏毛病、来源与授权范围 | [图片规范](docs/trainee-reference-spec.md) |
| 新歌歌词提案 | 原创或明确获授权的 UTF-8 歌词、主题、段落、曲风、时长目标、来源与授权范围 | [歌词规范](docs/lyrics-spec.md) |

请先读 [CONTRIBUTING](CONTRIBUTING.md) 和 [素材与授权边界](LICENSE_SOURCE_NOTES.md)。不要求真实姓名、手机号、身份证或私人邮箱。

## 目录

```text
.github/ISSUE_TEMPLATE/    两类投稿表单
.github/pull_request_template.md
submissions/trainees/     新练习生提案暂存（与生产素材分离）
submissions/lyrics/       新歌歌词提案暂存
episodes/ep01/            第一期参考资产与来源清单
docs/                    接收规范和维护者检查表
```

流程：**收到提案 → 安全/格式检查 → 来源/授权复核 → 创作审核 → 试用 → 维护者记录采纳**。未完成人工审核的文件不得写成「已人工批准」；Issue/PR 模板只是流程提醒，不是自动安全或版权审查系统。

## 当前边界

- 初始资料按私有协作准备；是否公开接收投稿，以仓库实际可见性与维护者通知为准。
- 尚未选择覆盖所有内容的统一开放许可，使用范围按每项素材记录处理。
- 三名角色的跨曲稳定歌唱声线尚未验收；本仓库不会把单主唱试样宣称为三人固定轮唱。
- 没有自动执行投稿代码的工作流；自动合并、分支保护和公开发布均不因文档存在而视为启用。
