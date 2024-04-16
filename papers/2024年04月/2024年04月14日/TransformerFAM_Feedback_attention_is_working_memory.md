# TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。

发布时间：2024年04月14日

`LLM理论`

> TransformerFAM: Feedback attention is working memory

# 摘要

> 变换器虽然引领了深度学习的新时代，但其处理极长输入的能力受限于其二次方的注意力复杂度。现在，我们引入了反馈注意力记忆（FAM），这是一种创新的变换器架构，通过反馈循环让网络能够关注自身的潜在表达，从而在变换器内部形成工作记忆，实现对无限长序列的处理。TransformerFAM无需增加额外权重，与现有预训练模型完美融合。实验结果显示，无论是1B、8B还是24B的模型，TransformerFAM都能显著提升处理长序列任务的性能，这为大型语言模型处理无限制长度的序列开辟了新的可能性。

> While Transformers have revolutionized deep learning, their quadratic attention complexity hinders their ability to process infinitely long inputs. We propose Feedback Attention Memory (FAM), a novel Transformer architecture that leverages a feedback loop to enable the network to attend to its own latent representations. This design fosters the emergence of working memory within the Transformer, allowing it to process indefinitely long sequences. TransformerFAM requires no additional weights, enabling seamless integration with pre-trained models. Our experiments show that TransformerFAM significantly improves Transformer performance on long-context tasks across various model sizes (1B, 8B, and 24B). These results showcase the potential to empower Large Language Models (LLMs) to process sequences of unlimited length.

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x1.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x2.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x3.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x4.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x5.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x6.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x7.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x8.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/txl_ani.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/fam_ani1.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/fam_ani2.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x9.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x10.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x11.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x12.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/x13.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am0.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am1.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am3.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am4.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am9.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am10.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am13.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am16.png)

![TransformerFAM 模型中，反馈注意力机制扮演着工作记忆的角色。](../../../paper_images/2404.09173/am17.png)

[Arxiv](https://arxiv.org/abs/2404.09173)