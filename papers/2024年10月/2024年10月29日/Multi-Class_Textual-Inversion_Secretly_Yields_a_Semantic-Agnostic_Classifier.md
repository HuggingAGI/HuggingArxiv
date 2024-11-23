# 多类文本反转竟悄然生成了一个语义无关的分类器

发布时间：2024年10月29日

`LLM应用` `计算机视觉`

> Multi-Class Textual-Inversion Secretly Yields a Semantic-Agnostic Classifier

# 摘要

> 随着像 CLIP 这样的大型预训练视觉语言模型的问世，提示学习方法致力于提升 CLIP 模型的可迁移性。它们在已知特定类名作为先验知识的情况下，依据下游任务所给定的少量样本学习提示，我们称其为语义感知分类。然而，在众多现实情境中，我们仅能获取少量样本和类名的知识（比如在考虑类的实例时）。这种颇具挑战的情境代表了语义未知的判别情形。文本到图像（T2I）个性化方法旨在通过学习新的标记，并赋予这些标记生成所学概念的能力，让 T2I 模型适应未曾见过的概念。这些方法无需类名知识作为语义感知的先验条件。所以，在本文中，我们首先探究文本反转，并且揭示新的概念标记将每个类别视作单个概念时具备生成和分类的能力。但从单概念文本反转学习分类器存在局限，因为所学标记对于判别任务并非最优。为了缓解此问题，我们提出多类文本反转，它包含一个用于标记更新过程的判别正则化项。运用此技术，我们的方法 MC-TI 在每个类别仅给定少量样本的情况下，实现了更出色的语义未知分类，同时保留了这些修饰符标记的生成能力。在实验中，我们在涵盖各种场景的 12 个数据集中对 MC-TI 进行了广泛评估，结果表明 MC-TI 在分类和生成结果上均表现卓越。

> With the advent of large pre-trained vision-language models such as CLIP, prompt learning methods aim to enhance the transferability of the CLIP model. They learn the prompt given few samples from the downstream task given the specific class names as prior knowledge, which we term as semantic-aware classification. However, in many realistic scenarios, we only have access to few samples and knowledge of the class names (e.g., when considering instances of classes). This challenging scenario represents the semantic-agnostic discriminative case. Text-to-Image (T2I) personalization methods aim to adapt T2I models to unseen concepts by learning new tokens and endowing these tokens with the capability of generating the learned concepts. These methods do not require knowledge of class names as a semantic-aware prior. Therefore, in this paper, we first explore Textual Inversion and reveal that the new concept tokens possess both generation and classification capabilities by regarding each category as a single concept. However, learning classifiers from single-concept textual inversion is limited since the learned tokens are suboptimal for the discriminative tasks. To mitigate this issue, we propose Multi-Class textual inversion, which includes a discriminative regularization term for the token updating process. Using this technique, our method MC-TI achieves stronger Semantic-Agnostic Classification while preserving the generation capability of these modifier tokens given only few samples per category. In the experiments, we extensively evaluate MC-TI on 12 datasets covering various scenarios, which demonstrates that MC-TI achieves superior results in terms of both classification and generation outcomes.

[Arxiv](https://arxiv.org/abs/2410.22317)