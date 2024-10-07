# ALR$^2$：一种专为长上下文问答设计的“先检索后推理”框架

发布时间：2024年10月04日

`LLM应用` `人工智能` `问答系统`

> ALR$^2$: A Retrieve-then-Reason Framework for Long-context Question Answering

# 摘要

> 近年来，大型语言模型（LLM）的上下文窗口大幅扩展，但模型在长上下文中的推理能力却显著下降。这是因为现代LLM在处理海量信息时，难以准确提取并推理相关证据。为此，我们设计了一个“先检索后推理”的框架，帮助LLM在检索到的相关证据上进行推理。然而，我们发现LLM在检索过程中常出现“幻觉性事实”，导致推理错误。为此，我们提出了ALR$^2$，通过两阶段过程增强LLM的长上下文推理能力。实验结果显示，ALR$^2$在长上下文QA任务中显著提升了性能，分别在HotpotQA和SQuAD数据集上提高了8.4和7.9的EM得分，远超现有基线。

> The context window of large language models (LLMs) has been extended significantly in recent years. However, while the context length that the LLM can process has grown, the capability of the model to accurately reason over that context degrades noticeably. This occurs because modern LLMs often become overwhelmed by the vast amount of information in the context; when answering questions, the model must identify and reason over relevant evidence sparsely distributed throughout the text. To alleviate the challenge of long-context reasoning, we develop a retrieve-then-reason framework, enabling LLMs to reason over relevant evidence collected during an intermediate retrieval step. We find that modern LLMs struggle to accurately retrieve relevant facts and instead, often hallucinate "retrieved facts", resulting in flawed reasoning and the production of incorrect answers. To address these issues, we introduce ALR$^2$, a method that augments the long-context reasoning capability of LLMs via an explicit two-stage procedure, i.e., aligning LLMs with the objectives of both retrieval and reasoning. We demonstrate the efficacy of ALR$^2$ for mitigating performance degradation in long-context reasoning tasks. Through extensive experiments on long-context QA benchmarks, we find our method to outperform competitive baselines by large margins, achieving at least 8.4 and 7.9 EM gains on the long-context versions of HotpotQA and SQuAD datasets, respectively.

[Arxiv](https://arxiv.org/abs/2410.03227)