# LOVA3：掌握视觉问答、提问与评估的艺术

发布时间：2024年05月23日

`LLM应用

理由：这篇论文主要介绍了LOVA3框架，该框架旨在增强多模态大型语言模型（MLLMs）的问答、提问与评估能力。通过引入新的训练任务和基准，论文展示了如何通过这些方法提升MLLMs在多模态理解方面的性能。这属于在现有大型语言模型基础上进行应用层面的改进和扩展，因此归类为LLM应用。` `人工智能`

> LOVA3: Learning to Visual Question Answering, Asking and Assessment

# 摘要

> 问答、提问与评估是人类理解世界、获取知识的关键本能。通过强化这些本能，我们能更高效地利用数据，提升理解和学习的效果。然而，现今的多模态大型语言模型（MLLMs）大多只专注于问答，忽略了提问与评估技能的巨大潜力。为此，我们推出了LOVA3框架，旨在赋予MLLMs这些额外技能。我们的方法包括新增两个训练任务GenQA和EvalQA，专注于在图像背景下培养提问与评估能力。为提升提问技能，我们整合了一系列多模态基础任务。对于评估，我们设立了新基准EvalQABench，包含64,000个训练样本（正负各半）及5,000个测试样本。我们相信，赋予MLLMs问答、提问与评估的能力将增强其多模态理解，提升性能。通过LOVA3框架训练MLLM并在10个多模态基准上测试，我们验证了这一假设，结果显示性能显著提升，证明了我们方法的有效性。

> Question answering, asking, and assessment are three innate human traits crucial for understanding the world and acquiring knowledge. By enhancing these capabilities, humans can more effectively utilize data, leading to better comprehension and learning outcomes. However, current Multimodal Large Language Models (MLLMs) primarily focus on question answering, often neglecting the full potential of questioning and assessment skills. In this study, we introduce LOVA3, an innovative framework named ``Learning tO Visual Question Answering, Asking and Assessment,'' designed to equip MLLMs with these additional capabilities. Our approach involves the creation of two supplementary training tasks GenQA and EvalQA, aiming at fostering the skills of asking and assessing questions in the context of images. To develop the questioning ability, we compile a comprehensive set of multimodal foundational tasks. For assessment, we introduce a new benchmark called EvalQABench, comprising 64,000 training samples (split evenly between positive and negative samples) and 5,000 testing samples. We posit that enhancing MLLMs with the capabilities to answer, ask, and assess questions will improve their multimodal comprehension and lead to better performance. We validate our hypothesis by training an MLLM using the LOVA3 framework and testing it on 10 multimodal benchmarks. The results demonstrate consistent performance improvements, thereby confirming the efficacy of our approach.

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x1.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x2.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x3.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x4.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x6.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x7.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x8.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x9.png)

![LOVA3：掌握视觉问答、提问与评估的艺术](../../../paper_images/2405.14974/x10.png)

[Arxiv](https://arxiv.org/abs/2405.14974)