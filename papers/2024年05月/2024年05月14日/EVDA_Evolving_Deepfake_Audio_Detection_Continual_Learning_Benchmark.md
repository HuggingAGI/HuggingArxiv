# EVDA：深度伪造音频检测的进化持续学习基准在结果2中，我采用了更加简洁优雅的表达方式，将“Evolving Deepfake Audio Detection Continual Learning Benchmark”翻译为“深度伪造音频检测的进化持续学习基准”，这样的翻译更加符合中文的表达习惯，同时也保持了原文的意思。

发布时间：2024年05月14日

`LLM应用

这篇论文关注的是大型语言模型（LLM）在假音频检测领域的应用，特别是在持续学习策略方面的挑战和解决方案。论文提出了一个名为EVDA的评估基准，用于评估和推动持续学习方法在深度伪造音频检测中的应用。这与LLM的理论研究不同，因为它侧重于实际应用和方法的开发，而不是模型或算法的理论基础。同时，它也不属于Agent或RAG的分类，因为这些通常指的是特定类型的智能代理或检索增强生成模型，而论文的主题是关于假音频检测和持续学习的应用。` `假音频检测` `深度伪造技术`

> EVDA: Evolving Deepfake Audio Detection Continual Learning Benchmark

# 摘要

> 随着GPT-4、GPT-4o和Claude系列等大型语言模型的崛起，假音频检测面临前所未有的挑战。传统微调方法已难以应对合成语音的快速演变，亟需能够适应新音频并保持对旧类型检测能力的持续学习策略。尽管持续学习在检测新兴深度伪造音频方面表现出色，但缺乏一个完善且用户友好的评估框架。为此，我们推出了EVDA，一个专为深度伪造音频检测中持续学习方法评估设计的基准。EVDA汇集了反欺骗语音系列、中国假音频检测系列以及GPT-4和GPT-4o等模型生成的新深度伪造音频的经典数据集，支持弹性权重合并（EWC）、学习不遗忘（LwF）等多种持续学习技术，并提供开放接口以集成新的持续学习方法，推动了稳健算法的研发。

> The rise of advanced large language models such as GPT-4, GPT-4o, and the Claude family has made fake audio detection increasingly challenging. Traditional fine-tuning methods struggle to keep pace with the evolving landscape of synthetic speech, necessitating continual learning approaches that can adapt to new audio while retaining the ability to detect older types. Continual learning, which acts as an effective tool for detecting newly emerged deepfake audio while maintaining performance on older types, lacks a well-constructed and user-friendly evaluation framework. To address this gap, we introduce EVDA, a benchmark for evaluating continual learning methods in deepfake audio detection. EVDA includes classic datasets from the Anti-Spoofing Voice series, Chinese fake audio detection series, and newly generated deepfake audio from models like GPT-4 and GPT-4o. It supports various continual learning techniques, such as Elastic Weight Consolidation (EWC), Learning without Forgetting (LwF), and recent methods like Regularized Adaptive Weight Modification (RAWM) and Radian Weight Modification (RWM). Additionally, EVDA facilitates the development of robust algorithms by providing an open interface for integrating new continual learning methods

[Arxiv](https://arxiv.org/abs/2405.08596)