# [IntactKV 方法旨在提升大型语言模型量化性能，其核心在于保留枢轴令牌的完整性。](https://arxiv.org/abs/2403.01241)

> IntactKV: Improving Large Language Model Quantization by Keeping Pivot Tokens Intact

发布时间：2024年03月02日

> 尽管LLMs在自然语言处理领域表现出众，却对计算资源需求巨大。为了平衡这一矛盾，科研人员尝试采用量化技术，但这往往会对LLM性能造成影响。本文发现并聚焦LLMs中一种先前未曾重视的“枢轴标记”现象——模型倾向于将大量注意力集中在输入序列起始位置的标记上，这对量化LLM的表现尤为关键。基于此，我们创新性地提出了IntactKV方案，它能从全精度模型中直接无损生成枢轴标记的KV缓存，既简洁又易于融入现有量化策略。更令人兴奋的是，IntactKV还能作为附加参数进行校准，助力量化LLMs再攀新高。严谨的数学分析表明，IntactKV有效降低了量化误差的上限。实验结果显示，IntactKV在多项下游任务中实现了稳定的性能提升，并成功达成了仅针对权重部分的无损INT4量化，树立了LLM量化技术的新标杆。

> Large language models (LLMs) excel in natural language processing but demand intensive computation. To mitigate this, various quantization methods have been explored, yet they compromise LLM performance. This paper unveils a previously overlooked type of outlier in LLMs. Such outliers are found to allocate most of the attention scores on initial tokens of input, termed as pivot tokens, which is crucial to the performance of quantized LLMs. Given that, we propose IntactKV to generate the KV cache of pivot tokens losslessly from the full-precision model. The approach is simple and easy to combine with existing quantization solutions. Besides, IntactKV can be calibrated as additional LLM parameters to boost the quantized LLMs further. Mathematical analysis also proves that IntactKV effectively reduces the upper bound of quantization error. Empirical results show that IntactKV brings consistent improvement and achieves lossless weight-only INT4 quantization on various downstream tasks, leading to the new state-of-the-art for LLM quantization.

`LLM应用`