## 赵圣

Focus on：不可控系统上的可靠性，和 LLM 输出的可验证性。

2027 届计算机本科，现在在上海做会展业务的数字化实习。

### 做过的系统

**微信批量触达** — 微信不提供群发接口，用 UIA 控件树 + 模拟输入做批量操作。
单轮 500 人两轮全量送达，累计发送过万；13 人因名称歧义主动放弃——消息撤不回，宁可少发。

**领英获客流水线** — Playwright 按地点 / 在职 / 职位三关，从 132 家公司产出 53 条线索。
设计 50 条带标签用例回归规则，逐条核验后砍掉一条准确率仅 20% 的兜底逻辑。

**业务文档问答 Agent** — 手写 agentic loop，3 个工具 + 三道终止条件，不依赖框架。
38 条分层用例（含 7 条拒答负例）全部通过；加文档冲突检测规则后 4/6 → 6/6。

### 仓库

| 仓库 | 里面是什么 |
| --- | --- |
| [agent-eval](https://github.com/SAsurav/agent-eval) | 问答 Agent 与抓取流水线的完整代码：工具循环、trace、分层评测 |
| [wx-reliability](https://github.com/SAsurav/wx-reliability) | 微信批量触达的统计脚本与脱敏样例 |

### 技术栈

`Python` · `Playwright` · `Flask` · `BM25` · `DeepSeek API` · `Windows UI Automation`

2250202697@qq.com
