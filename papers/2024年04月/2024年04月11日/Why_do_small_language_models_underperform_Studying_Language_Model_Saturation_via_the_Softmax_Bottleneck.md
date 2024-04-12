# 小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。

发布时间：2024年04月11日

`LLM理论` `语言模型` `神经网络`

> Why do small language models underperform? Studying Language Model Saturation via the Softmax Bottleneck

# 摘要

> 语言模型的最新进展在于对庞大的网络文本语料库进行高度参数化神经网络的预训练。然而，这类模型在实际训练和推理过程中的成本较高，促使人们倾向于使用规模较小的模型。但研究发现，小模型在训练的后期可能会出现性能下降并趋于平稳的现象，即饱和。本文发现，这种饱和现象可以归因于小模型的隐藏层维度与目标上下文概率分布的高阶特性之间的不匹配。这种不匹配导致模型中的线性预测头因softmax瓶颈效应而性能受损。我们通过在多种场景下测试发现，少于1000个隐藏维度的模型在预训练后期往往形成低效的潜在表示，从而降低了最终的评估表现。

> Recent advances in language modeling consist in pretraining highly parameterized neural networks on extremely large web-mined text corpora. Training and inference with such models can be costly in practice, which incentivizes the use of smaller counterparts. However, it has been observed that smaller models can suffer from saturation, characterized as a drop in performance at some advanced point in training followed by a plateau. In this paper, we find that such saturation can be explained by a mismatch between the hidden dimension of smaller models and the high rank of the target contextual probability distribution. This mismatch affects the performance of the linear prediction head used in such models through the well-known softmax bottleneck phenomenon. We measure the effect of the softmax bottleneck in various settings and find that models based on less than 1000 hidden dimensions tend to adopt degenerate latent representations in late pretraining, which leads to reduced evaluation performance.

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/x1.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/x2.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/pythia_anisotropy.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/gpt2_anisotropy.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/gemma_anisotropy.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/opt_anisotropy.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/anisotropy_explosion_14m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/anisotropy_explosion_31m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/anisotropy_explosion_70m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/anisotropy_explosion_160m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/anisotropy_explosion_410m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/sv_map_14m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/sv_map_31m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/sv_map_70m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/sv_map_160m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/sv_map_410m.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/kullback_uni.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/llama_bottleneck_acc.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/llama_bottleneck_loss.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/llama_sv_4gram.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/pythia_sv_4gram.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/loss_v_werr.png)

![小型语言模型为何表现不尽人意？探究 Softmax 瓶颈背后的语言模型饱和现象。](../../../paper_images/2404.07647/lr_final.png)

[Arxiv](https://arxiv.org/abs/2404.07647)