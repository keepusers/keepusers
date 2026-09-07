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
| 2026-09-04 | Codex Agent Rack | agent-rack + Codex | Codex 做 leader，将实现、测试、审查分派给可后台运行和取消的 CLI 子 Agent | P0 | VALIDATE |
| 2026-09-04 | Model Council Gate | model-council-mcp-codex + local/cloud models | 重要技术决策或研究结论先经过多模型独立判断、冲突显式化，再由 Codex 汇总 | P0 | VALIDATE |
| 2026-09-04 | Generative SFX Layer | mcp-soundfx + Reaper-MCP/OpenChatCut | 给 AI Video Factory 增加本地 SFX 生成，再进入 REAPER/视频后期 | P1 | IDEA |
| 2026-09-05 | Codex Browser QA Loop | ChromeDevTools/chrome-devtools-mcp + Codex | Codex 修改 Web 项目后自动基于 console、network、performance trace 做真实浏览器验证与回归修复 | P0 | VALIDATE |
| 2026-09-05 | Agent Skill Governance Layer | agentic-awesome-skills + local-skills-mcp + Codex | 私有 Skill 与公共 catalog 分层管理，并用项目级 aas-stack.json 固化可审查的最小技能组合 | P1 | IDEA |
| 2026-09-05 | Audio QC Intelligence Layer | audio-sonic-mcp + RVC + Reaper-MCP | 对原曲、转换人声和最终混音生成 sonic signature，用客观差异辅助 Codex 定位需要人工试听和修复的片段 | P1 | IDEA |
| 2026-09-06 | Codex Harness Bake-off | lazycodex + existing Codex harness tools | 用固定真实任务比较裸 Codex、LazyCodex 与模块化组合的计划质量、完成率、返工、验证证据和额度消耗，只保留有效 Harness | P0 | VALIDATE |
| 2026-09-06 | Cross-Agent Session Memory | agent-lcm + ai-memory + gno | 将项目事实知识与 Agent 会话/决策历史分层存储，让 Codex 跨 Session、跨 Harness 按证据恢复上下文 | P0 | VALIDATE |
| 2026-09-06 | Codex Quality Gate Skill | noobnooc/agent + local-skills-mcp | 抽取根因修复、范围控制、测试、secrets/env/deployment 检查，形成自己的任务完成前质量门禁 Skill | P1 | IDEA |
| 2026-09-07 | Local Agent Runtime Stack | LocalAI + LocalAGI + MCP + Codex | LocalAI 负责本地模型/多模态推理，LocalAGI 负责 Agent 生命周期与 MCP 编排，Codex 作为高层开发与操作入口；先验证单 Agent 最小闭环 | P0 | VALIDATE |
| 2026-09-07 | Meeting-to-Project Memory | Loqui + gno + Codex | 会议转录/摘要作为只读历史，确认后的 action item 与技术决策再进入项目知识库，分离口语记录与项目事实 | P1 | IDEA |
| 2026-09-07 | Agent Efficiency Benchmark | Caveman + Ratel Local + Codex Harness Bake-off | 在 Harness 对比中加入输入/输出 Token、完成时间、返工次数与最终通过率，衡量单位有效成果成本 | P1 | IDEA |

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