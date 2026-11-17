# daily-skills

常用 Agent Skills 合集,来自 [anthropics/skills](https://github.com/anthropics/skills)(各 skill 遵循其原始许可,见各目录内 LICENSE.txt / 上游仓库)。

目录按「分类」/「中文功能名」/skill 目录名 组织,skill 目录名保持英文原名,以便 SKILL.md 的 name 与目录一致。

| 分类 | 功能 | skill |
|---|---|---|
| 文档处理 | 创建和编辑 Word 文档 | docx |
| 文档处理 | 编辑 PDF | pdf |
| 文档处理 | 创建和编辑 PPT | pptx |
| 文档处理 | 创建和编辑 Excel | xlsx |
| 开发与技术 | 生成 MCP Server | mcp-builder |
| 开发与技术 | Web 应用测试 | webapp-testing |
| 开发与技术 | 构建前端 Artifact | web-artifacts-builder |
| 开发与技术 | 前端界面设计 | frontend-design |
| 开发与技术 | Claude API 开发指引 | claude-api |
| 开发与技术 | 创建 Skill | skill-creator |
| 创意与设计 | 算法艺术 | algorithmic-art |
| 创意与设计 | 海报与视觉设计 | canvas-design |
| 创意与设计 | Slack GIF 制作 | slack-gif-creator |
| 创意与设计 | 主题样式 | theme-factory |
| 企业与沟通 | 品牌规范 | brand-guidelines |
| 企业与沟通 | 内部沟通材料 | internal-comms |
| 企业与沟通 | 文档协作撰写 | doc-coauthoring |

 `academy-guide`、`discernment-nudge`。

## 其他来源

| 分类 | 功能 | 内容 | 来源 / 许可 |
|---|---|---|---|
| 开发流程 | AI 编码工程化工作流 | skills/(25 个 skill)、agents/(4 个角色)、references/(7 份检查清单,skill 会引用) | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills),MIT |
| 代码评审 | AI 代码评审 | open-code-review、open-code-review-delegate | [alibaba/open-code-review](https://github.com/alibaba/open-code-review),Apache-2.0 |
| 图表绘制 | draw.io 架构图与流程图 | drawio-skill | [Agents365-ai/drawio-skill](https://github.com/Agents365-ai/drawio-skill),MIT |

说明:
- 工程化工作流整体保留 `skills/`、`agents/`、`references/` 结构,避免 skill 引用的共享清单失效。使用时把 `skills/` 下需要的目录复制到 `~/.kiro/skills/`,并保留 `references/`。
- 代码评审需要先安装 `ocr` CLI:`npm install -g @alibaba-group/open-code-review`(需 Git >= 2.41)。委托模式不需要单独配置模型 key。

未收录 Anthropic 上游的 `academy-guide`、`discernment-nudge`。
