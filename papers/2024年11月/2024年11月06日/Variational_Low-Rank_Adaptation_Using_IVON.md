# 变分低秩适应使用 IVON

发布时间：2024年11月06日

`LLM应用` `语言模型` `机器学习`

> Variational Low-Rank Adaptation Using IVON

# 摘要

> 我们表明，变分学习可以显著提高低秩适应（LoRA）的准确性和校准，而不会大幅增加成本。我们用改进的变分在线牛顿（IVON）算法取代 AdamW 来微调大型语言模型。对于具有 70 亿参数的 Llama-2，IVON 比 AdamW 的准确性提高了 2.8％，预期校准误差降低了 4.6％。准确性也优于其他贝叶斯替代方案，然而成本更低，实现更容易。我们的工作为 IVON 对大型语言模型的有效性提供了额外的证据。代码可在 https://github.com/team-approx-bayes/ivon-lora 获得。

> We show that variational learning can significantly improve the accuracy and calibration of Low-Rank Adaptation (LoRA) without a substantial increase in the cost. We replace AdamW by the Improved Variational Online Newton (IVON) algorithm to finetune large language models. For Llama-2 with 7 billion parameters, IVON improves the accuracy over AdamW by 2.8% and expected calibration error by 4.6%. The accuracy is also better than the other Bayesian alternatives, yet the cost is lower and the implementation is easier. Our work provides additional evidence for the effectiveness of IVON for large language models. The code is available at https://github.com/team-approx-bayes/ivon-lora.

[Arxiv](https://arxiv.org/abs/2411.04421)