# SPORTU：专为多模态大型语言模型设计的综合性体育理解基准

发布时间：2024年10月10日

`LLM应用` `人工智能`

> SPORTU: A Comprehensive Sports Understanding Benchmark for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLM) 通过融合文本与视觉信息，正逐步提升对复杂体育场景的推理能力。为全面评估其性能，我们推出了 SPORTU 基准，涵盖多层次体育推理任务。SPORTU 分为两大模块：SPORTU-text 包含 900 道多选题，附有人工注释，专注于规则与策略理解，测试模型仅通过问答进行体育推理的能力；SPORTU-video 则包含 1,701 个慢动作视频片段，涉及 7 种体育项目和 12,048 个问答对，评估从基础识别到复杂任务（如犯规检测与规则应用）的多层次推理。我们测试了四种主流 LLM，主要采用少样本学习并辅以思维链 (CoT) 提示，结果显示 GPT-4o 在 SPORTU-text 上达到 71% 的最高准确率，但仍未及人类水平，表明规则理解与推理能力有待提升。在 SPORTU-video 部分，Claude-3.5-Sonnet 在高难度任务上表现最佳，准确率仅为 52.6%，仍有巨大改进空间。我们期待 SPORTU 成为评估模型体育理解和推理能力的关键一步。

> Multimodal Large Language Models (MLLMs) are advancing the ability to reason about complex sports scenarios by integrating textual and visual information. To comprehensively evaluate their capabilities, we introduce SPORTU, a benchmark designed to assess MLLMs across multi-level sports reasoning tasks. SPORTU comprises two key components: SPORTU-text, featuring 900 multiple-choice questions with human-annotated explanations for rule comprehension and strategy understanding. This component focuses on testing models' ability to reason about sports solely through question-answering (QA), without requiring visual inputs; SPORTU-video, consisting of 1,701 slow-motion video clips across 7 different sports and 12,048 QA pairs, designed to assess multi-level reasoning, from simple sports recognition to complex tasks like foul detection and rule application. We evaluate four prevalent LLMs mainly utilizing few-shot learning paradigms supplemented by chain-of-thought (CoT) prompting on the SPORTU-text part. We evaluate four LLMs using few-shot learning and chain-of-thought (CoT) prompting on SPORTU-text. GPT-4o achieves the highest accuracy of 71%, but still falls short of human-level performance, highlighting room for improvement in rule comprehension and reasoning. The evaluation for the SPORTU-video part includes 7 proprietary and 6 open-source MLLMs. Experiments show that models fall short on hard tasks that require deep reasoning and rule-based understanding. Claude-3.5-Sonnet performs the best with only 52.6% accuracy on the hard task, showing large room for improvement. We hope that SPORTU will serve as a critical step toward evaluating models' capabilities in sports understanding and reasoning.

[Arxiv](https://arxiv.org/abs/2410.08474)