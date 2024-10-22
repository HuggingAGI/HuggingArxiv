# 通过对比解码技术，有效减少大型语言模型在医学信息提取过程中产生的幻觉。

发布时间：2024年10月21日

`LLM应用` `人工智能`

> Mitigating Hallucinations of Large Language Models in Medical Information Extraction via Contrastive Decoding

# 摘要

> 大型语言模型（LLM）在医疗领域的应用潜力巨大，但其复杂的临床环境带来了幻觉问题，限制了其广泛应用。本文通过引入交替对比解码（ALCD），重新定义医学信息提取（MIE）任务为识别与分类过程，并在微调中分离识别与分类功能。推理阶段，通过交替对比子任务模型的输出分布，选择性增强识别与分类能力，同时减少其他固有能力的影响。此外，提出交替自适应约束策略，更有效地调整对比令牌的规模与范围。实验证明，ALCD 在解决幻觉问题上显著优于传统方法。

> The impressive capabilities of large language models (LLMs) have attracted extensive interests of applying LLMs to medical field. However, the complex nature of clinical environments presents significant hallucination challenges for LLMs, hindering their widespread adoption. In this paper, we address these hallucination issues in the context of Medical Information Extraction (MIE) tasks by introducing ALternate Contrastive Decoding (ALCD). We begin by redefining MIE tasks as an identify-and-classify process. We then separate the identification and classification functions of LLMs by selectively masking the optimization of tokens during fine-tuning. During the inference stage, we alternately contrast output distributions derived from sub-task models. This approach aims to selectively enhance the identification and classification capabilities while minimizing the influence of other inherent abilities in LLMs. Additionally, we propose an alternate adaptive constraint strategy to more effectively adjust the scale and scope of contrastive tokens. Through comprehensive experiments on two different backbones and six diverse medical information extraction tasks, ALCD demonstrates significant improvements in resolving hallucination issues compared to conventional decoding methods.

[Arxiv](https://arxiv.org/abs/2410.15702)