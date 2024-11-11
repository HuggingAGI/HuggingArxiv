# 用于领域生成算法检测的大型语言模型

发布时间：2024年11月05日

`LLM应用` `网络安全` `域名检测`

> LLMs for Domain Generation Algorithm Detection

# 摘要

> 这项工作分析了大型语言模型（LLMs）在检测域名生成算法（DGAs）方面的使用。我们对两种重要技术进行了详细评估：上下文学习（ICL）和有监督微调（SFT），展示了它们如何提高检测效果。SFT通过使用特定领域的数据来提高性能，而ICL帮助检测模型在不需要大量重新训练的情况下快速适应新的威胁。我们使用Meta的Llama3 8B模型，在一个包含68个恶意软件家族和正常域名的自定义数据集上，涵盖了几种难以检测的方案，包括最近基于单词的DGAs。结果证明，基于LLM的方法在DGA检测中可以取得有竞争力的结果。特别是，基于SFT的LLM DGA检测器优于使用注意力层的最先进模型，准确率达到94％，误报率（FPR）为4％，并且在检测基于单词的DGA域名方面表现出色。

> This work analyzes the use of large language models (LLMs) for detecting domain generation algorithms (DGAs). We perform a detailed evaluation of two important techniques: In-Context Learning (ICL) and Supervised Fine-Tuning (SFT), showing how they can improve detection. SFT increases performance by using domain-specific data, whereas ICL helps the detection model to quickly adapt to new threats without requiring much retraining. We use Meta's Llama3 8B model, on a custom dataset with 68 malware families and normal domains, covering several hard-to-detect schemes, including recent word-based DGAs. Results proved that LLM-based methods can achieve competitive results in DGA detection. In particular, the SFT-based LLM DGA detector outperforms state-of-the-art models using attention layers, achieving 94% accuracy with a 4% false positive rate (FPR) and excelling at detecting word-based DGA domains.

[Arxiv](https://arxiv.org/abs/2411.03307)