# 揭秘分子奥秘：LLM 增强的线性模型助力可解释与可校准的分子属性预测

发布时间：2024年10月11日

`LLM应用` `药物发现` `材料科学`

> Unveiling Molecular Secrets: An LLM-Augmented Linear Model for Explainable and Calibratable Molecular Property Prediction

# 摘要

> 分子性质预测的可解释性在药物发现和材料科学等领域至关重要。线性模型虽具内在解释性，但难以捕捉复杂非线性模式；而大型语言模型（LLM）虽能通过强大推理能力提供准确预测，却无法给出化学上有意义的解释。为此，我们提出MoleX框架，利用LLM知识构建简单而强大的线性模型，实现准确且可解释的分子性质预测。MoleX通过简单线性模型结合LLM知识和校准策略，有效建模复杂分子结构-性质关系。我们采用信息瓶颈微调和稀疏降维，从LLM嵌入中提取丰富信息，用于拟合线性模型进行可解释推理。此外，引入残差校准解决线性模型表达能力不足问题，提升预测准确性。理论分析为MoleX可解释性提供数学基础。实验证明，MoleX在分子性质预测上超越现有方法，显著提升预测性能、可解释性和效率。MoleX实现CPU推理，加速大规模数据处理，以300倍速度和少100,000参数达到可比性能。校准更将模型性能提升高达12.7%，且不损害可解释性。

> Explainable molecular property prediction is essential for various scientific fields, such as drug discovery and material science. Despite delivering intrinsic explainability, linear models struggle with capturing complex, non-linear patterns. Large language models (LLMs), on the other hand, yield accurate predictions through powerful inference capabilities yet fail to provide chemically meaningful explanations for their predictions. This work proposes a novel framework, called MoleX, which leverages LLM knowledge to build a simple yet powerful linear model for accurate molecular property prediction with faithful explanations. The core of MoleX is to model complicated molecular structure-property relationships using a simple linear model, augmented by LLM knowledge and a crafted calibration strategy. Specifically, to extract the maximum amount of task-relevant knowledge from LLM embeddings, we employ information bottleneck-inspired fine-tuning and sparsity-inducing dimensionality reduction. These informative embeddings are then used to fit a linear model for explainable inference. Moreover, we introduce residual calibration to address prediction errors stemming from linear models' insufficient expressiveness of complex LLM embeddings, thus recovering the LLM's predictive power and boosting overall accuracy. Theoretically, we provide a mathematical foundation to justify MoleX's explainability. Extensive experiments demonstrate that MoleX outperforms existing methods in molecular property prediction, establishing a new milestone in predictive performance, explainability, and efficiency. In particular, MoleX enables CPU inference and accelerates large-scale dataset processing, achieving comparable performance 300x faster with 100,000 fewer parameters than LLMs. Additionally, the calibration improves model performance by up to 12.7% without compromising explainability.

[Arxiv](https://arxiv.org/abs/2410.08829)