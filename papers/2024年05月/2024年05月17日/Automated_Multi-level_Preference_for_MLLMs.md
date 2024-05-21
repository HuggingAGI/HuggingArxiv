# 多语言大型语言模型的自动化多级偏好设置

发布时间：2024年05月17日

`RAG

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）中的“幻觉”现象，并提出了一种基于人类反馈的强化学习（RLHF）方法来改善模型的回答质量。论文中提到的自动化多级偏好（AMP）框架和多级直接偏好优化（MDPO）算法，以及创建的多级偏好数据集和幻觉基准测试MRHal-Bench，都是为了优化和评估模型的性能。这些内容更偏向于模型优化和评估的方法论，属于RAG（Retrieval-Augmented Generation）的范畴，即通过检索增强生成模型的性能。` `人工智能` `机器学习`

> Automated Multi-level Preference for MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）常出现“幻觉”现象，即生成与输入图像无关的回答。为此，我们探索了利用人类反馈的强化学习（RLHF）这一途径，旨在引导模型学习更优质的回答，同时避免劣质内容。我们反思了传统的二元偏好（优劣）评估方式，发现采用多级偏好（优、中、劣）更为有效，原因如下：1）它缩小了级别间的差距，促使模型识别细微差别；2）它引入了跨级别的比较，拓宽了与幻觉示例的对比范围。为验证这一观点，我们开发了自动化多级偏好（AMP）框架，并创建了无需人工标注的高质量多级偏好数据集生成流程。我们还设计了多级直接偏好优化（MDPO）算法，以稳健处理复杂的多级偏好学习。此外，我们推出了新的幻觉基准测试MRHal-Bench。在多个公共基准及MRHal-Bench上的实验结果均显示了我们方法的有效性。

> Current multimodal Large Language Models (MLLMs) suffer from ``hallucination'', occasionally generating responses that are not grounded in the input images. To tackle this challenge, one promising path is to utilize reinforcement learning from human feedback (RLHF), which steers MLLMs towards learning superior responses while avoiding inferior ones. We rethink the common practice of using binary preferences (\emph{i.e.}, superior, inferior), and find that adopting multi-level preferences (\emph{e.g.}, superior, medium, inferior) is better for two benefits: 1) It narrows the gap between adjacent levels, thereby encouraging MLLMs to discern subtle differences. 2) It further integrates cross-level comparisons (beyond adjacent-level comparisons), thus providing a broader range of comparisons with hallucination examples. To verify our viewpoint, we present the Automated Multi-level Preference (\textbf{AMP}) framework for MLLMs. To facilitate this framework, we first develop an automated dataset generation pipeline that provides high-quality multi-level preference datasets without any human annotators. Furthermore, we design the Multi-level Direct Preference Optimization (MDPO) algorithm to robustly conduct complex multi-level preference learning. Additionally, we propose a new hallucination benchmark, MRHal-Bench. Extensive experiments across public hallucination and general benchmarks, as well as our MRHal-Bench, demonstrate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2405.11165)