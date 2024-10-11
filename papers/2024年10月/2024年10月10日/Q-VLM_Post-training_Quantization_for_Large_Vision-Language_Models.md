# Q-VLM：为大型视觉-语言模型进行的后训练量化

发布时间：2024年10月10日

`LLM应用` `计算机视觉`

> Q-VLM: Post-training Quantization for Large Vision-Language Models

# 摘要

> 本文提出了一种高效多模态推理的大型视觉语言模型（LVLMs）的后训练量化框架。传统方法未能考虑跨层依赖性，导致量化策略不佳。我们通过挖掘跨层依赖性，并将其融入低成本的量化策略搜索中，显著提升了量化效果。具体而言，我们利用激活熵来优化块划分，实现了误差与成本的平衡。此外，通过优化视觉编码器，我们进一步降低了搜索成本，同时保持了量化精度。实验显示，该方法在不影响性能的前提下，将内存压缩2.78倍，生成速度提升1.44倍，适用于13B LLaVA模型。代码已开源，详见https://github.com/ChangyuanWang17/QVLM。

> In this paper, we propose a post-training quantization framework of large vision-language models (LVLMs) for efficient multi-modal inference. Conventional quantization methods sequentially search the layer-wise rounding functions by minimizing activation discretization errors, which fails to acquire optimal quantization strategy without considering cross-layer dependency. On the contrary, we mine the cross-layer dependency that significantly influences discretization errors of the entire vision-language model, and embed this dependency into optimal quantization strategy searching with low search cost. Specifically, we observe the strong correlation between the activation entropy and the cross-layer dependency concerning output discretization errors. Therefore, we employ the entropy as the proxy to partition blocks optimally, which aims to achieve satisfying trade-offs between discretization errors and the search cost. Moreover, we optimize the visual encoder to disentangle the cross-layer dependency for fine-grained decomposition of search space, so that the search cost is further reduced without harming the quantization accuracy. Experimental results demonstrate that our method compresses the memory by 2.78x and increase generate speed by 1.44x about 13B LLaVA model without performance degradation on diverse multi-modal reasoning tasks. Code is available at https://github.com/ChangyuanWang17/QVLM.

[Arxiv](https://arxiv.org/abs/2410.08119)