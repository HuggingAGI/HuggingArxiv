# 通过知识增强的跨模态提示模型实现少样本联合多模态实体关系提取

发布时间：2024年10月18日

`LLM应用` `社交媒体`

> Few-Shot Joint Multimodal Entity-Relation Extraction via Knowledge-Enhanced Cross-modal Prompt Model

# 摘要

> 联合多模态实体关系提取（JMERE）任务旨在从社交媒体的图文对中提取实体及其关系，极具挑战性。现有方法依赖大量标注数据，但收集和标注细粒度的多模态数据困难重重。为此，我们首先构建了适应原始数据分布的多样化少样本数据集。为弥补少样本设置中的信息不足，我们提出了知识增强跨模态提示模型（KECPM），通过引导大型语言模型生成补充背景知识，有效解决问题。我们的方法分两阶段进行：首先，根据语义相似性动态生成提示，引导ChatGPT生成相关知识，并通过自我反思完善；其次，将生成的知识与原始输入融合，利用transformer模型与JMERE的输出格式对齐。实验表明，我们的方法在少样本数据集上表现优异，F$_1$分数显著超越基线。定性分析和案例研究进一步验证了模型的有效性。

> Joint Multimodal Entity-Relation Extraction (JMERE) is a challenging task that aims to extract entities and their relations from text-image pairs in social media posts. Existing methods for JMERE require large amounts of labeled data. However, gathering and annotating fine-grained multimodal data for JMERE poses significant challenges. Initially, we construct diverse and comprehensive multimodal few-shot datasets fitted to the original data distribution. To address the insufficient information in the few-shot setting, we introduce the \textbf{K}nowledge-\textbf{E}nhanced \textbf{C}ross-modal \textbf{P}rompt \textbf{M}odel (KECPM) for JMERE. This method can effectively address the problem of insufficient information in the few-shot setting by guiding a large language model to generate supplementary background knowledge. Our proposed method comprises two stages: (1) a knowledge ingestion stage that dynamically formulates prompts based on semantic similarity guide ChatGPT generating relevant knowledge and employs self-reflection to refine the knowledge; (2) a knowledge-enhanced language model stage that merges the auxiliary knowledge with the original input and utilizes a transformer-based model to align with JMERE's required output format. We extensively evaluate our approach on a few-shot dataset derived from the JMERE dataset, demonstrating its superiority over strong baselines in terms of both micro and macro F$_1$ scores. Additionally, we present qualitative analyses and case studies to elucidate the effectiveness of our model.

[Arxiv](https://arxiv.org/abs/2410.14225)