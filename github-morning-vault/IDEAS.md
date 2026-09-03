# Idea Bank

从每日 GitHub 晨报项目中提炼出的可执行想法。

| 日期 | Idea | 来源项目 | 可执行方向 | 优先级 | 状态 |
|---|---|---|---|---|---|
| 2026-08-26 | Codex Persistent Workspace | akitaonrails/ai-memory | 给 Codex 项目增加跨 Session 记忆、决策记录、失败方案与自动 handoff | P0 | VALIDATE |
| 2026-08-26 | Local Multimodal Hub | mudler/LocalAI | 用统一 API 把本地 LLM、TTS、声音克隆、图像和视频接给 Codex | P0 | VALIDATE |
| 2026-08-26 | Document-to-Codex Pipeline | microsoft/markitdown | PDF/PPT/Word 批量转 Markdown，再生成目录、摘要和 Codex 输入包以降低 Token | P0 | VALIDATE |
| 2026-08-26 | AI Video Factory | MoneyPrinterTurbo + ComfyUI + LocalAI | 组合脚本、图像/视频、声音克隆、字幕和 FFmpeg，形成本地短视频流水线 | P1 | IDEA |
| 2026-08-27 | Codex Local Knowledge MCP | gmickel/gno | 建立本地资料索引并通过 MCP 暴露给 Codex | P0 | VALIDATE |
| 2026-08-27 | Visual Document Preprocessor | magicrew/doc7 + markitdown | 普通文件走 MarkItDown，复杂扫描件/图表/公式切到 doc7 | P0 | VALIDATE |
| 2026-08-27 | Local Dubbing Workbench | LA-Studio + LocalAI/voice models | 串联转录、翻译、声音克隆、配音和混音 | P1 | IDEA |
| 2026-08-28 | Voice-Enabled Codex | voicesmith-mcp + Codex | 给 Codex 增加本地语音输入与反馈 | P0 | VALIDATE |
| 2026-08-28 | Agent-Native Video Editor | openchatcut + Codex + AI Video Factory | 让 Codex 接管可编辑多轨时间线 | P0 | VALIDATE |
| 2026-08-28 | Modular Voice Production Stack | voice-mcp-agent + LocalAI/LA-Studio | 抽象 STT、TTS、克隆、MCP 四层接口 | P1 | IDEA |
| 2026-08-29 | Durable Codex Worker | codex-control-plane-mcp + Codex Desktop | 将耗时任务改造成持久工作流 | P0 | VALIDATE |
| 2026-08-29 | Codex Music Producer | Resonant + Codex MCP + voice stack | 用 Codex 驱动歌曲生成、编曲、混音和导出 | P0 | VALIDATE |
| 2026-08-29 | Local Agent Team Blueprint | Heddle + Codex | 抽取多 Agent 团队、隔离执行和 trace 机制 | P1 | IDEA |
| 2026-08-30 | Multi-Agent Coding Bus | concord-mcp + Codex | 让不同编码 Agent 通过统一协调层分工、共享决策并完成任务交接 | P0 | VALIDATE |
| 2026-08-30 | Video RAG for Codex | video-context-mcp + local knowledge | 让 Codex 按时间戳检索教程、会议和素材视频，只提取需要的证据 | P0 | VALIDATE |
| 2026-08-30 | Headless Video Post-Processor | kinocut + AI Video Factory | 用 MCP/CLI 统一承担批量裁剪、转码、字幕、质量检查和交付 | P1 | IDEA |
| 2026-08-31 | Portable Agent Skill Library | local-skills-mcp + Codex/other agents | 把常用工作方法沉淀为 SKILL.md，一份技能库按需加载给不同 Agent | P0 | VALIDATE |
| 2026-08-31 | Lightweight Offline Knowledge Sidecar | nexus-local-rag-mcp + MarkItDown | 为小型项目目录提供无 Docker 的本地 RAG | P1 | IDEA |
| 2026-08-31 | Push-to-Talk Agent Input | mcp-listen + Codex/MCP clients | 用本地麦克风+whisper.cpp 给 Agent 增加离线语音输入 | P0 | VALIDATE |
| 2026-09-01 | MCP Context Router | ratel-local + local-skills-mcp + Codex | 多 MCP 工具改为按需检索和加载，降低上下文成本 | P0 | VALIDATE |
| 2026-09-01 | Codex ComfyUI Control Plane | comfy-mcp + ComfyUI + Codex | 让 Codex 直接构建、运行和监控本地图像视频 workflow | P0 | VALIDATE |
| 2026-09-01 | Media-to-Knowledge Router | hearsay + video-context-mcp + gno | 按媒体类型选择 Markdown 转写或保留视觉证据的 Video RAG | P1 | IDEA |
| 2026-09-02 | Codex-to-REAPER Production Bridge | Reaper-MCP + Codex + RVC/voice stack | 让 Codex 直接承担 REAPER 工程中的轨道管理、FX、局部处理、混音和 QC，人工保留最终听感判断 | P0 | VALIDATE |
| 2026-09-02 | Codex Native Video Workspace | codex-code-video-toolkit + ComfyUI/OpenChatCut | 用 Skills/模板把脚本、素材生成、配音、音乐和渲染组织成 Codex 原生视频项目目录 | P0 | VALIDATE |
| 2026-09-02 | Token-Efficient Codebase Map | codegraph + Codex | 对大型代码库建立持续同步的本地代码图谱，优先返回结构关系再读取少量源码 | P1 | IDEA |
| 2026-09-03 | Codex Research Workbench | academic-research-skills-codex + MarkItDown/doc7 + gno | 把资料预处理、本地检索、研究流程、来源核验和论文输出组织成 Codex 原生研究工作台 | P0 | VALIDATE |
| 2026-09-03 | GitHub Automation Backbone | github-mcp-server + Codex + Morning Vault | 将仓库读取、Issue/PR 操作和晨报归档逐步统一到 GitHub 官方 MCP 接口 | P1 | IDEA |
| 2026-09-03 | Code Graph Bake-off | graphify + codegraph | 用固定代码库建立索引速度、关系准确率、增量更新和 Token 消耗基准，选择单一长期图谱底座 | P1 | IDEA |

## 优先级
- P0：立即值得尝试
- P1：近期研究
- P2：长期储备

## 状态
- IDEA：仅记录
- VALIDATE：需要验证
- BUILD：准备实现
- DONE：已落地
- ARCHIVE：归档