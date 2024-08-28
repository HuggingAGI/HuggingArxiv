# 探索对齐大型语言模型中对抗性后缀的转移学习进展

发布时间：2024年08月27日

`LLM应用` `网络安全` `人工智能`

> Advancing Adversarial Suffix Transfer Learning on Aligned Large Language Models

# 摘要

> 语言模型（LLM）因恶意用户的潜在滥用而面临安全挑战。最新研究通过红色团队测试，发现了能利用贪婪坐标梯度（GCG）算法破解LLM的对抗性后缀。但GCG的计算效率低下，阻碍了对后缀跨模型和数据的可转移性及扩展性的深入研究。为此，我们构建了搜索效率与后缀可转移性的桥梁，提出了两阶段迁移学习框架DeGCG，将搜索过程细分为预搜索（行为无关）和后搜索（行为相关），并在预搜索阶段实施直接的第一目标令牌优化以加速搜索。该方法在跨模型、跨数据及自转移场景中得到应用，并进一步发展为交错变体i-DeGCG，通过迭代利用自转移性提升搜索速度。HarmBench实验显示，i-DeGCG在Llama2-chat-7b模型上表现卓越，验证集与测试集的ASR分别提升至$43.9$和$39.0$。深入分析表明，第一目标令牌优化对于高效利用后缀可转移性至关重要。

> Language Language Models (LLMs) face safety concerns due to potential misuse by malicious users. Recent red-teaming efforts have identified adversarial suffixes capable of jailbreaking LLMs using the gradient-based search algorithm Greedy Coordinate Gradient (GCG). However, GCG struggles with computational inefficiency, limiting further investigations regarding suffix transferability and scalability across models and data. In this work, we bridge the connection between search efficiency and suffix transferability. We propose a two-stage transfer learning framework, DeGCG, which decouples the search process into behavior-agnostic pre-searching and behavior-relevant post-searching. Specifically, we employ direct first target token optimization in pre-searching to facilitate the search process. We apply our approach to cross-model, cross-data, and self-transfer scenarios. Furthermore, we introduce an interleaved variant of our approach, i-DeGCG, which iteratively leverages self-transferability to accelerate the search process. Experiments on HarmBench demonstrate the efficiency of our approach across various models and domains. Notably, our i-DeGCG outperforms the baseline on Llama2-chat-7b with ASRs of $43.9$ ($+22.2$) and $39.0$ ($+19.5$) on valid and test sets, respectively. Further analysis on cross-model transfer indicates the pivotal role of first target token optimization in leveraging suffix transferability for efficient searching.

[Arxiv](https://arxiv.org/abs/2408.14866)