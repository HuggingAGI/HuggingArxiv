# 利用大型语言模型优化 HPV 疫苗怀疑论和错误信息的社交媒体标注：关于跨多个模型的上下文学习和微调立场检测的实验评估

发布时间：2024年11月21日

`LLM应用` `社交媒体`

> Optimizing Social Media Annotation of HPV Vaccine Skepticism and Misinformation Using Large Language Models: An Experimental Evaluation of In-Context Learning and Fine-Tuning Stance Detection Across Multiple Models

# 摘要

> 这篇论文借助大型语言模型（LLMs），通过实验来确定扩大 HPV 疫苗相关推文的社交媒体内容标注以进行立场检测的最佳策略。我们对传统的微调方法和新兴的上下文学习方法均进行了研究，系统地改变了广泛使用的 LLMs 及其变体（如 GPT4、Mistral 和 Llama3 等）的提示工程策略。具体来说，我们在提示模板设计、样本抽样方法和样本数量上做出改变，以检测关于 HPV 疫苗接种的立场。我们的发现显示：1. 总体而言，在 HPV 疫苗社交媒体内容的立场检测中，上下文学习的表现优于微调；2. 增加样本数量并非必然能提升所有模型的性能；3. 不同的 LLMs 及其变体对上下文学习条件的敏感度各异。我们发现，针对 HPV 疫苗推文立场检测的最优上下文学习配置包含六个分层样本以及详细的上下文提示。此项研究凸显了潜力，并为将 LLMs 应用于社交媒体立场和怀疑检测研究提供了可行的方法。

> This paper leverages large-language models (LLMs) to experimentally determine optimal strategies for scaling up social media content annotation for stance detection on HPV vaccine-related tweets. We examine both conventional fine-tuning and emergent in-context learning methods, systematically varying strategies of prompt engineering across widely used LLMs and their variants (e.g., GPT4, Mistral, and Llama3, etc.). Specifically, we varied prompt template design, shot sampling methods, and shot quantity to detect stance on HPV vaccination. Our findings reveal that 1) in general, in-context learning outperforms fine-tuning in stance detection for HPV vaccine social media content; 2) increasing shot quantity does not necessarily enhance performance across models; and 3) different LLMs and their variants present differing sensitivity to in-context learning conditions. We uncovered that the optimal in-context learning configuration for stance detection on HPV vaccine tweets involves six stratified shots paired with detailed contextual prompts. This study highlights the potential and provides an applicable approach for applying LLMs to research on social media stance and skepticism detection.

[Arxiv](https://arxiv.org/abs/2411.14720)