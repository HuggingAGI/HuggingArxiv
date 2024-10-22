# Pangea：一款完全开放的多语言多模态 LLM，支持 39 种语言

发布时间：2024年10月21日

`LLM应用` `人工智能` `多语言技术`

> Pangea: A Fully Open Multilingual Multimodal LLM for 39 Languages

# 摘要

> 尽管多模态大型语言模型 (MLLM) 近期有所进展，但其发展主要集中在英语和西方数据集上，忽略了全球大多数语言和文化。本文介绍的 Pangea 是一种多语言多模态 LLM，基于涵盖 39 种语言的 600 万指令数据集 PangeaIns 训练。PangeaIns 包含高质量英语指令、精心翻译的指令和与文化相关的多模态任务，确保跨文化覆盖。为严格评估模型能力，我们推出了 PangeaBench，涵盖 14 个数据集，覆盖 47 种语言。结果表明，Pangea 在多语言和多样文化背景下显著优于现有开源模型。消融研究显示，英语数据比例、语言流行度和多模态训练样本数量对性能至关重要。我们完全开源数据、代码和训练检查点，以推动更广泛语言和文化范围内的公平和可及性。

> Despite recent advances in multimodal large language models (MLLMs), their development has predominantly focused on English- and western-centric datasets and tasks, leaving most of the world's languages and diverse cultural contexts underrepresented. This paper introduces Pangea, a multilingual multimodal LLM trained on PangeaIns, a diverse 6M instruction dataset spanning 39 languages. PangeaIns features: 1) high-quality English instructions, 2) carefully machine-translated instructions, and 3) culturally relevant multimodal tasks to ensure cross-cultural coverage. To rigorously assess models' capabilities, we introduce PangeaBench, a holistic evaluation suite encompassing 14 datasets covering 47 languages. Results show that Pangea significantly outperforms existing open-source models in multilingual settings and diverse cultural contexts. Ablation studies further reveal the importance of English data proportions, language popularity, and the number of multimodal training samples on overall performance. We fully open-source our data, code, and trained checkpoints, to facilitate the development of inclusive and robust multilingual MLLMs, promoting equity and accessibility across a broader linguistic and cultural spectrum.

[Arxiv](https://arxiv.org/abs/2410.16153)