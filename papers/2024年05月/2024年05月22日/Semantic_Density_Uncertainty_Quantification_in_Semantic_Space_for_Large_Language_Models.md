# 语义空间中的不确定性量化：探究大型语言模型的语义密度

发布时间：2024年05月22日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在生成响应时的不确定性量化问题，并提出了一种新的框架——语义密度，用于从语义空间的概率分布角度提取每个响应的不确定性信息。这一研究不仅限于特定的任务类型，也不依赖于额外的训练和数据，且适用于新模型和任务。因此，这项工作更偏向于LLM的理论研究，特别是在不确定性量化方面的理论创新。` `人工智能` `问答系统`

> Semantic Density: Uncertainty Quantification in Semantic Space for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在多领域的广泛应用，其不可预测的幻觉和错误信息生成引发了在安全关键场景中对其可信度的担忧。现有LLMs缺乏为每个响应提供不确定性度量的内置功能，使得可信度评估变得复杂。尽管已有研究致力于开发LLMs的不确定性量化方法，但这些方法存在局限，如仅适用于分类任务、需额外训练和数据、仅考虑词汇而非语义信息，且仅针对提示而非响应。本文提出了一种新框架——语义密度，它从语义空间的概率分布角度提取每个响应的不确定性信息，不受任务类型限制，适用于新模型和任务。在四个自由形式的问答基准上，对包括最新Llama 3和Mixtral-8x22B在内的七种顶级LLMs的实验显示，语义密度在性能和鲁棒性上均优于先前方法。

> With the widespread application of Large Language Models (LLMs) to various domains, concerns regarding the trustworthiness of LLMs in safety-critical scenarios have been raised, due to their unpredictable tendency to hallucinate and generate misinformation. Existing LLMs do not have an inherent functionality to provide the users with an uncertainty metric for each response it generates, making it difficult to evaluate trustworthiness. Although a number of works aim to develop uncertainty quantification methods for LLMs, they have fundamental limitations, such as being restricted to classification tasks, requiring additional training and data, considering only lexical instead of semantic information, and being prompt-wise but not response-wise. A new framework is proposed in this paper to address these issues. Semantic density extracts uncertainty information for each response from a probability distribution perspective in semantic space. It has no restriction on task types and is "off-the-shelf" for new models and tasks. Experiments on seven state-of-the-art LLMs, including the latest Llama 3 and Mixtral-8x22B models, on four free-form question-answering benchmarks demonstrate the superior performance and robustness of semantic density compared to prior approaches.

[Arxiv](https://arxiv.org/abs/2405.13845)