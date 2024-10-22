# 借助同心因果注意力机制，有效缓解对象幻觉问题。

发布时间：2024年10月21日

`LLM应用` `人工智能` `计算机视觉`

> Mitigating Object Hallucination via Concentric Causal Attention

# 摘要

> 最新的大型视觉语言模型 (LVLMs) 在多模态查询下展现了卓越的零-shot 对话和推理能力，但它们也面临对象幻觉的困扰——生成的文本与图像输入不符。初步研究发现，这一问题与广泛使用的 Rotary Position Encoding (RoPE) 密切相关。RoPE 的长期衰减导致 LVLMs 在视觉线索远离指令标记时更易产生幻觉。此外，反转视觉标记顺序也会产生类似影响。为应对这一挑战，我们提出了同心因果注意力 (CCA)，一种简单高效的位置对齐策略，通过缩短视觉与指令标记的相对距离，有效缓解 RoPE 的长期衰减问题。实验证明，CCA 显著提升了模型感知能力，大幅减少了对象幻觉现象，在多个基准测试中超越了现有方法。

> Recent Large Vision Language Models (LVLMs) present remarkable zero-shot conversational and reasoning capabilities given multimodal queries. Nevertheless, they suffer from object hallucination, a phenomenon where LVLMs are prone to generate textual responses not factually aligned with image inputs. Our pilot study reveals that object hallucination is closely tied with Rotary Position Encoding (RoPE), a widely adopted positional dependency modeling design in existing LVLMs. Due to the long-term decay in RoPE, LVLMs tend to hallucinate more when relevant visual cues are distant from instruction tokens in the multimodal input sequence. Additionally, we observe a similar effect when reversing the sequential order of visual tokens during multimodal alignment. Our tests indicate that long-term decay in RoPE poses challenges to LVLMs while capturing visual-instruction interactions across long distances. We propose Concentric Causal Attention (CCA), a simple yet effective positional alignment strategy that mitigates the impact of RoPE long-term decay in LVLMs by naturally reducing relative distance between visual and instruction tokens. With CCA, visual tokens can better interact with instruction tokens, thereby enhancing model's perception capability and alleviating object hallucination. Without bells and whistles, our positional alignment method surpasses existing hallucination mitigation strategies by large margins on multiple object hallucination benchmarks.

[Arxiv](https://arxiv.org/abs/2410.15926)