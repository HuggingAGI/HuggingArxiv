# LIME-M：在评估多语言大型语言模型时，简洁胜于繁复

发布时间：2024年09月10日

`LLM应用` `人工智能` `计算机视觉`

> LIME-M: Less Is More for Evaluation of MLLMs

# 摘要

> 随着多模态大型语言模型（MLLM）的显著成功，众多基准应运而生，旨在评估其在图像感知任务中的能力。然而，大量基准的存在使得全面评估模型性能时计算负担沉重。此外，这些基准中充斥着过于简单或极具挑战性的样本，无法有效区分不同MLLM的能力。为此，我们提出了一套处理现有基准的流程，包括两个核心模块：半自动化筛选和消除答案泄露。前者通过合成与手动评估多种MLLM，过滤掉无法区分模型能力的样本；后者则剔除那些答案可脱离图像推断的样本。最终，我们精心打造了LIME-M：一个轻量级多模态基准，旨在更高效地评估不同模型的性能。实验结果显示，LIME-M以更少的样本和时间（分别减少76%和77%），更精准地区分了各MLLM的性能。同时，它有效消除了答案泄露，聚焦于图像本身的信息。此外，我们发现当前的自动评估指标（如CIDEr）在描述任务中对MLLM能力的评估尚显不足。而移除描述任务分数后，整体评估更能准确反映模型间的性能差异。所有相关代码与数据已公开于https://github.com/kangreen0210/LIME-M。

> With the remarkable success achieved by Multimodal Large Language Models (MLLMs), numerous benchmarks have been designed to assess MLLMs' ability to guide their development in image perception tasks (e.g., image captioning and visual question answering). However, the existence of numerous benchmarks results in a substantial computational burden when evaluating model performance across all of them. Moreover, these benchmarks contain many overly simple problems or challenging samples, which do not effectively differentiate the capabilities among various MLLMs. To address these challenges, we propose a pipeline to process the existing benchmarks, which consists of two modules: (1) Semi-Automated Screening Process and (2) Eliminating Answer Leakage. The Semi-Automated Screening Process filters out samples that cannot distinguish the model's capabilities by synthesizing various MLLMs and manually evaluating them. The Eliminate Answer Leakage module filters samples whose answers can be inferred without images. Finally, we curate the LIME-M: Less Is More for Evaluation of Multimodal LLMs, a lightweight Multimodal benchmark that can more effectively evaluate the performance of different models. Our experiments demonstrate that: LIME-M can better distinguish the performance of different MLLMs with fewer samples (24% of the original) and reduced time (23% of the original); LIME-M eliminates answer leakage, focusing mainly on the information within images; The current automatic metric (i.e., CIDEr) is insufficient for evaluating MLLMs' capabilities in captioning. Moreover, removing the caption task score when calculating the overall score provides a more accurate reflection of model performance differences. All our codes and data are released at https://github.com/kangreen0210/LIME-M.

[Arxiv](https://arxiv.org/abs/2409.06851)