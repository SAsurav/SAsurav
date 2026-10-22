<p><strong>🎯 Focus on：不可控系统上的可靠性，和 LLM 输出的可验证性。</strong></p>

<p>2027 届计算机本科，现在在上海做会展业务的数字化实习。</p>

<h3>🛠 做过的系统</h3>

<p><strong>微信批量触达</strong> — 微信不提供群发接口，用 UIA 控件树 + 模拟输入做批量操作。<br>
单轮 500 人两轮全量送达，累计发送过万；13 人因名称歧义主动放弃——消息撤不回，宁可少发。</p>

<p><strong>领英获客流水线</strong> — Playwright 按地点 / 在职 / 职位三关，从 132 家公司产出 53 条线索。<br>
设计 50 条带标签用例回归规则，逐条核验后砍掉一条准确率仅 20% 的兜底逻辑。</p>

<p><strong>业务文档问答 Agent</strong> — 手写 agentic loop，3 个工具 + 三道终止条件，不依赖框架。<br>
38 条分层用例（含 7 条拒答负例）全部通过；加文档冲突检测规则后 4/6 → 6/6。</p>

<h3>📦 仓库</h3>

<table>
<tr><th align="left">仓库</th><th align="left">里面是什么</th></tr>
<tr><td><a href="https://github.com/SAsurav/agent-eval">agent-eval</a></td><td>问答 Agent 与抓取流水线的完整代码：工具循环、trace、分层评测</td></tr>
<tr><td><a href="https://github.com/SAsurav/wx-reliability">wx-reliability</a></td><td>微信批量触达的统计脚本与脱敏样例</td></tr>
</table>

<h3>🧰 技术栈</h3>

<p><code>Python</code> · <code>Playwright</code> · <code>Flask</code> · <code>BM25</code> · <code>DeepSeek API</code> · <code>Windows UI Automation</code></p>
