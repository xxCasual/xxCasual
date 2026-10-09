# 你好，我是黄向楠（xxCasual）

五邑大学计算机科学与技术专业 **2027 届本科生**，关注 **AI Agent、大模型应用与 Python 后端开发**。有 AI 智能体开发实习经历，参与智能标书助手的 Dify 工作流、后端接口及模型接入开发。喜欢把模型能力做成可运行、可验证的应用，重视工具调用、任务恢复、检索评测与工程交付。

## 简历项目

以下两个项目均为独立开发，与简历中的项目名称一一对应。

| 简历项目 | 代码仓库 | 核心能力 |
| --- | --- | --- |
| **Coding Agent 编程智能体** | [coding-agent](https://github.com/xxCasual/coding-agent) | 在独立工作副本中修改代码、执行测试与审查后交付补丁；支持开发 / 审查 / 规划、人工审批、断点续跑及 CLI / Web 入口。 |
| **劳动合规 RAG 与合同审查系统** | [Enterprise_Legal_RAG_Agent](https://github.com/xxCasual/Enterprise_Legal_RAG_Agent) | 法律与企业制度双知识库，BM25 + 向量混合检索、问答路由、合同风险提示与人工复核，支持异步文档索引及 Docker Compose 部署。 |

**主要技术：** Python · FastAPI · LangGraph · Dify · MCP · PostgreSQL · Redis · Celery · LlamaIndex · Chroma · Docker

项目的运行方式、验证记录与当前边界，请查看各仓库 README。

<details>
<summary>项目迭代关系</summary>

- `coding-agent` 由早期 PR 审查 Agent 项目重构演进，当前编程智能体以此仓库为入口。
- `Enterprise_Legal_RAG_Agent` 是基于 LangGraph / LlamaIndex 的重构版本；`legal-rag-system` 保留早期 LangChain 原型及历史 RAGAS 评测记录。简历中的历史检索指标来自该原型，具体口径见主项目 README。

</details>
