# SAFETY-J：以批判视角评估安全性

发布时间：2024年07月24日

`LLM应用` `安全评估` `人工智能`

> SAFETY-J: Evaluating Safety with Critique

# 摘要

> 大型语言模型在内容生成中的应用引发了显著的安全担忧，尤其是在内容评估的透明度和可解释性方面。当前方法主要依赖二元安全分类，缺乏深入批评的机制，限制了其在提升模型和增强用户信任方面的效用。为此，我们推出了 SAFETY-J，一款基于批评判断的英汉双语生成安全评估工具。SAFETY-J 通过使用包含多样化对话和增强查询-响应对的训练数据集，全面评估各种场景下的安全性。我们还建立了自动化的元评估基准，以客观评估批评质量，并实现最小化的人工干预，推动持续改进。此外，SAFETY-J 采用迭代偏好学习技术，根据元评估和批评结果动态优化安全评估。评估显示，SAFETY-J 能提供更细致和准确的安全评估，显著提升复杂内容场景中的批评质量和预测可靠性。为促进更广泛的研究和应用，我们将公开 SAFETY-J 的训练协议、数据集和代码。

> The deployment of Large Language Models (LLMs) in content generation raises significant safety concerns, particularly regarding the transparency and interpretability of content evaluations. Current methods, primarily focused on binary safety classifications, lack mechanisms for detailed critique, limiting their utility for model improvement and user trust. To address these limitations, we introduce SAFETY-J, a bilingual generative safety evaluator for English and Chinese with critique-based judgment. SAFETY-J utilizes a robust training dataset that includes diverse dialogues and augmented query-response pairs to assess safety across various scenarios comprehensively. We establish an automated meta-evaluation benchmark that objectively assesses the quality of critiques with minimal human intervention, facilitating scalable and continuous improvement. Additionally, SAFETY-J employs an iterative preference learning technique to dynamically refine safety assessments based on meta-evaluations and critiques. Our evaluations demonstrate that SAFETY-J provides more nuanced and accurate safety evaluations, thereby enhancing both critique quality and predictive reliability in complex content scenarios. To facilitate further research and application, we will open-source SAFETY-J's training protocols, datasets, and code.

![SAFETY-J：以批判视角评估安全性](../../../paper_images/2407.17075/circle.png)

![SAFETY-J：以批判视角评估安全性](../../../paper_images/2407.17075/x1.png)

![SAFETY-J：以批判视角评估安全性](../../../paper_images/2407.17075/x2.png)

![SAFETY-J：以批判视角评估安全性](../../../paper_images/2407.17075/x3.png)

![SAFETY-J：以批判视角评估安全性](../../../paper_images/2407.17075/x4.png)

[Arxiv](https://arxiv.org/abs/2407.17075)