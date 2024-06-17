# 推动生物医学领域高分辨率视觉-语言模型的前沿发展。

发布时间：2024年06月12日

`Agent

这篇论文主要介绍了在生物医学领域应用多模态学习技术，特别是通过开发新的数据集和图像编码策略，以及一个名为Llama3-Med的模型，来提升生物医学视觉问答的性能。这些技术的发展和应用，使得对话代理（Agent）在医疗领域的应用更加精准和可靠，推动了医学AI的创新。因此，这篇论文更适合归类于Agent，因为它关注的是如何通过技术改进来增强特定领域的智能代理功能。` `生物医学`

> Advancing High Resolution Vision-Language Models in Biomedicine

# 摘要

> 多模态学习极大地推动了生成式AI，尤其是在视觉与语言模型的融合上。GPT-4V和开源项目LLaVA等创新，已能驱动对话代理实现零-shot任务完成。但在生物医学领域应用这些技术，却面临特殊挑战。近期，LLaVA-Med等项目已开始利用如PMC-15M这样的大型数据集，针对生物医学场景进行指令调整。我们的研究成果有三：首先，我们推出了一款富含医学图像与文本配对的新指令数据集，源自Claude3-Opus与LLaMA3 70B；其次，我们提出了一种基于层次化表示的新图像编码策略，以增强生物医学视觉理解的精细度；最后，我们开发的Llama3-Med模型，在生物医学视觉问答领域实现了零-shot性能的领先，平均性能提升超过10%。这些进步是医疗专业人员更精准可靠的工具，填补了当前多模态对话助手的空白，并推动了医学AI的进一步创新。

> Multi-modal learning has significantly advanced generative AI, especially in vision-language modeling. Innovations like GPT-4V and open-source projects such as LLaVA have enabled robust conversational agents capable of zero-shot task completions. However, applying these technologies in the biomedical field presents unique challenges. Recent initiatives like LLaVA-Med have started to adapt instruction-tuning for biomedical contexts using large datasets such as PMC-15M. Our research offers three key contributions: (i) we present a new instruct dataset enriched with medical image-text pairs from Claude3-Opus and LLaMA3 70B, (ii) we propose a novel image encoding strategy using hierarchical representations to improve fine-grained biomedical visual comprehension, and (iii) we develop the Llama3-Med model, which achieves state-of-the-art zero-shot performance on biomedical visual question answering benchmarks, with an average performance improvement of over 10% compared to previous methods. These advancements provide more accurate and reliable tools for medical professionals, bridging gaps in current multi-modal conversational assistants and promoting further innovations in medical AI.

![推动生物医学领域高分辨率视觉-语言模型的前沿发展。](../../../paper_images/2406.09454/x1.png)

![推动生物医学领域高分辨率视觉-语言模型的前沿发展。](../../../paper_images/2406.09454/x2.png)

[Arxiv](https://arxiv.org/abs/2406.09454)