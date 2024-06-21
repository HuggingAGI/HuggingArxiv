# 提升标准：利用生成式演化测试探索大型语言模型的潜力

发布时间：2024年06月20日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的道德基准和价值对齐问题，并提出了一种创新的生成式进化测试方法（GETA）来动态评估LLMs的道德表现。这种方法涉及到理论上的创新，如通过迭代更新的项目生成器来推断和定制每个LLM的道德测试难度，以及学习项目和模型响应的联合分布。这些内容更多地关注于LLM的理论发展和评估方法的改进，而不是具体的应用或Agent的设计，因此更适合归类于LLM理论。` `人工智能伦理` `模型评估`

> Raising the Bar: Investigating the Values of Large Language Models via Generative Evolving Testing

# 摘要

> 警告：本文包含展示不道德信息的模型输出。尽管大型语言模型（LLMs）取得了显著进展，但其生成的不道德内容带来了潜在风险。因此，衡量LLMs的价值对齐变得至关重要。虽然已有多个数据集用于评估LLMs的社会偏见、毒性和伦理，但这些数据集因模型快速进化而过时，导致对LLMs的评估失真。为此，我们提出了GETA，一种创新的生成式进化测试方法，它能动态探测LLMs的道德基准。与依赖静态数据集的传统适应性测试不同，GETA通过迭代更新的项目生成器，推断并定制每个LLM的道德测试难度，准确反映其价值对齐程度。这种方法通过学习项目和模型响应的联合分布，与LLMs共同进化，有效解决了评估的时间效应问题。我们通过评估多种LLMs的能力，证明了GETA能更准确地匹配测试难度，更精确地评估LLMs的价值，为其在未知数据上的表现提供了更一致的评估，为未来的评估方法奠定了基础。

> Warning: this paper contains model outputs exhibiting unethical information. Large Language Models (LLMs) have achieved significant breakthroughs, but their generated unethical content poses potential risks. Measuring value alignment of LLMs becomes crucial for their regulation and responsible deployment. Numerous datasets have been constructed to assess social bias, toxicity, and ethics in LLMs, but they suffer from evaluation chronoeffect, that is, as models rapidly evolve, existing data becomes leaked or undemanding, overestimating ever-developing LLMs. To tackle this problem, we propose GETA, a novel generative evolving testing approach that dynamically probes the underlying moral baselines of LLMs. Distinct from previous adaptive testing methods that rely on static datasets with limited difficulty, GETA incorporates an iteratively-updated item generator which infers each LLM's moral boundaries and generates difficulty-tailored testing items, accurately reflecting the true alignment extent. This process theoretically learns a joint distribution of item and model response, with item difficulty and value conformity as latent variables, where the generator co-evolves with the LLM, addressing chronoeffect. We evaluate various popular LLMs with diverse capabilities and demonstrate that GETA can create difficulty-matching testing items and more accurately assess LLMs' values, better consistent with their performance on unseen OOD and i.i.d. items, laying the groundwork for future evaluation paradigms.

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x1.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x2.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x3.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x4.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x5.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x6.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x7.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x8.png)

![提升标准：利用生成式演化测试探索大型语言模型的潜力](../../../paper_images/2406.14230/x9.png)

[Arxiv](https://arxiv.org/abs/2406.14230)