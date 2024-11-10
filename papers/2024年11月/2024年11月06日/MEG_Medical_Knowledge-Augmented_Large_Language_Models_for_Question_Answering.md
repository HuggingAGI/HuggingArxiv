# MEG：用于问答的医学知识增强型大型语言模型

发布时间：2024年11月06日

`LLM应用` `问答系统`

> MEG: Medical Knowledge-Augmented Large Language Models for Question Answering

# 摘要

> 问答是一项自然语言理解任务，涉及对显性上下文和未陈述的相关领域知识的推理。作为大多数当代问答系统基础的大型语言模型（LLM），难以推断出在诸如医学等专业领域中的概念如何相关。现有的医学 LLM 训练成本也很高。在这项工作中，我们提出了 MEG，这是一种针对医学知识增强的 LLM 的参数高效方法。MEG 使用轻量级映射网络将图嵌入集成到 LLM 中，使其能够以经济有效的方式利用外部知识。我们在四个流行的医学多项选择数据集上评估了我们的方法，并表明 LLM 极大地受益于知识图嵌入提供的事实基础。MEG 比 Mistral-Instruct 基线平均准确率提高了 +10.2％，比像 BioMistral 这样的专业模型提高了 +6.7％。我们还展示了基于 Llama-3 的结果。最后，我们表明 MEG 的性能对于图编码器的选择仍然稳健。

> Question answering is a natural language understanding task that involves reasoning over both explicit context and unstated, relevant domain knowledge. Large language models (LLMs), which underpin most contemporary question answering systems, struggle to induce how concepts relate in specialized domains such as medicine. Existing medical LLMs are also costly to train. In this work, we present MEG, a parameter-efficient approach for medical knowledge-augmented LLMs. MEG uses a lightweight mapping network to integrate graph embeddings into the LLM, enabling it to leverage external knowledge in a cost-effective way. We evaluate our method on four popular medical multiple-choice datasets and show that LLMs greatly benefit from the factual grounding provided by knowledge graph embeddings. MEG attains an average of +10.2% accuracy over the Mistral-Instruct baseline, and +6.7% over specialized models like BioMistral. We also show results based on Llama-3. Finally, we show that MEG's performance remains robust to the choice of graph encoder.

[Arxiv](https://arxiv.org/abs/2411.03883)