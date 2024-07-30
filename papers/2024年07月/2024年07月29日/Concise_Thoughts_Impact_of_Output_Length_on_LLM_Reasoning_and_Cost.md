# 简思：输出长度如何影响 LLM 的推理与成本

发布时间：2024年07月29日

`LLM应用` `人工智能`

> Concise Thoughts: Impact of Output Length on LLM Reasoning and Cost

# 摘要

> 当前的大型语言模型 (LLM) 在处理复杂问答任务时表现出色，链式思维 (CoT) 等提示工程技术更是提升了输出的解释力和准确性。但生成详尽推理答案耗时较长。为此，本文探讨了输出长度对 LLM 推理效率的影响，并引入了“正确简洁性”的新评估指标。通过受限 CoT (CCoT) 策略，我们进一步研究了如何通过优化提示来控制输出长度。实验显示，这些新指标和 CCoT 策略在多个 LLM 中均有效。例如，限制 LLaMA2-70b 的推理长度至 100 字，GSM8K 数据集上的准确率提升至 41.07%，且输出长度平均缩短 28 字。

> Today's large language models (LLMs) can solve challenging question-answering tasks, and prompt engineering techniques, such as chain-of-thought (CoT), have gained attention for enhancing the explanation and correctness of outputs. Nevertheless, models require significant time to generate answers augmented with lengthy reasoning details. To address this issue, this paper analyzes the impact of output lengths on LLM inference pipelines and proposes novel metrics to evaluate them in terms of \textit{correct conciseness}. It also examines the impact of controlling output length through a refined prompt engineering strategy, Constrained-CoT (CCoT), which encourages the model to limit output length. Experiments on pre-trained LLMs demonstrated the benefit of the proposed metrics and the effectiveness of CCoT across different models. For instance, constraining the reasoning of LLaMA2-70b to 100 words improves the accuracy from 36.01\% (CoT) to 41.07\% (CCoT) on the GSM8K dataset, while reducing the average output length by 28 words.

[Arxiv](https://arxiv.org/abs/2407.19825)