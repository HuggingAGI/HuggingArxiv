# 意大利语的先进自然交互技术：LLaMAntino-3-ANITA

发布时间：2024年05月11日

`LLM应用

这篇论文介绍了一个针对意大利语优化的基于Meta LLaMA-3的大型语言模型LLaMAntino-3-ANITA-8B-Inst-DPO-ITA。通过使用监督微调（SFT）、动态偏好优化（DPO）和QLoRA技术，该模型在意大利语和英语数据集上进行了优化，以提高其在自然语言处理任务中的性能。这些技术确保了模型的输出既安全又恰当，同时减少了偏见。该模型在多项任务中表现出色，并通过了意大利语和英语的标准测试。因此，这篇论文属于LLM应用类别，因为它专注于实际应用中的模型优化和性能提升。` `语言模型`

> Advanced Natural-based interaction for the ITAlian language: LLaMAntino-3-ANITA

# 摘要

> 我们推出了基于Meta LLaMA-3的尖端大型语言模型LLaMAntino-3-ANITA-8B-Inst-DPO-ITA，旨在提升意大利语的自然语言处理能力。通过监督微调（SFT）技术，我们优化了原始模型的80亿参数，使其在英语和意大利语数据集上表现更佳。动态偏好优化（DPO）技术确保了模型的回答既安全又恰当，同时减少了偏见。借助QLoRA技术，我们仅对模型权重的一小部分进行了微调，以适应意大利语的独特结构，大幅提升了性能和效率。DPO的运用进一步提升了模型输出的质量，确保其与高质量答案相匹配。SFT、QLoRA和DPO的结合，使得我们的模型在文本完成、零-shot分类和上下文理解等多项任务中表现卓越。经过意大利语和英语标准测试的严格评估，该模型表现出色。现在，您可以在HuggingFace hub上免费获取该模型，并在我们的GitHub仓库中查看使用示例。https://huggingface.co/swap-uniba/LLaMAntino-3-ANITA-8B-Inst-DPO-ITA

> In the pursuit of advancing natural language processing for the Italian language, we introduce a state-of-the-art Large Language Model (LLM) based on the novel Meta LLaMA-3 model: LLaMAntino-3-ANITA-8B-Inst-DPO-ITA. We fine-tuned the original 8B parameters instruction tuned model using the Supervised Fine-tuning (SFT) technique on the English and Italian language datasets in order to improve the original performance. Consequently, a Dynamic Preference Optimization (DPO) process has been used to align preferences, avoid dangerous and inappropriate answers, and limit biases and prejudices. Our model leverages the efficiency of QLoRA to fine-tune the model on a smaller portion of the original model weights and then adapt the model specifically for the Italian linguistic structure, achieving significant improvements in both performance and computational efficiency. Concurrently, DPO is employed to refine the model's output, ensuring that generated content aligns with quality answers. The synergy between SFT, QLoRA's parameter efficiency and DPO's user-centric optimization results in a robust LLM that excels in a variety of tasks, including but not limited to text completion, zero-shot classification, and contextual understanding. The model has been extensively evaluated over standard benchmarks for the Italian and English languages, showing outstanding results. The model is freely available over the HuggingFace hub and, examples of use can be found in our GitHub repository. https://huggingface.co/swap-uniba/LLaMAntino-3-ANITA-8B-Inst-DPO-ITA

[Arxiv](https://arxiv.org/abs/2405.07101)