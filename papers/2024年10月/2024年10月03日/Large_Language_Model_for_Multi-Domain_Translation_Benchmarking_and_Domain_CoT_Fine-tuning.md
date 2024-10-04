# 大型语言模型在多领域翻译中的应用：基准测试与领域 CoT 微调

发布时间：2024年10月03日

`LLM应用` `机器翻译` `人工智能`

> Large Language Model for Multi-Domain Translation: Benchmarking and Domain CoT Fine-tuning

# 摘要

> 在多领域实现高质量机器翻译仍是一大挑战，主要因各领域平行训练数据有限且不均。尽管 LLMs 展现了强大的通用理解和生成能力，但其在多领域 MT 中的潜力尚待挖掘。我们构建了涵盖 15 个领域的多领域翻译基准，包括 25 个德英和 22 个中英测试集。评估显示，LLMs 在多领域 MT 中表现不及传统系统，微调后易出现领域过拟合和灾难性遗忘。为此，我们提出领域思维链 (CoT) 微调技术，利用 LLMs 的多领域智能提升翻译性能。该方法使 LLM 能从源文本中感知领域信息，进而指导翻译。尽管仅在四个领域的小数据集上训练，CoT 微调在翻译准确性和领域鲁棒性上显著优于传统微调，德英跨领域测试中平均 BLEU 分数提升 1.53 分。

> Achieving consistent high-quality machine translation (MT) across diverse domains remains a significant challenge, primarily due to the limited and imbalanced parallel training data available in various domains. While large language models (LLMs) have demonstrated impressive general understanding and generation abilities, their potential in multi-domain MT is under-explored. We establish a comprehensive benchmark for multi-domain translation, featuring 25 German$\Leftrightarrow$English and 22 Chinese$\Leftrightarrow$English test sets respectively covering 15 domains. Our evaluation of prominent LLMs reveals a discernible performance gap against traditional MT systems, highlighting domain overfitting and catastrophic forgetting issues after fine-tuning on domain-limited corpora. To mitigate this, we propose a domain Chain of Thought (CoT) fine-tuning technique that utilizes the intrinsic multi-domain intelligence of LLMs to improve translation performance. This method inspires the LLM to perceive domain information from the source text, which then serves as a helpful hint to guide the translation process. Despite being trained on a small dataset of four domains, our CoT fine-tune approach achieves notable enhancements in translation accuracy and domain robustness than traditional fine-tuning, as evidenced by an average 1.53 BLEU score increase in over 20 German$\rightarrow$English distinct out-of-domain tests.

[Arxiv](https://arxiv.org/abs/2410.02631)