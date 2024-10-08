# Lens：重新审视大型语言模型的多语言增强策略

发布时间：2024年10月06日

`LLM理论` `人工智能` `语言技术`

> Lens: Rethinking Multilingual Enhancement for Large Language Models

# 摘要

> 尽管全球对服务于多语言用户的大型语言模型 (LLM) 需求日益增长，但大多数尖端 LLM 仍以英语为主。这导致了语言间的性能差距，限制了非英语用户的高级 AI 服务访问。当前的多语言能力提升方法主要依赖数据驱动的后训练技术，如多语言指令调优或持续预训练，但面临高质量多语言数据集稀缺和多语言能力提升有限的挑战，常出现偏离目标和中心语言能力遗忘的问题。为此，我们提出 Lens，一种利用 LLM 内部语言表示空间增强多语言能力的新方法。Lens 通过操纵 LLM 顶层中的语言无关和语言特定子空间的隐藏表示，使用中心语言作为支点，在语言无关子空间中拉近目标语言，继承已建立的语义表示；在语言特定子空间中，分开目标和中心语言的表示，使目标语言独特表达。在以英语为中心和多语言 LLM 的广泛实验中，Lens 有效提升多语言性能，不牺牲原始中心语言能力，以更少计算资源实现卓越结果。

> Despite the growing global demand for large language models (LLMs) that serve users from diverse linguistic backgrounds, most cutting-edge LLMs remain predominantly English-centric. This creates a performance gap across languages, restricting access to advanced AI services for non-English speakers. Current methods to enhance multilingual capabilities largely rely on data-driven post-training techniques, such as multilingual instruction tuning or continual pre-training. However, these approaches encounter significant challenges, including the scarcity of high-quality multilingual datasets and the limited enhancement of multilingual capabilities. They often suffer from off-target issues and catastrophic forgetting of central language abilities. To this end, we propose Lens, a novel approach to enhance multilingual capabilities of LLMs by leveraging their internal language representation spaces. Specially, Lens operates by manipulating the hidden representations within the language-agnostic and language-specific subspaces from top layers of LLMs. Using the central language as a pivot, the target language is drawn closer to it within the language-agnostic subspace, allowing it to inherit well-established semantic representations. Meanwhile, in the language-specific subspace, the representations of the target and central languages are pushed apart, enabling the target language to express itself distinctly. Extensive experiments on one English-centric and two multilingual LLMs demonstrate that Lens effectively improves multilingual performance without sacrificing the original central language capabilities of the backbone model, achieving superior results with much fewer computational resources compared to existing post-training approaches.

[Arxiv](https://arxiv.org/abs/2410.04407)