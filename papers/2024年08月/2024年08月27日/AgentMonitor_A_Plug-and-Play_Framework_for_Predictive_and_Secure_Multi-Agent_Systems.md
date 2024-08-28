# AgentMonitor：一款即插即用的框架，专为预测性和安全的多代理系统设计。

发布时间：2024年08月27日

`Agent` `软件开发` `网络安全`

> AgentMonitor: A Plug-and-Play Framework for Predictive and Secure Multi-Agent Systems

# 摘要

> 随着大型语言模型的飞速进步，基于LLM的代理系统应运而生。最新研究发现，分工明确的多代理系统能超越单一LLM的表现。但为特定任务配置MAS颇具挑战，且性能需在任务完成后才能评估。借鉴LLM发展中的规模法则，我们探索能否预先预测MAS的性能。为此，我们推出了AgentMonitor框架，该框架在代理层面整合，捕捉输入输出并转化为统计数据，训练回归模型以预判任务成效。同时，它还能实时修正，应对恶意代理带来的安全威胁，提升系统安全。实验显示，XGBoost模型在常规条件下相关性达0.89，在复杂场景下为0.58。此外，AgentMonitor平均降低6.2%有害内容，提升1.8%有益内容，显著增强系统的安全与可靠性。相关代码已公开于\url{https://github.com/chanchimin/AgentMonitor}。

> The rapid advancement of large language models (LLMs) has led to the rise of LLM-based agents. Recent research shows that multi-agent systems (MAS), where each agent plays a specific role, can outperform individual LLMs. However, configuring an MAS for a task remains challenging, with performance only observable post-execution. Inspired by scaling laws in LLM development, we investigate whether MAS performance can be predicted beforehand. We introduce AgentMonitor, a framework that integrates at the agent level to capture inputs and outputs, transforming them into statistics for training a regression model to predict task performance. Additionally, it can further apply real-time corrections to address security risks posed by malicious agents, mitigating negative impacts and enhancing MAS security. Experiments demonstrate that an XGBoost model achieves a Spearman correlation of 0.89 in-domain and 0.58 in more challenging scenarios. Furthermore, using AgentMonitor reduces harmful content by 6.2% and increases helpful content by 1.8% on average, enhancing safety and reliability. Code is available at \url{https://github.com/chanchimin/AgentMonitor}.

[Arxiv](https://arxiv.org/abs/2408.14972)