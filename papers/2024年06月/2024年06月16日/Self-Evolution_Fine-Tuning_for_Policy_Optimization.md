# 策略优化中的自进化微调

发布时间：2024年06月16日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）的对齐问题，并提出了一种新的对齐方法——自进化微调（SEFT）。这种方法涉及理论上的创新，如适应性修订器和增强的响应微调策略，旨在优化模型的性能和响应质量，同时利用未标注数据。这些内容更偏向于LLM的理论研究和方法论创新，而不是具体的应用实例或Agent的设计，因此归类为LLM理论。` `人工智能`

> Self-Evolution Fine-Tuning for Policy Optimization

# 摘要

> 大型语言模型的对齐至关重要，不仅为了发挥其在特定任务中的潜力，还为了确保其响应符合人类期望并遵循安全和伦理准则。现有的对齐方法，如监督微调（SFT）和基于人类反馈的强化学习（RLHF），均面临挑战。本文提出了一种名为自进化微调（SEFT）的新方法，旨在无需标注样本的同时保持SFT的稳定性和效率。SEFT通过训练一个适应性修订器，提升低质量响应并保持高质量响应，进而通过增强的响应微调策略，逐步优化策略。该方法的亮点在于能利用大量未标注数据进行策略优化。我们在AlpacaEval 2.0和MT-Bench的实验验证了SEFT的有效性，并详细分析了其相对于现有技术的优势。

> The alignment of large language models (LLMs) is crucial not only for unlocking their potential in specific tasks but also for ensuring that responses meet human expectations and adhere to safety and ethical principles. Current alignment methodologies face considerable challenges. For instance, supervised fine-tuning (SFT) requires extensive, high-quality annotated samples, while reinforcement learning from human feedback (RLHF) is complex and often unstable. In this paper, we introduce self-evolution fine-tuning (SEFT) for policy optimization, with the aim of eliminating the need for annotated samples while retaining the stability and efficiency of SFT. SEFT first trains an adaptive reviser to elevate low-quality responses while maintaining high-quality ones. The reviser then gradually guides the policy's optimization by fine-tuning it with enhanced responses. One of the prominent features of this method is its ability to leverage unlimited amounts of unannotated data for policy optimization through supervised fine-tuning. Our experiments on AlpacaEval 2.0 and MT-Bench demonstrate the effectiveness of SEFT. We also provide a comprehensive analysis of its advantages over existing alignment techniques.

![策略优化中的自进化微调](../../../paper_images/2406.10813/x1.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x2.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x3.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x4.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x5.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x6.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x7.png)

![策略优化中的自进化微调](../../../paper_images/2406.10813/x8.png)

[Arxiv](https://arxiv.org/abs/2406.10813)