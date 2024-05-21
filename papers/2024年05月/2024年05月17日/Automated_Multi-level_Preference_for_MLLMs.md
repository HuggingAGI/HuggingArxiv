# 多语言大型语言模型的自动化多级偏好设置

发布时间：2024年05月17日

`LLM应用

这篇论文主要探讨了多模态大型语言模型（MLLMs）在处理图像输入时可能产生的“幻觉”问题，并提出了一种基于人类反馈的强化学习（RLHF）方法来改善模型的回答质量。论文中提出的自动化多级偏好（AMP）框架和多级直接偏好优化（MDPO）算法，以及创建的幻觉基准MRHal-Bench，都是针对MLLMs的具体应用问题进行的研究和改进。因此，这篇论文更符合LLM应用的分类。` `人工智能` `机器学习`

> Automated Multi-level Preference for MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）有时会“幻觉”，生成与图像输入无关的回答。对此，我们探索了利用人类反馈的强化学习（RLHF）这一途径，旨在引导模型学习更优质的回答，避免劣质内容。我们反思了传统的二元偏好（优劣）评估方式，发现采用多级偏好（优、中、劣）更为合适，原因有二：一是它能缩小级别间的差距，促使模型识别微妙差异；二是它扩展了跨级别的比较，提供了更广泛的幻觉示例对比。为此，我们开发了自动化多级偏好（AMP）框架，并创建了无需人工标注的高质量多级偏好数据集生成流程。我们还设计了多级直接偏好优化（MDPO）算法，以稳健处理复杂的多级偏好学习。此外，我们提出了MRHal-Bench这一新幻觉基准。在多个公共基准及MRHal-Bench上的实验充分验证了我们方法的有效性。

> Current multimodal Large Language Models (MLLMs) suffer from ``hallucination'', occasionally generating responses that are not grounded in the input images. To tackle this challenge, one promising path is to utilize reinforcement learning from human feedback (RLHF), which steers MLLMs towards learning superior responses while avoiding inferior ones. We rethink the common practice of using binary preferences (\emph{i.e.}, superior, inferior), and find that adopting multi-level preferences (\emph{e.g.}, superior, medium, inferior) is better for two benefits: 1) It narrows the gap between adjacent levels, thereby encouraging MLLMs to discern subtle differences. 2) It further integrates cross-level comparisons (beyond adjacent-level comparisons), thus providing a broader range of comparisons with hallucination examples. To verify our viewpoint, we present the Automated Multi-level Preference (\textbf{AMP}) framework for MLLMs. To facilitate this framework, we first develop an automated dataset generation pipeline that provides high-quality multi-level preference datasets without any human annotators. Furthermore, we design the Multi-level Direct Preference Optimization (MDPO) algorithm to robustly conduct complex multi-level preference learning. Additionally, we propose a new hallucination benchmark, MRHal-Bench. Extensive experiments across public hallucination and general benchmarks, as well as our MRHal-Bench, demonstrate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2405.11165)