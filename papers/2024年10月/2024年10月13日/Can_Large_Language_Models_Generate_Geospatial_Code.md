# 大型语言模型能否编写地理空间代码？

发布时间：2024年10月13日

`LLM应用` `地理信息系统` `软件开发`

> Can Large Language Models Generate Geospatial Code?

# 摘要

> 随着时空数据处理和地理建模需求的增加，自动化地理空间代码生成变得至关重要。尽管大型语言模型（LLMs）在代码生成方面潜力巨大，但仍面临领域知识不足和“编码幻觉”等挑战。为此，我们推出了GeoCode-Eval（GCE）框架，从“认知与记忆”、“理解与解释”、“创新与创造”三个维度，评估LLMs在八个能力级别上的地理空间代码生成能力。我们还创建了GeoCode-Bench基准数据集，包含多种题型，涵盖代码生成的各个方面。通过该数据集，我们评估了多种LLMs和专门代码生成模型，并进行了多种学习与推理实验。此外，我们还微调了Code LLaMA-7B模型，创建了GEECode-GPT，并验证了其在代码生成中的表现。实验结果显示，构建预训练和指令数据集能显著提升代码生成质量，为优化特定领域LLMs提供了宝贵经验。

> With the growing demand for spatiotemporal data processing and geospatial modeling, automating geospatial code generation has become essential for productivity. Large language models (LLMs) show promise in code generation but face challenges like domain-specific knowledge gaps and "coding hallucinations." This paper introduces GeoCode-Eval (GCE), a framework for assessing LLMs' ability to generate geospatial code across three dimensions: "Cognition and Memory," "Comprehension and Interpretation," and "Innovation and Creation," distributed across eight capability levels. We developed a benchmark dataset, GeoCode-Bench, consisting of 5,000 multiple-choice, 1,500 fill-in-the-blank, 1,500 true/false questions, and 1,000 subjective tasks covering code summarization, generation, completion, and correction. Using GeoCode-Bench, we evaluated three commercial closed-source LLMs, four open-source general-purpose LLMs, and 14 specialized code generation models. We also conducted experiments on few-shot and zero-shot learning, Chain of Thought reasoning, and multi-round majority voting to measure their impact on geospatial code generation. Additionally, we fine-tuned the Code LLaMA-7B model using Google Earth Engine-related JavaScript, creating GEECode-GPT, and evaluated it on subjective tasks. Results show that constructing pre-training and instruction datasets significantly improves code generation, offering insights for optimizing LLMs in specific domains.

[Arxiv](https://arxiv.org/abs/2410.09738)