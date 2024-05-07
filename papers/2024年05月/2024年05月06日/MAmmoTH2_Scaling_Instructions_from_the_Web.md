# MAmmoTH2：网络指令的规模化应用

发布时间：2024年05月06日

`LLM应用` `人工智能`

> MAmmoTH2: Scaling Instructions from the Web

# 摘要

> 通过指令微调，我们显著提升了大型语言模型（LLMs）的推理能力，其中数据的质量和可扩展性扮演着至关重要的角色。目前，大多数指令微调数据依赖于人工众包或GPT-4的蒸馏过程。为了解决这一问题，我们提出了一种创新的方法，能够从预训练的网络语料库中高效地提炼出1000万个自然生成的指令数据，以此增强LLM的推理性能。我们的方法涵盖了三个步骤：（1）检索相关文档，（2）抽取指令与响应对，以及（3）利用开源的LLMs对抽取的对进行优化。基于这些数据，我们对基础的LLMs进行了微调，开发出了性能显著提升的MAmmoTH2模型。特别是，MAmmoTH2-7B（米斯特拉尔）在MATH基准上的性能从11%飙升至34%，在GSM8K基准上从36%跃升至67%，所有这些提升都是在没有使用任何特定领域数据进行训练的情况下实现的。此外，我们在公共指令微调数据集上对MAmmoTH2进行了进一步训练，推出了性能卓越的MAmmoTH2-Plus，在多个推理和聊天机器人基准测试中达到了行业领先水平。我们的研究不仅展示了如何无需昂贵的人工标注或GPT-4蒸馏就能收集到大规模、高品质的指令数据，更为构建更优质的指令微调数据集提供了全新的思路。

> Instruction tuning improves the reasoning abilities of large language models (LLMs), with data quality and scalability being the crucial factors. Most instruction tuning data come from human crowd-sourcing or GPT-4 distillation. We propose a paradigm to efficiently harvest 10 million naturally existing instruction data from the pre-training web corpus to enhance LLM reasoning. Our approach involves (1) recalling relevant documents, (2) extracting instruction-response pairs, and (3) refining the extracted pairs using open-source LLMs. Fine-tuning base LLMs on this dataset, we build MAmmoTH2 models, which significantly boost performance on reasoning benchmarks. Notably, MAmmoTH2-7B's (Mistral) performance increases from 11% to 34% on MATH and from 36% to 67% on GSM8K without training on any in-domain data. Further training MAmmoTH2 on public instruction tuning datasets yields MAmmoTH2-Plus, achieving state-of-the-art performance on several reasoning and chatbot benchmarks. Our work demonstrates how to harvest large-scale, high-quality instruction data without costly human annotation or GPT-4 distillation, providing a new paradigm for building better instruction tuning data.

[Arxiv](https://arxiv.org/abs/2405.03548)