# HELPD：利用视觉增强的分层反馈学习与惩罚解码，有效减轻 LVLMs 的幻觉问题。

发布时间：2024年09月30日

`LLM应用` `计算机视觉`

> HELPD: Mitigating Hallucination of LVLMs by Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding

# 摘要

> 大型视觉-语言模型 (LVLMs) 在众多视觉-语言任务中表现出色，但仍面临多模态幻觉问题，即生成与图像不符的内容。现有方法多通过简单判断图像中是否存在某个对象来检测幻觉，忽略了对象与语义的深层关联。为此，我们提出了视觉增强惩罚解码的分层反馈学习 (HELPD)，该框架在对象和句子语义层面上整合幻觉反馈，即使在小规模训练下也能减少超过 15% 的幻觉。同时，HELPD 通过图像注意力窗口对输出进行惩罚，避免过度受生成文本影响。HELPD 可无缝集成到任何 LVLMs 中，实验证明其在多个幻觉基准测试中表现优异，有效减轻幻觉问题并提升文本生成质量。

> Large Vision-Language Models (LVLMs) have shown remarkable performance on many visual-language tasks. However, these models still suffer from multimodal hallucination, which means the generation of objects or content that violates the images. Many existing work detects hallucination by directly judging whether an object exists in an image, overlooking the association between the object and semantics. To address this issue, we propose Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding (HELPD). This framework incorporates hallucination feedback at both object and sentence semantic levels. Remarkably, even with a marginal degree of training, this approach can alleviate over 15% of hallucination. Simultaneously, HELPD penalizes the output logits according to the image attention window to avoid being overly affected by generated text. HELPD can be seamlessly integrated with any LVLMs. Our experiments demonstrate that the proposed framework yields favorable results across multiple hallucination benchmarks. It effectively mitigates hallucination for different LVLMs and concurrently improves their text generation quality.

[Arxiv](https://arxiv.org/abs/2409.20429)