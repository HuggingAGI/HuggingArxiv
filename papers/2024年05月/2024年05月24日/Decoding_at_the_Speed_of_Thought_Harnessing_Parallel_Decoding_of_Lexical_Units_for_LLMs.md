# 思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率

发布时间：2024年05月24日

`LLM应用

这篇论文介绍了一种名为词汇单元解码（LUD）的新解码策略，旨在加速大型语言模型的解码过程，以满足实时应用的需求。LUD通过并行解码预训练模型预测的连续令牌（作为“词汇单元”）来实现加速，同时保持输出质量。这种方法特别适用于自然语言生成和代码生成，且不需要额外模型支持，也不改变现有架构，还可以与其他加速方法结合使用。因此，这篇论文属于LLM应用分类，因为它专注于改进大型语言模型的实际应用性能。` `软件开发`

> Decoding at the Speed of Thought: Harnessing Parallel Decoding of Lexical Units for LLMs

# 摘要

> 大型语言模型在自然语言理解和生成上表现出色，但其生成速度受限于解码过程的顺序性，难以满足实时应用的需求。为此，本文提出了一种名为词汇单元解码（LUD）的创新解码策略，该策略通过数据驱动的方式加速解码，同时确保输出质量不受影响。LUD的核心在于利用预训练模型预测连续令牌的能力，将这些连续令牌作为一个“词汇单元”并行解码。实验结果表明，LUD在自然语言生成上提速33%且无质量损失，在代码生成上提速30%，质量损失微乎其微（3%）。此外，LUD无需额外模型支持，也不改变现有架构，还能与其他加速方法结合，进一步提升推理效率。我们相信，LUD的基本原则将为未来语言模型开辟新的解码范式，拓展其在更多领域的应用潜力。相关代码已公开于https://github.com/tjunlp-lab/Lexical-Unit-Decoding-LUD-。关键词：并行解码，词汇单元解码，大型语言模型

> Large language models have demonstrated exceptional capability in natural language understanding and generation. However, their generation speed is limited by the inherently sequential nature of their decoding process, posing challenges for real-time applications. This paper introduces Lexical Unit Decoding (LUD), a novel decoding methodology implemented in a data-driven manner, accelerating the decoding process without sacrificing output quality. The core of our approach is the observation that a pre-trained language model can confidently predict multiple contiguous tokens, forming the basis for a \textit{lexical unit}, in which these contiguous tokens could be decoded in parallel. Extensive experiments validate that our method substantially reduces decoding time while maintaining generation quality, i.e., 33\% speed up on natural language generation with no quality loss, and 30\% speed up on code generation with a negligible quality loss of 3\%. Distinctively, LUD requires no auxiliary models and does not require changes to existing architectures. It can also be integrated with other decoding acceleration methods, thus achieving an even more pronounced inference efficiency boost. We posit that the foundational principles of LUD could define a new decoding paradigm for future language models, enhancing their applicability for a broader spectrum of applications. All codes are be publicly available at https://github.com/tjunlp-lab/Lexical-Unit-Decoding-LUD-.
Keywords: Parallel Decoding, Lexical Unit Decoding, Large Language Model

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/fig_intro_intuition.png)

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/fig_infer.png)

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/fig_method_LUI.png)

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/curves_text.png)

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/curves_code.png)

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/fig_examples.png)

![思维速度解码：借助词汇单元的并行处理，加速大型语言模型的解码效率](../../../paper_images/2405.15208/histogram.png)

[Arxiv](https://arxiv.org/abs/2405.15208)