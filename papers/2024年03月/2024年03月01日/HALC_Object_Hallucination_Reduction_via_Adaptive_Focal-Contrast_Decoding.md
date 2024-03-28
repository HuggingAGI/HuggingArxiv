# HALC 方法提出了一种新颖的自适应焦点对比解码技术，旨在有效减少对象幻觉现象。该方法针对图像识别中的错误预测问题，通过优化解码过程来提升模型对真实目标的区分能力和鲁棒性。

发布时间：2024年03月01日

`Agent`

> HALC: Object Hallucination Reduction via Adaptive Focal-Contrast Decoding

# 摘要

> 尽管大型视觉-语言模型在处理多模态情境时表现出卓越能力，却常常困于对象幻觉难题。为此，我们创新性地提出了HALC解码算法，专为解决LVLM中的对象幻觉而设计。HALC巧妙运用视觉-语言任务中的精细视觉信息，在局部和全局层面同步运作，既包含一套稳健的自聚焦锚定机制，实时纠正错位的符号，又配备了一种专业化的束搜索算法，大幅削减OH现象的同时确保文本生成质量不打折。更重要的是，HALC能够以即插即用的方式轻松融入任何LVLM，无需额外训练成本。大量的实验证明，HALC在对抗OH上功效显著，无论是在四个基准测试中，均展现出优于业界最先进水平的表现。

> While large vision-language models (LVLMs) have demonstrated impressive capabilities in interpreting multi-modal contexts, they invariably suffer from object hallucinations (OH). We introduce HALC, a novel decoding algorithm designed to mitigate OH in LVLMs. HALC leverages distinct fine-grained optimal visual information in vision-language tasks and operates on both local and global contexts simultaneously. Specifically, HALC integrates a robust auto-focal grounding mechanism (locally) to correct hallucinated tokens on the fly, and a specialized beam search algorithm (globally) to significantly reduce OH while preserving text generation quality. Additionally, HALC can be integrated into any LVLMs as a plug-and-play module without extra training. Extensive experimental studies demonstrate the effectiveness of HALC in reducing OH, outperforming state-of-the-arts across four benchmarks.

[Arxiv](https://arxiv.org/abs/2403.00425)