# 利用大型语言模型，从文本政策中生成健康保险的智能合约

发布时间：2024年07月09日

`LLM应用` `区块链`

> Using Large Language Models for Generating Smart Contracts for Health Insurance from Textual Policies

# 摘要

> 我们利用大型语言模型 (LLM) 从文本保险政策中自动生成健康保险流程的应用代码。选择基于区块链的智能合约，因其具备不可变性、可验证性、可扩展性和无需信任的特性。我们的方法分三个层次生成输出：(1) 文本摘要，(2) 声明性决策逻辑，(3) 带单元测试的智能合约代码。LLM 在生成文本摘要方面表现优异，结构化输出对后续验证任务至关重要。声明性语言常用于医疗政策形式化，但在区块链上执行复杂。我们尝试通过智能合约直接自动化流程。评估指标包括完整性、正确性、清晰度、语法和功能代码。实验采用三种难度递增的保险政策场景，涉及多种模型。结果显示，尽管 LLM 在生成摘要方面表现出色，但后续任务仍需人工监督，且复杂场景的挑战依然存在。实验证明了 LLM 在将文本流程转化为智能合约方面的潜力。

> We explore using Large Language Models (LLMs) to generate application code that automates health insurance processes from text-based policies. We target blockchain-based smart contracts as they offer immutability, verifiability, scalability, and a trustless setting: any number of parties can use the smart contracts, and they need not have previously established trust relationships with each other. Our methodology generates outputs at increasing levels of technical detail: (1) textual summaries, (2) declarative decision logic, and (3) smart contract code with unit tests. We ascertain LLMs are good at the task (1), and the structured output is useful to validate tasks (2) and (3). Declarative languages (task 2) are often used to formalize healthcare policies, but their execution on blockchain is non-trivial. Hence, task (3) attempts to directly automate the process using smart contracts. To assess the LLM output, we propose completeness, soundness, clarity, syntax, and functioning code as metrics. Our evaluation employs three health insurance policies (scenarios) with increasing difficulty from Medicare's official booklet. Our evaluation uses GPT-3.5 Turbo, GPT-3.5 Turbo 16K, GPT-4, GPT-4 Turbo and CodeLLaMA. Our findings confirm that LLMs perform quite well in generating textual summaries. Although outputs from tasks (2)-(3) are useful starting points, they require human oversight: in multiple cases, even "runnable" code will not yield sound results; the popularity of the target language affects the output quality; and more complex scenarios still seem a bridge too far. Nevertheless, our experiments demonstrate the promise of LLMs for translating textual process descriptions into smart contracts.

[Arxiv](https://arxiv.org/abs/2407.07019)