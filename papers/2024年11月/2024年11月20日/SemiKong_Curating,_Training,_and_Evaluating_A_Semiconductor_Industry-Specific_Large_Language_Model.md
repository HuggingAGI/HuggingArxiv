# SemiKong：对一个半导体行业专用的大型语言模型进行策划、训练与评估

发布时间：2024年11月20日

`LLM应用` `半导体` `人工智能`

> SemiKong: Curating, Training, and Evaluating A Semiconductor Industry-Specific Large Language Model

# 摘要

> 大型语言模型（LLMs）展现出了解决半导体行业部分问题的潜力。但它们多为通用模型，缺少应对该行业独特挑战（如半导体器件和工艺的复杂物理化学）所需的专业知识。SemiKong 作为半导体领域的首个行业专用 LLM，为开发定制的专有模型奠定了基础。凭借 SemiKong 1.0，我们致力于打造一个能在专家级别理解蚀刻问题的基础模型。我们的关键贡献有：（a）整理了全面的半导体相关文本库；（b）创建了具有深度半导体知识的基础模型；（c）引入了整合专家知识的框架，进而推动特定领域 AI 模型的评估进程。通过使用我们整理的数据集对预训练的 LLM 进行微调，我们证明 SemiKong 在各类半导体制造和设计任务中比更大的通用 LLMs 表现更优。我们大量的实验凸显了开发特定领域 LLM 作为公司或工具专用专有模型基础的重要性，为半导体领域的进一步研究和应用铺平了道路。代码和数据集可在 https://github.com/aitomatic/semikong 获取。

> Large Language Models (LLMs) have demonstrated the potential to address some issues within the semiconductor industry. However, they are often general-purpose models that lack the specialized knowledge needed to tackle the unique challenges of this sector, such as the intricate physics and chemistry of semiconductor devices and processes. SemiKong, the first industry-specific LLM for the semiconductor domain, provides a foundation that can be used to develop tailored proprietary models. With SemiKong 1.0, we aim to develop a foundational model capable of understanding etching problems at an expert level. Our key contributions include (a) curating a comprehensive corpus of semiconductor-related texts, (b) creating a foundational model with in-depth semiconductor knowledge, and (c) introducing a framework for integrating expert knowledge, thereby advancing the evaluation process of domain-specific AI models. Through fine-tuning a pre-trained LLM using our curated dataset, we have shown that SemiKong outperforms larger, general-purpose LLMs in various semiconductor manufacturing and design tasks. Our extensive experiments underscore the importance of developing domain-specific LLMs as a foundation for company- or tool-specific proprietary models, paving the way for further research and applications in the semiconductor domain. Code and dataset will be available at https://github.com/aitomatic/semikong

[Arxiv](https://arxiv.org/abs/2411.13802)