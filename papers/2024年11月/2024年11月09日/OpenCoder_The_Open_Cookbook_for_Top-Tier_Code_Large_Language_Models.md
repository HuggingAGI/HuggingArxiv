# OpenCoder：顶级代码大型语言模型的开放食谱

发布时间：2024年11月09日

`LLM应用` `人工智能`

> OpenCoder: The Open Cookbook for Top-Tier Code Large Language Models

# 摘要

> 大型语言模型（LLM）在代码方面已在包括代码生成、推理任务和代理系统等各个领域变得不可或缺。虽然开放获取的代码 LLM 越来越接近专有模型的性能水平，但适合严格科学研究的高质量代码 LLM，特别是那些具有可重现的数据处理管道和透明训练协议的模型，仍然有限。这种稀缺是由于各种挑战造成的，包括资源限制、伦理考虑以及保持模型先进的竞争优势。为了解决这一差距，我们引入了 OpenCoder，这是一个顶级的代码 LLM，不仅实现了与领先模型相当的性能，而且还为研究社区充当了一个“开放的食谱”。与大多数先前的努力不同，我们不仅发布了模型权重和推理代码，还发布了可重现的训练数据、完整的数据处理管道、严格的实验消融结果以及用于开放科学研究的详细训练协议。通过这种全面的发布，我们确定了构建顶级代码 LLM 的关键要素：（1）用于数据清理的代码优化启发式规则和数据去重方法，（2）与代码相关的文本语料库的召回，（3）在退火和监督微调阶段的高质量合成数据。通过提供这种程度的开放性，我们旨在拓宽对顶级代码 LLM 各个方面的访问，使 OpenCoder 既成为一个强大的模型，又成为加速研究的开放基础，并在代码 AI 中实现可重现的进步。

> Large language models (LLMs) for code have become indispensable in various domains, including code generation, reasoning tasks and agent systems. While open-access code LLMs are increasingly approaching the performance levels of proprietary models, high-quality code LLMs suitable for rigorous scientific investigation, particularly those with reproducible data processing pipelines and transparent training protocols, remain limited. The scarcity is due to various challenges, including resource constraints, ethical considerations, and the competitive advantages of keeping models advanced. To address the gap, we introduce OpenCoder, a top-tier code LLM that not only achieves performance comparable to leading models but also serves as an "open cookbook" for the research community. Unlike most prior efforts, we release not only model weights and inference code, but also the reproducible training data, complete data processing pipeline, rigorous experimental ablation results, and detailed training protocols for open scientific research. Through this comprehensive release, we identify the key ingredients for building a top-tier code LLM: (1) code optimized heuristic rules for data cleaning and methods for data deduplication, (2) recall of text corpus related to code and (3) high-quality synthetic data in both annealing and supervised fine-tuning stages. By offering this level of openness, we aim to broaden access to all aspects of a top-tier code LLM, with OpenCoder serving as both a powerful model and an open foundation to accelerate research, and enable reproducible advancements in code AI.

[Arxiv](https://arxiv.org/abs/2411.04905)