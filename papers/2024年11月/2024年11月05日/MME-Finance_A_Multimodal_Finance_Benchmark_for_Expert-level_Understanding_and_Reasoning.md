# MME-Finance：用于专家级理解和推理的多模态金融基准

发布时间：2024年11月05日

`LLM应用` `多模态模型`

> MME-Finance: A Multimodal Finance Benchmark for Expert-level Understanding and Reasoning

# 摘要

> 近年来，通用领域的多模态基准已经引导了多模态模型在通用任务上的快速发展。然而，金融领域有其特殊性。它具有独特的图形图像（例如，烛台图表、技术指标图表），并拥有丰富的专业金融知识（例如，期货、换手率）。因此，来自通用领域的基准通常无法衡量金融领域中多模态模型的性能，因此不能有效地引导大型金融模型的快速发展。为了促进大型金融多模态模型的发展，我们提出了 MME-Finance，一个双语开放式和实用导向的视觉问答（VQA）基准。我们基准的特点是金融和专业性，包括构建反映用户实际使用需求的图表（例如，计算机截图和手机摄影），根据金融领域查询的偏好创建问题，并由具有 10 多年金融行业经验的专家注释问题。此外，我们开发了一个定制设计的金融评估系统，其中在多模态评估过程中首先引入视觉信息。对 19 个主流 MLLM 进行了广泛的实验评估，以测试它们的感知、推理和认知能力。结果表明，在通用基准上表现良好的模型在 MME-Finance 上表现不佳；例如，表现最好的开源和闭源模型分别获得 65.69（Qwen2VL-72B）和 63.18（GPT-4o）。它们在与金融最相关的类别，如烛台图表和技术指标图表方面表现特别差。此外，我们提出了一个中文版，有助于比较 MLLM 在中文语境下的性能。

> In recent years, multimodal benchmarks for general domains have guided the rapid development of multimodal models on general tasks. However, the financial field has its peculiarities. It features unique graphical images (e.g., candlestick charts, technical indicator charts) and possesses a wealth of specialized financial knowledge (e.g., futures, turnover rate). Therefore, benchmarks from general fields often fail to measure the performance of multimodal models in the financial domain, and thus cannot effectively guide the rapid development of large financial models. To promote the development of large financial multimodal models, we propose MME-Finance, an bilingual open-ended and practical usage-oriented Visual Question Answering (VQA) benchmark. The characteristics of our benchmark are finance and expertise, which include constructing charts that reflect the actual usage needs of users (e.g., computer screenshots and mobile photography), creating questions according to the preferences in financial domain inquiries, and annotating questions by experts with 10+ years of experience in the financial industry. Additionally, we have developed a custom-designed financial evaluation system in which visual information is first introduced in the multi-modal evaluation process. Extensive experimental evaluations of 19 mainstream MLLMs are conducted to test their perception, reasoning, and cognition capabilities. The results indicate that models performing well on general benchmarks cannot do well on MME-Finance; for instance, the top-performing open-source and closed-source models obtain 65.69 (Qwen2VL-72B) and 63.18 (GPT-4o), respectively. Their performance is particularly poor in categories most relevant to finance, such as candlestick charts and technical indicator charts. In addition, we propose a Chinese version, which helps compare performance of MLLMs under a Chinese context.

[Arxiv](https://arxiv.org/abs/2411.03314)