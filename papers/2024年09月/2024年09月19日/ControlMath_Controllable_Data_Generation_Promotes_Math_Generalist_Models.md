# ControlMath：通过可控数据生成，助力数学通才模型的成长

发布时间：2024年09月19日

`LLM应用` `人工智能`

> ControlMath: Controllable Data Generation Promotes Math Generalist Models

# 摘要

> 通过大型语言模型 (LLM) 进行数据增强，在数学推理中已取得显著成效。然而，现有方法在问题多样性上存在局限，可能仅限于生成特定领域内的数据。为此，我们设计了 ControlMath，一种迭代方法，结合方程生成器和两个 LLM 代理。方程生成器创造多样方程，Problem-Crafter 将其转化为数学应用题，而 Reverse-Agent 则精选高质量数据，遵循“少即是多”原则，以少量数据实现更佳效果。这种方法突破了领域限制，生成多样数学问题。我们因此收集了包含 190k 题的 ControlMathQA。实验证明，结合 GSM8K 等数据集，能显著提升模型泛化能力，无论在特定领域内外，均表现更优。

> Utilizing large language models (LLMs) for data augmentation has yielded encouraging results in mathematical reasoning. However, these approaches face constraints in problem diversity, potentially restricting them to in-domain/distribution data generation. To this end, we propose ControlMath, an iterative method involving an equation-generator module and two LLM-based agents. The module creates diverse equations, which the Problem-Crafter agent then transforms into math word problems. The Reverse-Agent filters and selects high-quality data, adhering to the "less is more" principle, achieving better results with fewer data points. This approach enables the generation of diverse math problems, not limited to specific domains or distributions. As a result, we collect ControlMathQA, which involves 190k math word problems. Extensive results prove that combining our dataset with in-domain datasets like GSM8K can help improve the model's mathematical ability to generalize, leading to improved performances both within and beyond specific domains.

[Arxiv](https://arxiv.org/abs/2409.15376)