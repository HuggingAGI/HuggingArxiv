# 大型多语言语言模型（MLLMs）的自动化多级偏好设置

发布时间：2024年05月17日

`RAG

这篇论文主要关注多模态大型语言模型（MLLMs）中的“幻觉”问题，并提出了一种基于人类反馈的强化学习（RLHF）的解决方案。论文中提出的自动化多级偏好（AMP）框架和多级直接偏好优化（MDPO）算法，以及创建的幻觉基准MRHal-Bench，都是为了改进模型的回答质量，避免生成无关或劣质的回答。这些方法和工具的开发，特别是通过多级偏好来优化模型性能，属于模型调整和优化的范畴，因此更适合归类为RAG（Retrieval-Augmented Generation），这是一个涉及模型生成内容调整和优化的领域。` `人工智能` `机器学习`

> Automated Multi-level Preference for MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）有时会“幻觉”，生成与图像输入无关的回答。对此，利用人类反馈的强化学习（RLHF）是一条有希望的解决路径，它能引导模型学习更优的回答，避免劣质回答。我们反思了传统的二元偏好（优劣）方法，发现采用多级偏好（优、中、劣）更为有效，因为它能：1) 缩小级别间的差距，促使模型识别细微差别；2) 进行跨级别比较，提供更广泛的幻觉示例对比。为此，我们推出了自动化多级偏好（AMP）框架，并开发了无需人工标注的高质量数据集生成流程。我们还设计了多级直接偏好优化（MDPO）算法，并创建了新的幻觉基准MRHal-Bench。在多个测试中，我们的方法均显示出其有效性。

> Current multimodal Large Language Models (MLLMs) suffer from ``hallucination'', occasionally generating responses that are not grounded in the input images. To tackle this challenge, one promising path is to utilize reinforcement learning from human feedback (RLHF), which steers MLLMs towards learning superior responses while avoiding inferior ones. We rethink the common practice of using binary preferences (\emph{i.e.}, superior, inferior), and find that adopting multi-level preferences (\emph{e.g.}, superior, medium, inferior) is better for two benefits: 1) It narrows the gap between adjacent levels, thereby encouraging MLLMs to discern subtle differences. 2) It further integrates cross-level comparisons (beyond adjacent-level comparisons), thus providing a broader range of comparisons with hallucination examples. To verify our viewpoint, we present the Automated Multi-level Preference (\textbf{AMP}) framework for MLLMs. To facilitate this framework, we first develop an automated dataset generation pipeline that provides high-quality multi-level preference datasets without any human annotators. Furthermore, we design the Multi-level Direct Preference Optimization (MDPO) algorithm to robustly conduct complex multi-level preference learning. Additionally, we propose a new hallucination benchmark, MRHal-Bench. Extensive experiments across public hallucination and general benchmarks, as well as our MRHal-Bench, demonstrate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2405.11165)