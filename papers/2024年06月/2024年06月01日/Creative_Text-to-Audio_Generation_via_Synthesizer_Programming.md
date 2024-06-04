# 借助合成器编程，创意文本转音频的生成得以实现

发布时间：2024年06月01日

`Agent

理由：这篇论文介绍了一种新颖的文本至音频生成方法，即CTAG方法，它使用了一个仅有78个参数的虚拟模块化声音合成器。这种方法通过迭代调整合成器参数来生成音频，强调了其灵活性和直观的操控性，这与Agent的概念相符，即一个能够根据输入（文本提示）自主调整参数以生成输出的系统。此外，论文中提到的“虚拟模块化声音合成器”可以被视为一个Agent，因为它能够根据外部输入（文本提示）进行自我调整以产生特定的输出（音频）。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论。` `音乐制作` `电影制作`

> Creative Text-to-Audio Generation via Synthesizer Programming

# 摘要

> 神经音频合成技术现已支持通过自然语言来指定创意。然而，这些技术所生成的音频结果难以微调，因为它们依赖于庞大的潜在空间和多达数十亿难以解读的参数。我们提出了一种新颖的文本至音频生成方法，该方法运用了一个仅有78个参数的虚拟模块化声音合成器。合成器因其灵活性和直观的操控性，一直被专业声音设计师用于音乐和电影等媒体制作。我们的CTAG方法通过迭代调整合成器参数，能够生成易于审视和调整的高质量文本提示音频。这种方法产生的声音更具抽象性，捕捉了核心概念特征而非细微的声学细节，类似于简洁的草图能够生动传达视觉概念。我们的研究表明，CTAG生成的声音不仅独特且具有艺术感，而且与最新的神经音频合成模型同样易于识别，证明了它是一个宝贵且互补的工具。

> Neural audio synthesis methods now allow specifying ideas in natural language. However, these methods produce results that cannot be easily tweaked, as they are based on large latent spaces and up to billions of uninterpretable parameters. We propose a text-to-audio generation method that leverages a virtual modular sound synthesizer with only 78 parameters. Synthesizers have long been used by skilled sound designers for media like music and film due to their flexibility and intuitive controls. Our method, CTAG, iteratively updates a synthesizer's parameters to produce high-quality audio renderings of text prompts that can be easily inspected and tweaked. Sounds produced this way are also more abstract, capturing essential conceptual features over fine-grained acoustic details, akin to how simple sketches can vividly convey visual concepts. Our results show how CTAG produces sounds that are distinctive, perceived as artistic, and yet similarly identifiable to recent neural audio synthesis models, positioning it as a valuable and complementary tool.

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/x1.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/system_diagram.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/results.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/x2.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/accuracy_prompt.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/x3.png)

[Arxiv](https://arxiv.org/abs/2406.00294)