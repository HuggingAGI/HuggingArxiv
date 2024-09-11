# 利用大型语言模型预测材料与分子性质的回归分析

发布时间：2024年09月09日

`LLM应用` `材料科学`

> Regression with Large Language Models for Materials and Molecular Property Prediction

# 摘要

> 我们展示了 LLM 在材料和分子属性回归任务中的潜力，这超出了其传统应用范畴。通过在 QM9 数据集和 24 种材料属性上对 LLaMA 3 进行基准测试，我们发现，仅使用基于组成的输入字符串并微调生成损失，LLaMA 3 在分子 SMILES 表示下的回归结果可与标准预测模型媲美。尽管其误差仍高于使用更精细分子表示的先进模型，但 LLaMA 3 的预测性能优于 GPT-3.5 和 GPT-4o。这项研究揭示了 LLM 的多功能性，预示着生成模型在解决复杂物理现象方面的广阔前景，为化学、材料科学等领域的未来研究与应用开辟了新路径。

> We demonstrate the ability of large language models (LLMs) to perform material and molecular property regression tasks, a significant deviation from the conventional LLM use case. We benchmark the Large Language Model Meta AI (LLaMA) 3 on several molecular properties in the QM9 dataset and 24 materials properties. Only composition-based input strings are used as the model input and we fine tune on only the generative loss. We broadly find that LLaMA 3, when fine-tuned using the SMILES representation of molecules, provides useful regression results which can rival standard materials property prediction models like random forest or fully connected neural networks on the QM9 dataset. Not surprisingly, LLaMA 3 errors are 5-10x higher than those of the state-of-the-art models that were trained using far more granular representation of molecules (e.g., atom types and their coordinates) for the same task. Interestingly, LLaMA 3 provides improved predictions compared to GPT-3.5 and GPT-4o. This work highlights the versatility of LLMs, suggesting that LLM-like generative models can potentially transcend their traditional applications to tackle complex physical phenomena, thus paving the way for future research and applications in chemistry, materials science and other scientific domains.

[Arxiv](https://arxiv.org/abs/2409.06080)