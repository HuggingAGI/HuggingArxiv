# 延误条件下，基于提示优化的大语言模型助力地铁乘客流量精准预测

发布时间：2024年10月19日

`LLM应用` `应急管理`

> A Prompt Refinement-based Large Language Model for Metro Passenger Flow Forecasting under Delay Conditions

# 摘要

> 在地铁延误情况下，准确预测短期乘客流量对应急响应和服务恢复至关重要，但这一领域研究尚浅，充满挑战。由于延误事件罕见，样本量有限，传统模型难以捕捉其对乘客流量的复杂影响，预测精度低。我们利用大型语言模型（LLM）在少样本学习中的优势，提出了一种结合LLM和精心设计提示工程的乘客流量预测框架。通过优化提示设计，LLM能理解延误信息和历史流量模式，克服预测难题。框架包括系统提示生成和优化两个阶段，使用多维度思维链（CoT）方法优化提示。实验证明，该模型在深圳地铁延误条件下的乘客流量预测中表现优异。

> Accurate short-term forecasts of passenger flow in metro systems under delay conditions are crucial for emergency response and service recovery, which pose significant challenges and are currently under-researched. Due to the rare occurrence of delay events, the limited sample size under delay condictions make it difficult for conventional models to effectively capture the complex impacts of delays on passenger flow, resulting in low forecasting accuracy. Recognizing the strengths of large language models (LLMs) in few-shot learning due to their powerful pre-training, contextual understanding, ability to perform zero-shot and few-shot reasoning, to address the issues that effectively generalize and adapt with minimal data, we propose a passenger flow forecasting framework under delay conditions that synthesizes an LLM with carefully designed prompt engineering. By Refining prompt design, we enable the LLM to understand delay event information and the pattern from historical passenger flow data, thus overcoming the challenges of passenger flow forecasting under delay conditions. The propmpt engineering in the framework consists of two main stages: systematic prompt generation and prompt refinement. In the prompt generation stage, multi-source data is transformed into descriptive texts understandable by the LLM and stored. In the prompt refinement stage, we employ the multidimensional Chain of Thought (CoT) method to refine the prompts. We verify the proposed framework by conducting experiments using real-world datasets specifically targeting passenger flow forecasting under delay conditions of Shenzhen metro in China. The experimental results demonstrate that the proposed model performs particularly well in forecasting passenger flow under delay conditions.

[Arxiv](https://arxiv.org/abs/2410.15111)