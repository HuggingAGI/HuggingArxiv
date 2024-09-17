# HALO：通过幻觉分析与学习优化，为 LLM 注入检索增强的上下文，助力临床决策的精准引导。

发布时间：2024年09月16日

`LLM应用` `人工智能`

> HALO: Hallucination Analysis and Learning Optimization to Empower LLMs with Retrieval-Augmented Context for Guided Clinical Decision Making

# 摘要

> 大型语言模型（LLM）在自然语言处理方面取得了巨大进步，但它们容易产生不准确或不可靠的回答，这种现象被称为“幻觉”。在医疗等关键领域，这种幻觉可能带来严重风险。为此，我们推出了 HALO 框架，通过检测和缓解幻觉，显著提升医疗问答系统的准确性和可靠性。HALO 利用 LLM 生成查询的多种变体，并从外部知识库中检索相关信息，丰富上下文。通过最大边际相关性评分，优先处理检索到的信息，再由 LLM 生成答案，从而降低幻觉风险。LangChain 的集成进一步优化了这一流程，使得 Llama-3.1 和 ChatGPT 等模型的准确性大幅提升（Llama-3.1 从 44% 提升至 65%，ChatGPT 从 56% 提升至 70%）。HALO 框架凸显了在医疗问答系统中解决幻觉问题的重要性，最终有助于改善临床决策和患者护理。HALO 已开源，可在 https://github.com/ResponsibleAILab/HALO 获取。

> Large language models (LLMs) have significantly advanced natural language processing tasks, yet they are susceptible to generating inaccurate or unreliable responses, a phenomenon known as hallucination. In critical domains such as health and medicine, these hallucinations can pose serious risks. This paper introduces HALO, a novel framework designed to enhance the accuracy and reliability of medical question-answering (QA) systems by focusing on the detection and mitigation of hallucinations. Our approach generates multiple variations of a given query using LLMs and retrieves relevant information from external open knowledge bases to enrich the context. We utilize maximum marginal relevance scoring to prioritize the retrieved context, which is then provided to LLMs for answer generation, thereby reducing the risk of hallucinations. The integration of LangChain further streamlines this process, resulting in a notable and robust increase in the accuracy of both open-source and commercial LLMs, such as Llama-3.1 (from 44% to 65%) and ChatGPT (from 56% to 70%). This framework underscores the critical importance of addressing hallucinations in medical QA systems, ultimately improving clinical decision-making and patient care. The open-source HALO is available at: https://github.com/ResponsibleAILab/HALO.

[Arxiv](https://arxiv.org/abs/2409.10011)