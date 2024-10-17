# PRefLexOR：基于偏好的递归语言建模，旨在探索性优化推理与代理思维

发布时间：2024年10月16日

`Agent` `生物材料科学` `人工智能`

> PRefLexOR: Preference-based Recursive Language Modeling for Exploratory Optimization of Reasoning and Agentic Thinking

# 摘要

> PRefLexOR 结合偏好优化与强化学习，使模型通过迭代推理自我提升。我们提出递归学习方法，让模型在训练和推理中多步骤推理、回顾并改进中间步骤，最终生成输出。模型首先通过优化对数几率，学习与准确决策路径对齐。PRefLexOR 构建动态知识图谱，从训练语料中情境化细节。第二阶段，偏好优化通过拒绝采样微调推理质量，同时生成现场训练数据并掩盖推理步骤。思考令牌框架内的递归优化引入迭代反馈，模型在其中改进推理，实现更深层次的一致性、连贯性和适应性。我们在仅30亿参数的小型语言模型中实现，表明微小模型也能自我教学，以更深入和反思的方式推理。实现简单，可融入任何预训练LLM。我们专注于生物材料科学，并在多种案例研究中展示方法。通过包含思考和反思的推理策略，构建多代理递归自我改进推理方法，通过重复采样逐步改进响应。

> PRefLexOR (Preference-based Recursive Language Modeling for Exploratory Optimization of Reasoning) combines preference optimization with concepts from Reinforcement Learning to enable models to self-teach through iterative reasoning improvements. We propose a recursive learning approach that engages the model in multi-step reasoning, revisiting, and refining intermediate steps before producing a final output in training and inference phases. Through multiple training stages, the model first learns to align its reasoning with accurate decision paths by optimizing the log odds between preferred and non-preferred responses. During this process, PRefLexOR builds a dynamic knowledge graph by generating questions from random text chunks and retrieval-augmentation to contextualize relevant details from the entire training corpus. In the second stage, preference optimization enhances model performance by using rejection sampling to fine-tune reasoning quality by continually producing in-situ training data while masking the reasoning steps. Recursive optimization within a thinking token framework introduces iterative feedback loops, where the model refines reasoning, achieving deeper coherence, consistency, and adaptability. Implemented in small language models with only 3 billion parameters, we should that even tiny models can iteratively teach themselves to reason with greater depth and reflectivity. Our implementation is straightforward and can be incorporated into any existing pretrained LLM. We focus our examples on applications in biological materials science and demonstrate the method in a variety of case studies that range from in-domain to cross-domain applications. Using reasoning strategies that include thinking and reflection modalities we build a multi-agent recursive self-improving inference approach to successively improve responses via repeated sampling in inference time.

[Arxiv](https://arxiv.org/abs/2410.12375)