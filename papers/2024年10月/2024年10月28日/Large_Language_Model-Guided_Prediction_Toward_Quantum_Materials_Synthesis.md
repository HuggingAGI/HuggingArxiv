# 大型语言模型引导的量子材料合成预测

发布时间：2024年10月28日

`LLM应用` `材料科学` `量子材料`

> Large Language Model-Guided Prediction Toward Quantum Materials Synthesis

# 摘要

> 无机晶体材料的合成对于现代技术至关重要，特别是在量子材料的发展中。然而，由于精确的实验条件和大量的反复试验，设计高效的合成工作流程仍然是一个重大挑战。在这里，我们提出了一个使用大型语言模型（LLM）来预测无机材料（包括量子材料）合成途径的框架。我们的框架包含三个模型：LHS2RHS，从反应物预测产物；RHS2LHS，从产物预测反应物；以及 TGT2CEQ，为目标化合物生成完整的化学方程式。在一个文本挖掘的合成数据库上进行微调，我们的模型将准确率从预训练模型的不到 40%提高到常规微调的不到 80%，再通过我们提出的广义田口相似度进一步提高到约 90%，同时对额外的合成步骤保持稳健。我们的模型进一步证明，在使用量子权重量化的不同量子程度的材料中，性能相当，这表明 LLM 为预测量子材料发现的平衡化学方程式提供了一个强大的工具。

> The synthesis of inorganic crystalline materials is essential for modern technology, especially in quantum materials development. However, designing efficient synthesis workflows remains a significant challenge due to the precise experimental conditions and extensive trial and error. Here, we present a framework using large language models (LLMs) to predict synthesis pathways for inorganic materials, including quantum materials. Our framework contains three models: LHS2RHS, predicting products from reactants; RHS2LHS, predicting reactants from products; and TGT2CEQ, generating full chemical equations for target compounds. Fine-tuned on a text-mined synthesis database, our model raises accuracy from under 40% with pretrained models, to under 80% using conventional fine-tuning, and further to around 90% with our proposed generalized Tanimoto similarity, while maintaining robust to additional synthesis steps. Our model further demonstrates comparable performance across materials with varying degrees of quantumness quantified using quantum weight, indicating that LLMs offer a powerful tool to predict balanced chemical equations for quantum materials discovery.

[Arxiv](https://arxiv.org/abs/2410.20976)