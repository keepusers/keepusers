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
| 2026-08-31 | Portable Agent Skill Library | local-skills-mcp + Codex/other agents | 把常用工作方法沉淀为 SKILL.md，一份技能库按需加载给不同 Agent，减少重复提示词和 Token | P0 | VALIDATE |
| 2026-08-31 | Lightweight Offline Knowledge Sidecar | nexus-local-rag-mcp + MarkItDown | 为小型项目目录提供无 Docker 的本地 RAG；复杂格式先转 Markdown，再由轻量 MCP 检索 | P1 | IDEA |
| 2026-08-31 | Push-to-Talk Agent Input | mcp-listen + Codex/MCP clients | 用本地麦克风+whisper.cpp 给 Agent 增加离线语音输入，与现有 TTS 项目组合成双向语音 | P0 | VALIDATE |

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
