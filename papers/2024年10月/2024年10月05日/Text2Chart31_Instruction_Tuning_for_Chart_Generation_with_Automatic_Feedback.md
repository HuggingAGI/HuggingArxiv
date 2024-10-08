# Text2Chart31：通过自动反馈进行图表生成的指令调优

发布时间：2024年10月05日

`LLM应用` `数据可视化` `人工智能`

> Text2Chart31: Instruction Tuning for Chart Generation with Automatic Feedback

# 摘要

> 大型语言模型（LLM）在多种语言任务中表现出色，尤其得益于指令调优方法。然而，LLM 在处理复杂现实数据的图表可视化时遇到难题。现有数据集缺乏多样性，且监督微调未能充分挖掘数据间的深层关系。为此，我们设计了分层管道和全新数据集 Text2Chart31，涵盖 31 种图表类型，包含 11.1K 个数据元组。我们还创新性地采用强化学习进行指令调优，无需人工反馈。实验结果显示，这种方法大幅提升模型性能，使小型模型在数据可视化任务中超越大型开源模型，甚至媲美顶尖专有模型。代码和数据集已公开在 https://github.com/fatemehpesaran310/Text2Chart31。

> Large language models (LLMs) have demonstrated strong capabilities across various language tasks, notably through instruction-tuning methods. However, LLMs face challenges in visualizing complex, real-world data through charts and plots. Firstly, existing datasets rarely cover a full range of chart types, such as 3D, volumetric, and gridded charts. Secondly, supervised fine-tuning methods do not fully leverage the intricate relationships within rich datasets, including text, code, and figures. To address these challenges, we propose a hierarchical pipeline and a new dataset for chart generation. Our dataset, Text2Chart31, includes 31 unique plot types referring to the Matplotlib library, with 11.1K tuples of descriptions, code, data tables, and plots. Moreover, we introduce a reinforcement learning-based instruction tuning technique for chart generation tasks without requiring human feedback. Our experiments show that this approach significantly enhances the model performance, enabling smaller models to outperform larger open-source models and be comparable to state-of-the-art proprietary models in data visualization tasks. We make the code and dataset available at https://github.com/fatemehpesaran310/Text2Chart31.

[Arxiv](https://arxiv.org/abs/2410.04064)