# SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术

发布时间：2024年03月18日

`LLM应用` `计算机视觉`

> SuperLoRA: Parameter-Efficient Unified Adaptation of Multi-Layer Attention Modules

# 摘要

> 广泛应用于诸如NLP领域的大型语言模型及CV中的扩散模型等微调任务的低秩适应（LoRA）及其多种变体，如今被一种称为SuperLoRA的新型通用框架所整合与拓展。该框架能够在不同超参数配置下实现各种LoRA变体，并创新性地融入了分组、折叠、混洗、投影以及张量分解机制，从而赋予其相比其他同类方法更高的灵活度。尤其在极端少量参数的场景下，SuperLoRA在迁移学习任务上展现出卓越的表现。

> Low-rank adaptation (LoRA) and its variants are widely employed in fine-tuning large models, including large language models for natural language processing and diffusion models for computer vision. This paper proposes a generalized framework called SuperLoRA that unifies and extends different LoRA variants, which can be realized under different hyper-parameter settings. Introducing grouping, folding, shuffling, projecting, and tensor factoring, SuperLoRA offers high flexibility compared with other LoRA variants and demonstrates superior performance for transfer learning tasks especially in the extremely few-parameter regimes.

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x1.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x2.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x3.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x4.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x5.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x6.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x7.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x8.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x9.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x10.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x11.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x12.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/dense.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lora_rank8_ckpt20_IS00325_param75776.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/loragroup_group8_rank13_is00305_param70720.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/loragroup_reshape_group4_rank24_is00263_param73728.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lonkr_split2_g1_r10_factor6_ckpt20_IS0036_param5112.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/loragroup_reshape_rank7_group1_is00294_param10752.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lorta_d3_g12_r5_ckpt20_IS00272_param8160.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lorta_d4_g12_r5_ckpt20_IS0036_param11100.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/loragroup_reshape_rank4_group4_lrv2proj05_IS00273_param8512.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lonkr_split2_g1_r2_factor6_ckpt20_IS00471_param1080.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lorta_d3_g1_r4_ckpt20_IS00565_param1060.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lorta_d3_g4_r4_lrv2proj001_ckpt20_IS00607_param832.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lorta_d5_g1_r1_ckpt20_IS01131_param76.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/lorta_d5_g1_r1_lrv2proj001_ckpt20_IS00871_param31.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x13.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x14.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x15.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x16.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x17.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x18.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x19.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x20.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x21.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x22.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x23.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x24.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x25.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x26.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x27.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x28.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x29.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x30.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x31.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x32.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x33.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x34.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x35.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x36.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x37.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x38.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x39.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x40.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x41.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x42.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x43.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x44.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x45.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x46.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x47.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x48.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x49.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x50.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x51.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x52.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x53.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x54.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x55.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x56.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x57.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x58.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x59.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x60.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x61.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x62.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x63.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x64.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x65.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x66.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x68.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x69.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x70.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x71.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x72.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x74.png)

![SuperLoRA：一种针对多层注意力模块的参数高效统一调适技术](../../../paper_images/2403.11887/x75.png)

[Arxiv](https://arxiv.org/abs/2403.11887)