# ERVQA：一款专为评估大型视觉语言模型在医院环境中的应用准备度而设计的基准数据集

发布时间：2024年10月08日

`LLM应用` `人工智能`

> ERVQA: A Dataset to Benchmark the Readiness of Large Vision Language Models in Hospital Environments

# 摘要

> 全球医疗工作者短缺催生了智能医疗助手的开发，这些助手能在必要时监控并提醒医疗工作者。我们通过医院环境中的视觉问答（VQA）任务，利用专家注释的开放式问题，评估现有大型视觉语言模型（LVLMs）的医疗知识。我们推出了急诊室视觉问答（ERVQA）数据集，包含涵盖多种急诊场景的<图像，问题，答案>三元组，为LVLMs设立了新基准。通过细致的错误分类和答案趋势分析，我们揭示了任务的复杂性。我们采用传统及适应性VQA指标（如蕴涵分数和CLIPScore置信度）对最先进的开源和封闭LVLMs进行基准测试。分析模型间的错误，我们根据解码器类型、模型大小和上下文示例等属性推断趋势。研究结果显示，ERVQA数据集任务极为复杂，凸显了开发专门领域解决方案的必要性。

> The global shortage of healthcare workers has demanded the development of smart healthcare assistants, which can help monitor and alert healthcare workers when necessary. We examine the healthcare knowledge of existing Large Vision Language Models (LVLMs) via the Visual Question Answering (VQA) task in hospital settings through expert annotated open-ended questions. We introduce the Emergency Room Visual Question Answering (ERVQA) dataset, consisting of <image, question, answer> triplets covering diverse emergency room scenarios, a seminal benchmark for LVLMs. By developing a detailed error taxonomy and analyzing answer trends, we reveal the nuanced nature of the task. We benchmark state-of-the-art open-source and closed LVLMs using traditional and adapted VQA metrics: Entailment Score and CLIPScore Confidence. Analyzing errors across models, we infer trends based on properties like decoder type, model size, and in-context examples. Our findings suggest the ERVQA dataset presents a highly complex task, highlighting the need for specialized, domain-specific solutions.

[Arxiv](https://arxiv.org/abs/2410.06420)