# FEEL 是一个专门针对大型语言模型（LLMs）的情感支持能力评估框架，旨在深入探究和量化LLMs在提供情绪支持方面的表现。

发布时间：2024年03月22日

`LLM应用` `情感计算` `聊天机器人`

> FEEL: A Framework for Evaluating Emotional Support Capability with Large Language Models

# 摘要

> ESC对话能够有效舒缓用户情绪压力，但因情绪分析中的主观因素，传统非人工评估手段难以准确评判其情感支持效能，且评估指标与人判存在低关联度，加之人工评估成本极高。为此，我们创新设计了一款名为FEEL的评估模型，巧妙运用LLMs作为评估工具，从多角度细致考察ESC的情感支持特性，从而提供更为全面、精准的评估方案。模型还引入概率分布方法确保结果稳定性，并结合集成学习策略，通过为多个LLMs分配权重以提升评估精确度。为了验证FEEL的有效性，我们在现有ESC对话数据上开展了大量实验，实验证明相较于基础模型，FEEL在与人判一致性上的提升显著。您可访问https://github.com/Ansisy/FEEL查看我们的源代码。

> Emotional Support Conversation (ESC) is a typical dialogue that can effec-tively assist the user in mitigating emotional pressures. However, owing to the inherent subjectivity involved in analyzing emotions, current non-artificial methodologies face challenges in effectively appraising the emo-tional support capability. These metrics exhibit a low correlation with human judgments. Concurrently, manual evaluation methods extremely will cause high costs. To solve these problems, we propose a novel model FEEL (Framework for Evaluating Emotional Support Capability with Large Lan-guage Models), employing Large Language Models (LLMs) as evaluators to assess emotional support capabilities. The model meticulously considers var-ious evaluative aspects of ESC to apply a more comprehensive and accurate evaluation method for ESC. Additionally, it employs a probability distribu-tion approach for a more stable result and integrates an ensemble learning strategy, leveraging multiple LLMs with assigned weights to enhance evalua-tion accuracy. To appraise the performance of FEEL, we conduct extensive experiments on existing ESC model dialogues. Experimental results demon-strate our model exhibits a substantial enhancement in alignment with human evaluations compared to the baselines. Our source code is available at https://github.com/Ansisy/FEEL.

[Arxiv](https://arxiv.org/abs/2403.15699)