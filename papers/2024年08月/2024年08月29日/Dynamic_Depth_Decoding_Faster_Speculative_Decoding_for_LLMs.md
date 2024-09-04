# 动态深度解码技术，旨在为大型语言模型加速推测性解码过程。

发布时间：2024年08月29日

`LLM理论` `人工智能` `软件开发`

> Dynamic Depth Decoding: Faster Speculative Decoding for LLMs

# 摘要

> 通过推测解码，大型语言模型 (LLM) 实现了运行时的显著提升，且不失准确性。EAGLE-2 作为当前顶尖的推测解码技术，通过动态草稿树对 EAGLE 进行了改进。我们提出的动态深度解码 (DDD) 进一步优化了 EAGLE-2 的树草稿方法，利用动态深度，将 EAGLE-2 相对于 EAGLE 的平均加速提升了 $44\%$，最终 DDD 实现了 $3.16$ 倍的平均加速。

> The acceleration of Large Language Models (LLMs) with speculative decoding provides a significant runtime improvement without any loss of accuracy. Currently, EAGLE-2 is the state-of-the-art speculative decoding method, improving on EAGLE with a dynamic draft tree. We introduce Dynamic Depth Decoding (DDD), which optimises EAGLE-2's tree drafting method using a dynamic depth. This extends the average speedup that EAGLE-2 achieves over EAGLE by $44\%$, giving DDD an average speedup of $3.16$x.

[Arxiv](https://arxiv.org/abs/2409.00142)