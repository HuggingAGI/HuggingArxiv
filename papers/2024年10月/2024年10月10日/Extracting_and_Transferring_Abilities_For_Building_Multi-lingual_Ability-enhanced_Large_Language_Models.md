# 构建多语言能力增强的大型语言模型，关键在于提取和转移能力。

发布时间：2024年10月10日

`LLM理论` `人工智能`

> Extracting and Transferring Abilities For Building Multi-lingual Ability-enhanced Large Language Models

# 摘要

> 多语言能力迁移在 LLM 的广泛应用中愈发重要。现有方法依赖于多语言能力相关数据的训练，但这不适用于低资源语言。为此，我们提出了 MAET 方法，通过分解和提取与语言无关的能力权重，实现跨语言的简单迁移，无需额外训练。MAET 分为提取和迁移两个阶段：首先定位关键神经元，提取可迁移的能力权重；然后选择能力相关参数，设计合并策略，构建多语言能力增强的 LLM。实验证明，MAET 在数学和科学任务中表现优异，超越了传统训练方法。代码和数据详见 \url{https://github.com/RUCAIBox/MAET}。

> Multi-lingual ability transfer has become increasingly important for the broad application of large language models (LLMs). Existing work highly relies on training with the multi-lingual ability-related data, which may be not available for low-resource languages. To solve it, we propose a Multi-lingual Ability Extraction and Transfer approach, named as MAET. Our key idea is to decompose and extract language-agnostic ability-related weights from LLMs, and transfer them across different languages by simple addition and subtraction operations without training. Specially, our MAET consists of the extraction and transfer stages. In the extraction stage, we firstly locate key neurons that are highly related to specific abilities, and then employ them to extract the transferable ability-specific weights. In the transfer stage, we further select the ability-related parameter tensors, and design the merging strategy based on the linguistic and ability specific weights, to build the multi-lingual ability-enhanced LLM. To demonstrate the effectiveness of our proposed approach, we conduct extensive experiments on mathematical and scientific tasks in both high-resource lingual and low-resource lingual scenarios. Experiment results have shown that MAET can effectively and efficiently extract and transfer the advanced abilities, and outperform training-based baseline methods. Our code and data are available at \url{https://github.com/RUCAIBox/MAET}.

[Arxiv](https://arxiv.org/abs/2410.07825)