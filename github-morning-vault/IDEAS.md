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
