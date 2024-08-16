# 知识图谱上训练语言模型：探索幻觉现象及其检测方法

发布时间：2024年08月14日

`LLM理论` `人工智能` `知识图谱`

> Training Language Models on the Knowledge Graph: Insights on Hallucinations and Their Detectability

# 摘要

> 随着训练预算的增加，语言模型的许多能力得到提升，但规模对幻觉的影响仍未明朗。幻觉形式多样，定义不一。我们因此聚焦于研究那些训练集中正确答案完全一致的幻觉。为精确掌控训练数据，我们构建了基于知识图谱的数据集，并以此训练一系列规模递增的语言模型。结果显示，固定数据集下，规模更大、训练更久的模型幻觉更少。但若要在不超过5%的训练数据上减少幻觉，所需模型规模和计算量远超Hoffmann等人(2022)所称的最佳值。鉴于成本高昂，我们探究了幻觉检测器对规模的依赖性。尽管检测器规模能提升固定模型输出的检测性能，我们却发现模型规模与幻觉可检测性呈反比关系。

> While many capabilities of language models (LMs) improve with increased training budget, the influence of scale on hallucinations is not yet fully understood. Hallucinations come in many forms, and there is no universally accepted definition. We thus focus on studying only those hallucinations where a correct answer appears verbatim in the training set. To fully control the training data content, we construct a knowledge graph (KG)-based dataset, and use it to train a set of increasingly large LMs. We find that for a fixed dataset, larger and longer-trained LMs hallucinate less. However, hallucinating on $\leq5$% of the training data requires an order of magnitude larger model, and thus an order of magnitude more compute, than Hoffmann et al. (2022) reported was optimal. Given this costliness, we study how hallucination detectors depend on scale. While we see detector size improves performance on fixed LM's outputs, we find an inverse relationship between the scale of the LM and the detectability of its hallucinations.

[Arxiv](https://arxiv.org/abs/2408.07852)