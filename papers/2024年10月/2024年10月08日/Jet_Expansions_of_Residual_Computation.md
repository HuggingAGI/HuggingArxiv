# 残差计算的喷气扩展技术

发布时间：2024年10月08日

`LLM理论` `人工智能` `可解释性`

> Jet Expansions of Residual Computation

# 摘要

> 我们提出了一种利用 jets（广义截断泰勒级数算子）扩展残差计算图的框架。该方法系统地解析了不同计算路径对模型预测的影响，无需数据、训练或模型采样，与蒸馏、探测等现有技术形成鲜明对比。我们的框架不仅奠定了 logit lens 的基础，还揭示了递归残差深度中的（超）指数路径结构，并开拓了多项应用，如利用 $n$-gram 统计数据绘制 transformer 大型语言模型，以及评估模型的毒性知识水平。这一创新方法为模型的可解释性、开发和评估提供了无数据分析的新途径。

> We introduce a framework for expanding residual computational graphs using jets, operators that generalize truncated Taylor series. Our method provides a systematic approach to disentangle contributions of different computational paths to model predictions. In contrast to existing techniques such as distillation, probing, or early decoding, our expansions rely solely on the model itself and requires no data, training, or sampling from the model. We demonstrate how our framework grounds and subsumes logit lens, reveals a (super-)exponential path structure in the recursive residual depth and opens up several applications. These include sketching a transformer large language model with $n$-gram statistics extracted from its computations, and indexing the models' levels of toxicity knowledge. Our approach enables data-free analysis of residual computation for model interpretability, development, and evaluation.

[Arxiv](https://arxiv.org/abs/2410.06024)