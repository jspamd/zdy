# AI 应用学习大纲

面向已经会写程序（默认 Python）、想自己做出大模型应用的人。学完能独立做对话、知识库问答，或带工具的助手。

这条路线不覆盖模型训练，也不覆盖论文向的机器学习。

## 进度怎么记

每课只有三种状态，勾选时只保留一项：

- `未开始`：还没看这课
- `进行中`：正在看要点或做练习
- `已完成`：要点看完，练习做完，自检项都勾上

规则：

- 一课完成：读完要点，并做完该课练习且自检通过。
- 一模块完成：该模块 3 课全部为「已完成」。
- 总进度：已完成课时数 / 全部课时数。全部共 24 课。

更新顺序：先改模块文档里该课的状态，再回到本页改清单和下面的数字。本页不会自动计数。

## 总进度

- 已完成：0 / 24
- 进行中：0
- 未开始：24

## 路线

```mermaid
flowchart LR
  m1[入门与第一次调用] --> m2[Prompt与输出控制]
  m2 --> m3[对话应用工程]
  m3 --> m4[工具调用]
  m4 --> m5[RAG知识库]
  m5 --> m6[Agent与工作流]
  m6 --> m7[评测安全与上线]
  m7 --> m8[综合项目]
```

按顺序学。前一模块的完成标准没达到时，先不要跳到后面把项目做大。

## 视频教程

视频用来对照课时。看完视频不等于课时完成，完成仍以该课练习的自检为准。

这些课来自 DeepLearning.AI 短课和 Andrej Karpathy 的公开演讲。官网是英文，页内有视频和可运行示例。B 站链接是同一门课的中文字幕转载，转载页失效时用官网课名再搜。短课里的模型名可能已经过时，调用方式以你现在的接口为准。

中文配套笔记（不是视频）：[Datawhale《面向开发者的 LLM 入门教程》](https://github.com/datawhalechina/llm-cookbook)。

| 模块 | 先看 |
| --- | --- |
| 1. 入门与第一次调用 | [Karpathy：Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g)（[B 站](https://www.bilibili.com/video/BV1NH4y1m78m/)）；[Building Systems with the ChatGPT API](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/) 的 Language Models, the Chat Format and Tokens（[B 站](https://www.bilibili.com/video/BV15N411k7bB/)） |
| 2. Prompt 与输出控制 | [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) 的 Guidelines、Iterative（[B 站全 9 集](https://www.bilibili.com/video/BV1mc411K7vB/)） |
| 3. 对话应用工程 | 上一门课的 Chatbot；Building Systems 的 Chaining Prompts；[LangChain for LLM Application Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/) 的 Memory（[B 站](https://www.bilibili.com/video/BV1gz421S73U/)） |
| 4. 工具调用 | [Functions, Tools and Agents with LangChain](https://www.deeplearning.ai/short-courses/functions-tools-agents-langchain/) 的 OpenAI Function Calling、Tools and Routing（[B 站](https://www.bilibili.com/video/BV1im421u7iv/)） |
| 5. RAG 知识库 | [LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/)（[B 站](https://www.bilibili.com/video/BV148411D7d2/)）；选看 [Building and Evaluating Advanced RAG](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/) 的 RAG Triad |
| 6. Agent 与工作流 | Building Systems 的 Chaining Prompts；[AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) 的 Build an Agent from Scratch（[B 站](https://www.bilibili.com/video/BV1bi421v7oD/)） |
| 7. 评测、安全与上线 | Building Systems 的 Evaluation；[Red Teaming LLM Applications](https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/)；[Building Generative AI Applications with Gradio](https://www.deeplearning.ai/short-courses/building-generative-ai-applications-with-gradio/) 的文本界面 |
| 8. 综合项目 | 只看和你选题对应的那一门收尾，不要三门都刷完再动手 |

每一课看哪一集，写在对应模块文档的「视频教程」一节。

## 模块与课时

### [1. 入门与第一次调用](modules/01-入门与第一次调用.md)

状态：未开始

- [ ] [1.1 应用地图](modules/01-入门与第一次调用.md#1-1)（未开始）
- [ ] [1.2 Token、上下文窗口、温度、费用](modules/01-入门与第一次调用.md#1-2)（未开始）
- [ ] [1.3 环境与第一次调用](modules/01-入门与第一次调用.md#1-3)（未开始）

### [2. Prompt 与输出控制](modules/02-prompt与输出控制.md)

状态：未开始

- [ ] [2.1 四段式提示](modules/02-prompt与输出控制.md#2-1)（未开始）
- [ ] [2.2 少样本与格式约束](modules/02-prompt与输出控制.md#2-2)（未开始）
- [ ] [2.3 失败样例改写](modules/02-prompt与输出控制.md#2-3)（未开始）

### [3. 对话应用工程](modules/03-对话应用工程.md)

状态：未开始

- [ ] [3.1 消息角色与历史](modules/03-对话应用工程.md#3-1)（未开始）
- [ ] [3.2 流式输出、超时、重试、限流](modules/03-对话应用工程.md#3-2)（未开始）
- [ ] [3.3 会话状态与日志](modules/03-对话应用工程.md#3-3)（未开始）

### [4. 工具调用](modules/04-工具调用.md)

状态：未开始

- [ ] [4.1 什么时候该用工具](modules/04-工具调用.md#4-1)（未开始）
- [ ] [4.2 工具描述、参数与回填](modules/04-工具调用.md#4-2)（未开始）
- [ ] [4.3 失败与越权](modules/04-工具调用.md#4-3)（未开始）

### [5. RAG 知识库](modules/05-rag知识库.md)

状态：未开始

- [ ] [5.1 切分、嵌入与召回](modules/05-rag知识库.md#5-1)（未开始）
- [ ] [5.2 提问改写、Top-K 与引用](modules/05-rag知识库.md#5-2)（未开始）
- [ ] [5.3 答不出就拒答](modules/05-rag知识库.md#5-3)（未开始）

### [6. Agent 与工作流](modules/06-agent与工作流.md)

状态：未开始

- [ ] [6.1 工作流](modules/06-agent与工作流.md#6-1)（未开始）
- [ ] [6.2 Agent 循环与步数上限](modules/06-agent与工作流.md#6-2)（未开始）
- [ ] [6.3 本次记忆与长期记忆](modules/06-agent与工作流.md#6-3)（未开始）

### [7. 评测、安全与上线](modules/07-评测安全与上线.md)

状态：未开始

- [ ] [7.1 固定用例](modules/07-评测安全与上线.md#7-1)（未开始）
- [ ] [7.2 提示注入与数据外泄](modules/07-评测安全与上线.md#7-2)（未开始）
- [ ] [7.3 最小上线](modules/07-评测安全与上线.md#7-3)（未开始）

### [8. 综合项目](modules/08-综合项目.md)

状态：未开始

- [ ] [8.1 选定项目并写清输入输出](modules/08-综合项目.md#8-1)（未开始）
- [ ] [8.2 接上外部能力并准备用例](modules/08-综合项目.md#8-2)（未开始）
- [ ] [8.3 换机运行并演示](modules/08-综合项目.md#8-3)（未开始）
