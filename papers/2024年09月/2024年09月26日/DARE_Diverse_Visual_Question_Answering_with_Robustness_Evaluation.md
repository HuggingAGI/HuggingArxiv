# DARE：多样视觉问答的鲁棒性评估

发布时间：2024年09月26日

`LLM应用` `计算机视觉` `人工智能`

> DARE: Diverse Visual Question Answering with Robustness Evaluation

# 摘要

> 视觉语言模型（VLM）不仅继承了文本和视觉模型的优势，还能处理多模态的视觉文本输入。尽管在图像分类和图文匹配等任务中表现优异，VLM 在计数和空间推理等关键视觉语言推理能力上仍显不足。此外，现有基准未能充分评估其对指令和评估协议变化的鲁棒性。为此，我们推出了 DARE，一个包含多样化视觉问答和鲁棒性评估的多项选择 VQA 基准。DARE 涵盖五个类别，并针对提示、答案选项、输出格式和正确答案数量进行四项鲁棒性测试。研究发现，最先进的 VLM 在多数类别中表现不佳，且在鲁棒性测试中难以维持最佳性能，最差情况下性能下降高达 34%。开源 VLM 如 LLaVA 1.6 和 Idefics2 的鲁棒性不及闭源模型如 GPT-4 和 Gemini，但后者同样对变化敏感。

> Vision Language Models (VLMs) extend remarkable capabilities of text-only large language models and vision-only models, and are able to learn from and process multi-modal vision-text input. While modern VLMs perform well on a number of standard image classification and image-text matching tasks, they still struggle with a number of crucial vision-language (VL) reasoning abilities such as counting and spatial reasoning. Moreover, while they might be very brittle to small variations in instructions and/or evaluation protocols, existing benchmarks fail to evaluate their robustness (or rather the lack of it). In order to couple challenging VL scenarios with comprehensive robustness evaluation, we introduce DARE, Diverse Visual Question Answering with Robustness Evaluation, a carefully created and curated multiple-choice VQA benchmark. DARE evaluates VLM performance on five diverse categories and includes four robustness-oriented evaluations based on the variations of: prompts, the subsets of answer options, the output format and the number of correct answers. Among a spectrum of other findings, we report that state-of-the-art VLMs still struggle with questions in most categories and are unable to consistently deliver their peak performance across the tested robustness evaluations. The worst case performance across the subsets of options is up to 34% below the performance in the standard case. The robustness of the open-source VLMs such as LLaVA 1.6 and Idefics2 cannot match the closed-source models such as GPT-4 and Gemini, but even the latter remain very brittle to different variations.

[Arxiv](https://arxiv.org/abs/2409.18023)