# 博斯普鲁斯之桥：借助低资源语言适应与基准测试策略，推动土耳其大型语言模型的进步。

发布时间：2024年05月07日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在低资源语言（如土耳其语）中的应用和挑战，研究了训练策略、模型选择、数据可用性等因素对模型性能的影响，并进行了实验以评估这些因素。此外，论文还关注了跨语言知识转移和灾难性遗忘问题，这些都是LLM理论研究的重要方面。因此，这篇论文更倾向于LLM理论研究，而不是Agent、RAG或LLM应用。` `低资源语言`

> Bridging the Bosphorus: Advancing Turkish Large Language Models through Strategies for Low-Resource Language Adaptation and Benchmarking

# 摘要

> 大型语言模型（LLMs）在多领域的重要性日益凸显，特别是在代表性不足的语言中，高质量模型的需求迫在眉睫。本研究深入探讨了低资源语言如土耳其语所面临的挑战，包括数据匮乏、模型选择、评估和计算限制。我们评估了训练策略、模型选择和数据可用性对LLMs性能的影响，并采用了两种策略：一是将英语预训练的LLMs适应于土耳其语，二是利用土耳其语数据从头构建模型，两者均通过监督微调提升推理能力。我们创建了一个土耳其LLMs的新排行榜，通过评估推理和知识技能的基准来衡量这些方法的性能。同时，我们在预训练和微调中进行了数据和模型的缩放实验，强调了跨语言知识转移的重要性，并解决了在不同语言微调时可能出现的灾难性遗忘问题。我们的目标是为低资源语言环境中的LLM发展提供详尽指南，以期让自然语言处理（NLP）的益处惠及全球。

> Large Language Models (LLMs) are becoming crucial across various fields, emphasizing the urgency for high-quality models in underrepresented languages. This study explores the unique challenges faced by low-resource languages, such as data scarcity, model selection, evaluation, and computational limitations, with a special focus on Turkish. We conduct an in-depth analysis to evaluate the impact of training strategies, model choices, and data availability on the performance of LLMs designed for underrepresented languages. Our approach includes two methodologies: (i) adapting existing LLMs originally pretrained in English to understand Turkish, and (ii) developing a model from the ground up using Turkish pretraining data, both supplemented with supervised fine-tuning on a novel Turkish instruction-tuning dataset aimed at enhancing reasoning capabilities. The relative performance of these methods is evaluated through the creation of a new leaderboard for Turkish LLMs, featuring benchmarks that assess different reasoning and knowledge skills. Furthermore, we conducted experiments on data and model scaling, both during pretraining and fine-tuning, simultaneously emphasizing the capacity for knowledge transfer across languages and addressing the challenges of catastrophic forgetting encountered during fine-tuning on a different language. Our goal is to offer a detailed guide for advancing the LLM framework in low-resource linguistic contexts, thereby making natural language processing (NLP) benefits more globally accessible.

[Arxiv](https://arxiv.org/abs/2405.04685)