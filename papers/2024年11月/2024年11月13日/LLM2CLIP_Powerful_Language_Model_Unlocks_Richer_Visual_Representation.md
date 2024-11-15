# LLM2CLIP：强大的语言模型解锁更丰富的视觉表示

发布时间：2024年11月13日

`LLM应用` `多模态` `计算机视觉`

> LLM2CLIP: Powerful Language Model Unlocks Richer Visual Representation

# 摘要

> CLIP 是当今最重要的多模态基础模型之一。是什么赋予了 CLIP 的能力？人类知识的载体——自然语言所提供的丰富监督信号，塑造了一个强大的跨模态表示空间。然而，随着像 GPT-4 和 LLaMA 这样的大型语言模型（LLM）的快速发展，语言理解和生成的边界不断被推进。这就提出了一个有趣的问题：能否利用 LLM 的能力来进一步改进多模态表示学习？将 LLM 纳入 CLIP 的潜在好处是显而易见的。LLM 强大的文本理解能力可以从根本上提高 CLIP 处理图像标题的能力，极大地增强其处理长而复杂文本的能力，这是原始 CLIP 的一个众所周知的限制。此外，LLM 在大量的文本语料库上进行训练，拥有开放世界的知识。这使它们能够在训练期间扩展标题信息，提高学习过程的效率。在本文中，我们提出了 LLM2CLIP，这是一种利用 LLM 的力量来释放 CLIP 潜力的新方法。通过在标题空间中用对比学习对 LLM 进行微调，我们将其文本能力提取到输出嵌入中，显著提高了输出层的文本判别能力。然后，我们设计了一个高效的训练过程，其中微调后的 LLM 充当 CLIP 视觉编码器的强大教师。由于 LLM 的存在，我们现在可以纳入更长和更复杂的标题，而不受原始 CLIP 的文本编码器的上下文窗口和能力限制。我们的实验表明，这种方法在跨模态任务中带来了显著的改进。

> CLIP is one of the most important multimodal foundational models today. What powers CLIP's capabilities? The rich supervision signals provided by natural language, the carrier of human knowledge, shape a powerful cross-modal representation space. However, with the rapid advancements in large language models LLMs like GPT-4 and LLaMA, the boundaries of language comprehension and generation are continually being pushed. This raises an intriguing question: can the capabilities of LLMs be harnessed to further improve multimodal representation learning? The potential benefits of incorporating LLMs into CLIP are clear. LLMs' strong textual understanding can fundamentally improve CLIP's ability to handle image captions, drastically enhancing its ability to process long and complex texts, a well-known limitation of vanilla CLIP. Moreover, LLMs are trained on a vast corpus of text, possessing open-world knowledge. This allows them to expand on caption information during training, increasing the efficiency of the learning process. In this paper, we propose LLM2CLIP, a novel approach that embraces the power of LLMs to unlock CLIP's potential. By fine-tuning the LLM in the caption space with contrastive learning, we extract its textual capabilities into the output embeddings, significantly improving the output layer's textual discriminability. We then design an efficient training process where the fine-tuned LLM acts as a powerful teacher for CLIP's visual encoder. Thanks to the LLM's presence, we can now incorporate longer and more complex captions without being restricted by vanilla CLIP's text encoder's context window and ability limitations. Our experiments demonstrate that this approach brings substantial improvements in cross-modal tasks.

[Arxiv](https://arxiv.org/abs/2411.04997)