# 自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。

发布时间：2024年08月04日

`LLM应用` `计算机视觉`

> Self-Introspective Decoding: Alleviating Hallucinations for Large Vision-Language Models

# 摘要

> 尽管大型视觉-语言模型（LVLMs）近年来取得了显著进展，但“幻觉”问题已成为其实际应用的一大障碍。现有解决方案主要从两个角度入手：一是通过精心策划的数据集或辅助分析网络对模型进行强化训练，但这会增加成本；二是采用对比解码技术，通过干扰输入来识别并减少幻觉，但这种方法增加了计算负担。为此，我们提出了一种名为自我反省解码（SID）的新方法。实证研究表明，预训练的LVLMs能够根据先前的视觉和文本信息自我评估视觉令牌的重要性。我们设计的上下文和文本感知令牌选择（CT2S）策略，在模型早期层后仅保留非关键视觉令牌，从而在自回归解码过程中有针对性地放大文本引导的幻觉。这样，早期层吸收的多模态知识能够引发有上下文依据的幻觉，而非无目的的幻觉。通过从原始令牌对数中减去放大的视觉和文本关联幻觉，我们指导模型进行更忠实的解码。大量实验证明，SID在无需额外知识和大量计算的情况下，能够生成更少幻觉且质量更高的文本。

> While Large Vision-Language Models (LVLMs) have rapidly advanced in recent years, the prevalent issue known as the `hallucination' problem has emerged as a significant bottleneck, hindering their real-world deployments. Existing methods mitigate this issue mainly from two perspectives: One approach leverages extra knowledge like robust instruction tuning LVLMs with curated datasets or employing auxiliary analysis networks, which inevitable incur additional costs. Another approach, known as contrastive decoding, induces hallucinations by manually disturbing the vision or instruction raw inputs and mitigates them by contrasting the outputs of the disturbed and original LVLMs. However, these approaches rely on empirical holistic input disturbances and double the inference cost. To avoid these issues, we propose a simple yet effective method named Self-Introspective Decoding (SID). Our empirical investigation reveals that pretrained LVLMs can introspectively assess the importance of vision tokens based on preceding vision and text (both instruction and generated) tokens. We develop the Context and Text-aware Token Selection (CT2S) strategy, which preserves only unimportant vision tokens after early layers of LVLMs to adaptively amplify text-informed hallucination during the auto-regressive decoding. This approach ensures that multimodal knowledge absorbed in the early layers induces multimodal contextual rather than aimless hallucinations. Subsequently, the original token logits subtract the amplified vision-and-text association hallucinations, guiding LVLMs decoding faithfully. Extensive experiments illustrate SID generates less-hallucination and higher-quality texts across various metrics, without extra knowledge and much additional computation burdens.

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x1.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x2.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x3.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x4.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x5.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/msgreedy.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/mssampling.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/add-greedy.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/add-sampling.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x6.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/alpha.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/beta.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/others.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x7.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x8.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x9.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x10.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x11.png)

![自我反省解码技术旨在减轻大型视觉-语言模型中的幻觉问题。](../../../paper_images/2408.02032/x12.png)

[Arxiv](https://arxiv.org/abs/2408.02032)