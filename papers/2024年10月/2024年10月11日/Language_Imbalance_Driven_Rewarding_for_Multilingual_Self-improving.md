# 多语言自我改进的奖励机制，由语言不平衡驱动

发布时间：2024年10月11日

`LLM应用` `人工智能` `语言学`

> Language Imbalance Driven Rewarding for Multilingual Self-improving

# 摘要

> 大型语言模型（LLM）在多项任务中表现卓越，但这些进步主要集中在英语和中文等主流语言，导致其他语言被忽视。这种不平衡不仅限制了应用范围，还自然地为语言间建立了偏好顺序，为 LLM 的多语言能力自我提升提供了契机。我们提出 $\textit{Language Imbalance Driven Rewarding}$，利用 LLM 中主流与非主流语言间的固有不平衡作为奖励信号。通过迭代 DPO 训练，这种方法不仅提升了非主流语言的表现，还增强了主流语言的能力，形成迭代奖励机制。对 Meta-Llama-3-8B-Instruct 进行两轮微调后，指令跟随和算术推理任务中的多语言性能显著提升，X-AlpacaEval 排行榜胜率平均提高 7.46%，MGSM 基准准确率提升 13.9%。这项研究为 LLM 的多语言自我改进奠定了基础。

> Large Language Models (LLMs) have achieved state-of-the-art performance across numerous tasks. However, these advancements have predominantly benefited "first-class" languages such as English and Chinese, leaving many other languages underrepresented. This imbalance, while limiting broader applications, generates a natural preference ranking between languages, offering an opportunity to bootstrap the multilingual capabilities of LLM in a self-improving manner. Thus, we propose $\textit{Language Imbalance Driven Rewarding}$, where the inherent imbalance between dominant and non-dominant languages within LLMs is leveraged as a reward signal. Iterative DPO training demonstrates that this approach not only enhances LLM performance in non-dominant languages but also improves the dominant language's capacity, thereby yielding an iterative reward signal. Fine-tuning Meta-Llama-3-8B-Instruct over two iterations of this approach results in continuous improvements in multilingual performance across instruction-following and arithmetic reasoning tasks, evidenced by an average improvement of 7.46% win rate on the X-AlpacaEval leaderboard and 13.9% accuracy on the MGSM benchmark. This work serves as an initial exploration, paving the way for multilingual self-improvement of LLMs.

[Arxiv](https://arxiv.org/abs/2410.08964)