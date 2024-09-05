# CMM-Math：一款中文多模态数学数据集，旨在评估并提升大型多模态模型在数学推理方面的能力。

发布时间：2024年09月04日

`LLM应用` `人工智能`

> CMM-Math: A Chinese Multimodal Math Dataset To Evaluate and Enhance the Mathematics Reasoning of Large Multimodal Models

# 摘要

> 大型语言模型在数学推理领域取得了显著成果，这是人类智能的核心能力。以往研究多聚焦于基于文本的数学推理数据集来提升和评估 LLM 性能。近期，有研究者推出了英语多模态数学数据集，以测试大型多模态模型的效能。本文中，我们推出了中文多模态数学数据集 CMM-Math，旨在评估并提升 LMM 的数学推理能力。该数据集包含超过 28,000 个高质量样本，涵盖从小学到高中的 12 个年级，问题类型多样，解答详尽。数据集中，视觉元素的加入增加了难度。分析显示，当前最先进的 LMM 在 CMM-Math 上仍面临挑战，凸显了 LMM 进一步改进的必要性。为此，我们提出了一种新的多模态数学 LMM，专门处理包含多图像和文本的复杂问题。我们的模型经过三个阶段的训练：基础预训练、基础微调和数学微调。实验结果表明，与现有最先进的 LMM 相比，我们的模型在三个多模态数学数据集上显著提升了数学推理性能。

> Large language models (LLMs) have obtained promising results in mathematical reasoning, which is a foundational skill for human intelligence. Most previous studies focus on improving and measuring the performance of LLMs based on textual math reasoning datasets (e.g., MATH, GSM8K). Recently, a few researchers have released English multimodal math datasets (e.g., MATHVISTA and MATH-V) to evaluate the effectiveness of large multimodal models (LMMs). In this paper, we release a Chinese multimodal math (CMM-Math) dataset, including benchmark and training parts, to evaluate and enhance the mathematical reasoning of LMMs. CMM-Math contains over 28,000 high-quality samples, featuring a variety of problem types (e.g., multiple-choice, fill-in-the-blank, and so on) with detailed solutions across 12 grade levels from elementary to high school in China. Specifically, the visual context may be present in the questions or opinions, which makes this dataset more challenging. Through comprehensive analysis, we discover that state-of-the-art LMMs on the CMM-Math dataset face challenges, emphasizing the necessity for further improvements in LMM development. We also propose a Multimodal Mathematical LMM (Math-LMM) to handle the problems with mixed input of multiple images and text segments. We train our model using three stages, including foundational pre-training, foundational fine-tuning, and mathematical fine-tuning. The extensive experiments indicate that our model effectively improves math reasoning performance by comparing it with the SOTA LMMs over three multimodal mathematical datasets.

[Arxiv](https://arxiv.org/abs/2409.02834)