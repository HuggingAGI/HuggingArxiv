# 提升大型语言模型对外部环境的适应性与准确性

发布时间：2024年10月18日

`LLM应用` `问答系统` `人工智能`

> Enhancing Large Language Models' Situated Faithfulness to External Contexts

# 摘要

> 大型语言模型 (LLM) 常借助外部信息增强上下文，但这些信息有时可能不准确或有意误导。我们主张，稳健的 LLM 应具备情境忠诚度，根据内部知识和外部上下文的信心，动态调整对外部信息的信任。为此，我们在多个 QA 数据集上评估了 LLM，包括新创的 RedditQA 数据集，该数据集包含从 Reddit 帖子中提取的野外不正确上下文。结果显示，无论上下文正确与否，模型都倾向于过度依赖外部信息。为提升情境忠诚度，我们提出了两种方法：自我引导的信心推理 (SCR) 和基于规则的信心推理 (RCR)。SCR 使模型能根据内部知识评估外部信息的信心，从而给出最准确的答案；而 RCR 则从 LLM 中提取信心信号，并按预设规则确定答案。实验表明，对于推理能力强的 LLM 如 GPT-4o，SCR 表现优于 RCR，性能提升高达 24.2%。而对于较小模型如 Llama-3-8B，RCR 表现更佳。通过我们提出的 CR-DPO 方法微调 SCR，可在已见和未见数据集上提升性能，Llama-3-8B 平均改进率达 8.9%。此外，我们还探讨了 SCR 和 RCR 的相对优势。研究结果为提升 LLM 情境忠诚度指明了方向。数据和代码已公开。

> Large Language Models (LLMs) are often augmented with external information as contexts, but this external information can sometimes be inaccurate or even intentionally misleading. We argue that robust LLMs should demonstrate situated faithfulness, dynamically calibrating their trust in external information based on their confidence in the internal knowledge and the external context. To benchmark this capability, we evaluate LLMs across several QA datasets, including a newly created dataset called RedditQA featuring in-the-wild incorrect contexts sourced from Reddit posts. We show that when provided with both correct and incorrect contexts, both open-source and proprietary models tend to overly rely on external information, regardless of its factual accuracy. To enhance situated faithfulness, we propose two approaches: Self-Guided Confidence Reasoning (SCR) and Rule-Based Confidence Reasoning (RCR). SCR enables models to self-access the confidence of external information relative to their own internal knowledge to produce the most accurate answer. RCR, in contrast, extracts explicit confidence signals from the LLM and determines the final answer using predefined rules. Our results show that for LLMs with strong reasoning capabilities, such as GPT-4o and GPT-4o mini, SCR outperforms RCR, achieving improvements of up to 24.2% over a direct input augmentation baseline. Conversely, for a smaller model like Llama-3-8B, RCR outperforms SCR. Fine-tuning SCR with our proposed Confidence Reasoning Direct Preference Optimization (CR-DPO) method improves performance on both seen and unseen datasets, yielding an average improvement of 8.9% on Llama-3-8B. In addition to quantitative results, we offer insights into the relative strengths of SCR and RCR. Our findings highlight promising avenues for improving situated faithfulness in LLMs. The data and code are released.

[Arxiv](https://arxiv.org/abs/2410.14675)