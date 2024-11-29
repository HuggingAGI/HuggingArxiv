# 运用 LoRA PEFT 调优让多语言 LLMs 适应低资源语言时所遭遇的挑战

发布时间：2024年11月27日

`LLM应用` `语言模型` `低资源语言`

> Challenges in Adapting Multilingual LLMs to Low-Resource Languages using LoRA PEFT Tuning

# 摘要

> 大型语言模型（LLMs）展现出了出色的多语言能力，然而在将其适配到低资源语言时仍面临挑战。本研究探讨了低秩适应（LoRA）参数高效微调（PEFT）对马拉地语这种资源有限语言的多语言 Gemma 模型的影响。通过使用包含 52,000 个指令 - 响应对的翻译后的 Alpaca 数据集，我们发现，尽管评估指标常显示微调后性能降低，但人工评估往往表明微调后的模型优于原始模型。这表明语言适应后，目标语言生成能力有所提升，但推理能力有所减弱。这些结果凸显了改进评估方法以及创建高质量本地数据集的必要性，以便在低资源环境中准确评估特定语言模型的性能。

> Large Language Models (LLMs) have demonstrated remarkable multilingual capabilities, yet challenges persist in adapting these models for low-resource languages. In this study, we investigate the effects of Low-Rank Adaptation (LoRA) Parameter-Efficient Fine-Tuning (PEFT) on multilingual Gemma models for Marathi, a language with limited resources. Using a translated Alpaca dataset with 52,000 instruction-response pairs, our findings reveal that while evaluation metrics often show a performance decline post-fine-tuning, manual assessments frequently suggest that the fine-tuned models outperform their original counterparts. The observations indicate improvements in target language generation capabilities but a reduction in reasoning abilities following language adaptation. These results underscore the need for improved evaluation methodologies and the creation of high-quality native datasets to accurately assess language-specific model performance in low-resource settings.

[Arxiv](https://arxiv.org/abs/2411.18571)