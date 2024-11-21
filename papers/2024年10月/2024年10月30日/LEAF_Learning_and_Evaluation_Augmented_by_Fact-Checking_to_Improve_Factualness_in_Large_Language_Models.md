# LEAF：借助事实核查来增强学习与评估，以提升大型语言模型中的事实准确性

发布时间：2024年10月30日

`LLM应用`

> LEAF: Learning and Evaluation Augmented by Fact-Checking to Improve Factualness in Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类自然语言处理任务中表现出色，然而在保持事实准确性上常遇难题，尤其在医疗保健这类知识密集型领域。本研究推出 LEAF：基于事实核查的学习与评估增强，这是一种致力于提升 LLMs 事实可靠性的新方法，重点聚焦于医疗问答（QA）。LEAF 采用双重策略来增强诸如 Llama 3 70B Instruct 和 Llama 3 8B Instruct 等模型回答的事实准确性。第一种策略“事实核查然后 RAG”，将事实核查结果融入其中以改进检索增强生成（RAG），从而引导检索流程，且不更新模型参数。第二种策略“通过自训练从事实核查中学习”，包含对经事实核查的回答进行有监督微调（SFT），或者把事实核查当作排名机制应用简单偏好优化（SimPO），二者均通过监督来更新 LLM 参数。这些研究结果表明，不管是通过 RAG 增强还是自训练来整合经过事实核查的回答，都能提升 LLM 输出的可靠性和事实准确性，为信息准确性至关重要的应用提供了颇具前景的解决方案。

> Large language models (LLMs) have shown remarkable capabilities in various natural language processing tasks, yet they often struggle with maintaining factual accuracy, particularly in knowledge-intensive domains like healthcare. This study introduces LEAF: Learning and Evaluation Augmented by Fact-Checking, a novel approach designed to enhance the factual reliability of LLMs, with a focus on medical question answering (QA). LEAF utilizes a dual strategy to enhance the factual accuracy of responses from models such as Llama 3 70B Instruct and Llama 3 8B Instruct. The first strategy, Fact-Check-Then-RAG, improves Retrieval-Augmented Generation (RAG) by incorporating fact-checking results to guide the retrieval process without updating model parameters. The second strategy, Learning from Fact-Checks via Self-Training, involves supervised fine-tuning (SFT) on fact-checked responses or applying Simple Preference Optimization (SimPO) with fact-checking as a ranking mechanism, both updating LLM parameters from supervision. These findings suggest that integrating fact-checked responses whether through RAG enhancement or self-training enhances the reliability and factual correctness of LLM outputs, offering a promising solution for applications where information accuracy is crucial.

[Arxiv](https://arxiv.org/abs/2410.23526)