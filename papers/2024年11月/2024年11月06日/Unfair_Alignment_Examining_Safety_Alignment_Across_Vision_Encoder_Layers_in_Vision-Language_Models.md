# 不公平对齐：检查视觉语言模型中视觉编码器层的安全对齐

发布时间：2024年11月06日

`LLM应用` `计算机视觉` `模型安全`

> Unfair Alignment: Examining Safety Alignment Across Vision Encoder Layers in Vision-Language Models

# 摘要

> 视觉语言模型（VLMs）在多模态任务中已有显著改进，但它们更复杂的架构使得其安全对齐比大型语言模型（LLMs）的对齐更具挑战性。在本文中，我们揭示了 VLM 视觉编码器各层的安全分布不公平，与更稳健的最后一层相比，较早和中间的层更容易受到恶意输入的影响。这种“跨层”漏洞源于模型无法将其安全训练从训练期间使用的默认架构设置推广到未见过或分布外的场景，从而使某些层暴露在外。我们通过投射来自各种中间层的激活进行了全面分析，并证明当这些层暴露于恶意输入时，更有可能产生有害输出。我们对 LLaVA-1.5 和 Llama 3.2 的实验表明，各层的攻击成功率和毒性分数存在差异，这表明当前专注于单个默认层的安全对齐策略是不够的。

> Vision-language models (VLMs) have improved significantly in multi-modal tasks, but their more complex architecture makes their safety alignment more challenging than the alignment of large language models (LLMs). In this paper, we reveal an unfair distribution of safety across the layers of VLM's vision encoder, with earlier and middle layers being disproportionately vulnerable to malicious inputs compared to the more robust final layers. This 'cross-layer' vulnerability stems from the model's inability to generalize its safety training from the default architectural settings used during training to unseen or out-of-distribution scenarios, leaving certain layers exposed. We conduct a comprehensive analysis by projecting activations from various intermediate layers and demonstrate that these layers are more likely to generate harmful outputs when exposed to malicious inputs. Our experiments with LLaVA-1.5 and Llama 3.2 show discrepancies in attack success rates and toxicity scores across layers, indicating that current safety alignment strategies focused on a single default layer are insufficient.

[Arxiv](https://arxiv.org/abs/2411.04291)