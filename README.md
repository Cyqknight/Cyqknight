* 实现了 ReAct AgentLoop 和工具调用闭环
* 用 EventBus 把 Agent 执行过程外化成事件流
* 实现了 TUI 实时渲染、工具折叠块、权限审批卡片
* 实现了 Session、thread、notes 三层记忆体系
* 实现了上下文水位检测、tool_result 截断、自动 compact 和手动 compact
* 实现了 Skills、Subagents、MCP 外部工具接入
* 用 pytest、mypy strict、ruff 保证项目质量
* 实现了守护进程 + 多客户端架构
* 设计了 JSON-RPC 2.0 + NDJSON 的类型化 IPC 协议
