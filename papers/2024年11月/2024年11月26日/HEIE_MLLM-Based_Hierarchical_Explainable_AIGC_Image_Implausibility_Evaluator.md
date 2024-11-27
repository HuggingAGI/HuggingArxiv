# HEIE：基于 MLLM 的分层式可解释的 AIGC 图像不合理性评估工具

发布时间：2024年11月26日

`LLM应用` `AIGC`

> HEIE: MLLM-Based Hierarchical Explainable AIGC Image Implausibility Evaluator

# 摘要

> AIGC 图像在众多领域广泛存在，然而它们常存在质量问题，像有伪影和纹理不自然等。专门的模型意在预测缺陷区域热图，却面临两大主要挑战：其一，缺乏可解释性，不能为细微缺陷给出原因和分析；其二，无法借助常识和逻辑推理，致使泛化能力不佳。多模态大型语言模型（MLLMs）有望实现更优的理解和推理，可自身也面临挑战：一是因捕捉微小细节受限，难以进行细粒度的缺陷定位；二是在提供精确热图生成所需的像素级输出上存在局限。为应对这些难题，我们提出了 HEIE：一种新型的基于 MLLM 的分层可解释图像不合理性评估器。我们引入了 CoT 驱动的可解释三位一体评估器，它整合了热图、分数和解释输出，利用 CoT 将复杂任务分解为难度渐增的子任务，增强了可解释性。我们的自适应分层不合理映射器将低级图像特征与来自 LLM 的高级映射器令牌协同起来，通过基于不确定性的自适应令牌方法实现精准的局部到全局分层热图预测。另外，我们还提出了一个新的数据集：Expl-AIGI-Eval，旨在助力 AIGC 图像的可解释不合理性评估。我们的方法通过大量实验展现出了前沿的性能。

> AIGC images are prevalent across various fields, yet they frequently suffer from quality issues like artifacts and unnatural textures. Specialized models aim to predict defect region heatmaps but face two primary challenges: (1) lack of explainability, failing to provide reasons and analyses for subtle defects, and (2) inability to leverage common sense and logical reasoning, leading to poor generalization. Multimodal large language models (MLLMs) promise better comprehension and reasoning but face their own challenges: (1) difficulty in fine-grained defect localization due to the limitations in capturing tiny details; and (2) constraints in providing pixel-wise outputs necessary for precise heatmap generation. To address these challenges, we propose HEIE: a novel MLLM-Based Hierarchical Explainable image Implausibility Evaluator. We introduce the CoT-Driven Explainable Trinity Evaluator, which integrates heatmaps, scores, and explanation outputs, using CoT to decompose complex tasks into subtasks of increasing difficulty and enhance interpretability. Our Adaptive Hierarchical Implausibility Mapper synergizes low-level image features with high-level mapper tokens from LLMs, enabling precise local-to-global hierarchical heatmap predictions through an uncertainty-based adaptive token approach. Moreover, we propose a new dataset: Expl-AIGI-Eval, designed to facilitate interpretable implausibility evaluation of AIGC images. Our method demonstrates state-of-the-art performance through extensive experiments.

[Arxiv](https://arxiv.org/abs/2411.17261)