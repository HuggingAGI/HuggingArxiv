# MURI：利用反向指令技术，为低资源语言打造高质量的指令调优数据集。

发布时间：2024年09月19日

`LLM应用` `数据集`

> MURI: High-Quality Instruction Tuning Datasets for Low-Resource Languages via Reverse Instructions

# 摘要

> 指令调整通过使 LLM 与多样任务中的人类偏好对齐，显著提升其性能。然而，传统方法在创建低资源语言的指令调整数据集时，因依赖数据注释而面临挑战。为此，我们推出了多语言反向指令 (MURI) 方法，无需人工注释或现有多语言模型，即可为低资源语言生成高质量数据集。MURI 利用反向指令和翻译管道，从低资源语言的现有文本中生成指令-输出对，确保文化相关性和内容多样性。我们的 MURI-IT 数据集包含超过 200 种语言的 200 万对指令-输出对，并通过母语人士评估和 mT5 模型微调实验，验证了其在 NLU 和开放式生成任务中的有效性。数据集和模型已公开发布，访问地址为 https://github.com/akoksal/muri。

> Instruction tuning enhances large language models (LLMs) by aligning them with human preferences across diverse tasks. Traditional approaches to create instruction tuning datasets face serious challenges for low-resource languages due to their dependence on data annotation. This work introduces a novel method, Multilingual Reverse Instructions (MURI), which generates high-quality instruction tuning datasets for low-resource languages without requiring human annotators or pre-existing multilingual models. Utilizing reverse instructions and a translation pipeline, MURI produces instruction-output pairs from existing human-written texts in low-resource languages. This method ensures cultural relevance and diversity by sourcing texts from different native domains and applying filters to eliminate inappropriate content. Our dataset, MURI-IT, includes more than 2 million instruction-output pairs across 200 languages. Evaluation by native speakers and fine-tuning experiments with mT5 models demonstrate the approach's effectiveness for both NLU and open-ended generation. We publicly release datasets and models at https://github.com/akoksal/muri.

[Arxiv](https://arxiv.org/abs/2409.12958)