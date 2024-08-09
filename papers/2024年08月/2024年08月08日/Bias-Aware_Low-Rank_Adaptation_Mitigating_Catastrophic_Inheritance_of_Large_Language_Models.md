# 偏差感知低秩适应策略，旨在缓解大型语言模型中的灾难性继承问题。

发布时间：2024年08月08日

`LLM理论` `人工智能`

> Bias-Aware Low-Rank Adaptation: Mitigating Catastrophic Inheritance of Large Language Models

# 摘要

> 大型语言模型 (LLM) 在多样化的 NLP 任务中表现出色，但适应下游应用往往需要高计算和内存的微调。为减轻这些负担，参数高效的微调 (PEFT) 技术应运而生，以最小计算开销定制 LLM。尽管 PEFT 技术优势显著，但未能完全解决预训练数据偏差传播的问题。为此，我们提出了偏差感知低秩适应 (BA-LoRA)，一种创新的 PEFT 方法，旨在对抗偏差继承。BA-LoRA 融合了三种正则化项：一致性、多样性和奇异向量分解正则化器，共同提升微调过程中模型的一致性、多样性和泛化能力。通过在多种 NLU 和 NLG 任务上使用 LLaMA、Mistral 和 Gemma 等 LLM 进行广泛实验，我们验证了 BA-LoRA 优于现有方法，并有效减轻了预训练偏差的影响，使模型输出更可靠和健壮。代码已公开在 https://github.com/cyp-jlu-ai/BA-LoRA。

> Large language models (LLMs) have exhibited remarkable proficiency across a diverse array of natural language processing (NLP) tasks. However, adapting LLMs to downstream applications typically necessitates computationally intensive and memory-demanding fine-tuning procedures. To mitigate these burdens, parameter-efficient fine-tuning (PEFT) techniques have emerged as a promising approach to tailor LLMs with minimal computational overhead. While PEFT methods offer substantial advantages, they do not fully address the pervasive issue of bias propagation from pre-training data. In this work, we introduce Bias-Aware Low-Rank Adaptation (BA-LoRA), a novel PEFT method designed to counteract bias inheritance. BA-LoRA incorporates three distinct regularization terms: (1) consistency regularizer, (2) diversity regularizer, and (3) singular vector decomposition regularizer. These regularizers collectively aim to improve the generative models' consistency, diversity, and generalization capabilities during the fine-tuning process. Through extensive experiments on a variety of natural language understanding (NLU) and natural language generation (NLG) tasks, employing prominent LLMs such as LLaMA, Mistral, and Gemma, we demonstrate that BA-LoRA surpasses the performance of LoRA and its state-of-the-art variants. Moreover, our method effectively mitigates the deleterious effects of pre-training bias, leading to more reliable and robust model outputs. The code is available at https://github.com/cyp-jlu-ai/BA-LoRA.

[Arxiv](https://arxiv.org/abs/2408.04556)