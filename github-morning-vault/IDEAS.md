# Idea Bank

从每日 GitHub 晨报项目中提炼出的可执行想法。

| 日期 | Idea | 来源项目 | 可执行方向 | 优先级 | 状态 |
|---|---|---|---|---|---|
| 2026-08-26 | Codex Persistent Workspace | akitaonrails/ai-memory | 给 Codex 项目增加跨 Session 记忆、决策记录、失败方案与自动 handoff | P0 | VALIDATE |
| 2026-08-26 | Local Multimodal Hub | mudler/LocalAI | 用统一 API 把本地 LLM、TTS、声音克隆、图像和视频接给 Codex | P0 | VALIDATE |
| 2026-08-26 | Document-to-Codex Pipeline | microsoft/markitdown | PDF/PPT/Word 批量转 Markdown，再生成目录、摘要和 Codex 输入包以降低 Token | P0 | VALIDATE |
| 2026-08-26 | AI Video Factory | MoneyPrinterTurbo + ComfyUI + LocalAI | 组合脚本、图像/视频、声音克隆、字幕和 FFmpeg，形成本地短视频流水线 | P1 | IDEA |
| 2026-08-27 | Codex Local Knowledge MCP | gmickel/gno | 建立本地资料索引并通过 MCP 暴露给 Codex，使项目文档、代码和笔记可低成本检索 | P0 | VALIDATE |
| 2026-08-27 | Visual Document Preprocessor | magicrew/doc7 + markitdown | 普通 Office/PDF 先走 MarkItDown，复杂扫描件/图表/公式切到 doc7，形成分层文档预处理管线 | P0 | VALIDATE |
| 2026-08-27 | Local Dubbing Workbench | LA-Studio + LocalAI/voice models | 把转录、翻译、声音克隆、配音和混音串成完全本地的视频翻译/配音流程 | P1 | IDEA |
| 2026-08-28 | Voice-Enabled Codex | voicesmith-mcp + Codex | 给 Codex 增加本地语音输入与语音反馈，形成无需云语音 API 的开发交互模式 | P0 | VALIDATE |
| 2026-08-28 | Agent-Native Video Editor | openchatcut + Codex + AI Video Factory | 让 Codex 接管可编辑多轨时间线，把已有脚本/素材生成流水线与真正的视频后期工程连接起来 | P0 | VALIDATE |
| 2026-08-28 | Modular Voice Production Stack | voice-mcp-agent + LocalAI/LA-Studio | 对比并抽象 STT、TTS、克隆、MCP 四层接口，避免声音工作流绑定单一软件 | P1 | IDEA |
| 2026-08-29 | Durable Codex Worker | codex-control-plane-mcp + Codex Desktop | 将耗时任务改造成 submit→poll→approval→report 的持久工作流，支持中断恢复和自动化调度 | P0 | VALIDATE |
| 2026-08-29 | Codex Music Producer | Resonant + Codex MCP + voice stack | 用 Codex 驱动歌曲生成、编曲、混音和导出，再接声音克隆/REAPER 做精修 | P0 | VALIDATE |
| 2026-08-29 | Local Agent Team Blueprint | Heddle + Codex | 抽取 leader/reviewer/worker、YAML flow、隔离执行和 trace 机制，形成自己的 Codex 多 Agent 模板 | P1 | IDEA |

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
