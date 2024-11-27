# “一心，多语”：深度剖析大型语言模型中的语言无关知识神经元

发布时间：2024年11月26日

`LLM理论` `语言模型` `知识神经元`

> One Mind, Many Tongues: A Deep Dive into Language-Agnostic Knowledge Neurons in Large Language Models

# 摘要

> 大型语言模型（LLMs）在大规模语料库上进行自监督预训练，从而获取了海量的事实知识。同时，LLMs 还展现出卓越的多语言能力，能够以多种语言来表达所学到的知识。然而，LLMs 里的知识存储机制依旧成谜。一些研究者尝试从知识神经元的角度来揭开 LLMs 中事实知识的神秘面纱，进而发现了以跨越语言障碍的形式存储事实知识的与语言无关的知识神经元。但初步成果存在两个局限：1）定位结果的高度不确定性。现有的研究仅运用基于提示的探测器为每个事实定位知识神经元，而 LLMs 无法针对语义等同的查询给出一致答案。所以，这致使定位结果不准确且不确定性高。2）对更多语言的分析缺失。该研究仅在英语和中文数据上对与语言无关的知识神经元进行分析，未探索更多语系和语言。这自然限制了研究发现的通用性。为解决上述问题，我们首先构建了一个名为重新表述的多语言 LAMA（RML-LAMA）的新基准，其中为每个事实都包含了高质量的填空式多语言并行查询。接着，我们提出了一种名为具有不确定性估计的多语言集成梯度（MATRICE）的新方法，它能在知识定位过程中对查询和语言的不确定性加以量化。大量实验表明，我们的方法能够精准定位与语言无关的知识神经元。我们还进一步探究了与语言无关的知识神经元在跨语言知识编辑、知识增强和新知识注入方面的作用。

> Large language models (LLMs) have learned vast amounts of factual knowledge through self-supervised pre-training on large-scale corpora. Meanwhile, LLMs have also demonstrated excellent multilingual capabilities, which can express the learned knowledge in multiple languages. However, the knowledge storage mechanism in LLMs still remains mysterious. Some researchers attempt to demystify the factual knowledge in LLMs from the perspective of knowledge neurons, and subsequently discover language-agnostic knowledge neurons that store factual knowledge in a form that transcends language barriers. However, the preliminary finding suffers from two limitations: 1) High Uncertainty in Localization Results. Existing study only uses a prompt-based probe to localize knowledge neurons for each fact, while LLMs cannot provide consistent answers for semantically equivalent queries. Thus, it leads to inaccurate localization results with high uncertainty. 2) Lack of Analysis in More Languages. The study only analyzes language-agnostic knowledge neurons on English and Chinese data, without exploring more language families and languages. Naturally, it limits the generalizability of the findings. To address aforementioned problems, we first construct a new benchmark called Rephrased Multilingual LAMA (RML-LAMA), which contains high-quality cloze-style multilingual parallel queries for each fact. Then, we propose a novel method named Multilingual Integrated Gradients with Uncertainty Estimation (MATRICE), which quantifies the uncertainty across queries and languages during knowledge localization. Extensive experiments show that our method can accurately localize language-agnostic knowledge neurons. We also further investigate the role of language-agnostic knowledge neurons in cross-lingual knowledge editing, knowledge enhancement and new knowledge injection.

[Arxiv](https://arxiv.org/abs/2411.17401)