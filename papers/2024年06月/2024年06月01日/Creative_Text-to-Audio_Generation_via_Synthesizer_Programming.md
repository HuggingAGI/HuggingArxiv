# 借助合成器编程，创意文本转音频的生成得以实现

发布时间：2024年06月01日

`LLM应用

这篇论文介绍了一种新型的文本至音频生成技术CTAG，它采用了一个仅含78个参数的虚拟模块化声音合成器。这种技术通过迭代调整合成器参数，能够高效生成可便捷调整的高品质文本驱动音频。虽然这项技术与大型语言模型（LLM）没有直接的理论联系，但它利用了文本输入来驱动音频生成，这可以被视为LLM的一种应用，特别是在将自然语言处理技术应用于音频合成领域。因此，将其归类为LLM应用是合适的。` `音乐制作` `电影制作`

> Creative Text-to-Audio Generation via Synthesizer Programming

# 摘要

> 神经音频合成技术现已支持通过自然语言描述创意，但其结果因基于庞大且复杂的参数系统而难以微调。为此，我们开发了一种新型文本至音频生成技术CTAG，它采用仅含78个参数的虚拟模块化声音合成器。这种合成器因其灵活直观的操控性，在音乐和电影制作中广受声音设计师青睐。CTAG通过迭代调整合成器参数，能高效生成可便捷调整的高品质文本驱动音频。生成的音频更具抽象美，捕捉核心概念而非琐碎声学细节，如同简洁草图传达视觉理念。实验证明，CTAG所创声音独特且艺术感强，与现有神经音频合成模型相比毫不逊色，成为一项宝贵且互补的技术。

> Neural audio synthesis methods now allow specifying ideas in natural language. However, these methods produce results that cannot be easily tweaked, as they are based on large latent spaces and up to billions of uninterpretable parameters. We propose a text-to-audio generation method that leverages a virtual modular sound synthesizer with only 78 parameters. Synthesizers have long been used by skilled sound designers for media like music and film due to their flexibility and intuitive controls. Our method, CTAG, iteratively updates a synthesizer's parameters to produce high-quality audio renderings of text prompts that can be easily inspected and tweaked. Sounds produced this way are also more abstract, capturing essential conceptual features over fine-grained acoustic details, akin to how simple sketches can vividly convey visual concepts. Our results show how CTAG produces sounds that are distinctive, perceived as artistic, and yet similarly identifiable to recent neural audio synthesis models, positioning it as a valuable and complementary tool.

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/x1.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/system_diagram.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/results.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/x2.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/accuracy_prompt.png)

![借助合成器编程，创意文本转音频的生成得以实现](../../../paper_images/2406.00294/x3.png)

[Arxiv](https://arxiv.org/abs/2406.00294)