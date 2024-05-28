# SelfCP：借助冻结的大型语言模型，将冗长提示精简至原长的1/12

发布时间：2024年05月27日

`LLM应用

这篇论文介绍了一种名为SelfCP的方法，该方法旨在解决使用大型语言模型（LLMs）处理长提示时的高硬件成本问题。SelfCP利用LLM自身的语言理解能力将长提示压缩为紧凑的虚拟令牌，从而减少处理长输入任务时的资源消耗。这种方法特别适用于需要处理长输入的任务，如总结。论文中提到的SelfCP方法通过两次使用同一冻结的LLM，先作为编码器压缩提示，再作为解码器生成响应，展示了其在LLM应用中的实际价值和效率。因此，这篇论文应归类为LLM应用。` `模型优化`

> SelfCP: Compressing Long Prompt to 1/12 Using the Frozen Large Language Model Itself

# 摘要

> 在使用大型语言模型（LLMs）时，长提示的引入会带来高昂的硬件成本，尤其是在需要处理长输入的任务如总结时。情境学习的普及更是加剧了这一问题。为此，我们提出了SelfCP方法，该方法利用LLM自身的语言理解能力，将长提示压缩为紧凑的虚拟令牌。SelfCP通过两次使用同一冻结的LLM，先作为编码器压缩提示，再作为解码器生成响应。具体操作是，在长提示中插入特殊令牌，指示LLM生成k个虚拟令牌，随后这些虚拟令牌与未压缩部分一同输入LLM以生成最终响应。SelfCP不仅支持无条件和有条件的提示压缩，还因其编码器和解码器均为冻结状态，仅含17M可训练参数，便于在不同LLM骨干间灵活应用。我们已在两个LLM骨干上实现并测试了SelfCP，结果显示，压缩后的虚拟令牌能有效替代原长提示的12倍大小。

> Long prompt leads to huge hardware costs when using Large Language Models (LLMs). Unfortunately, many tasks, such as summarization, inevitably introduce long task-inputs, and the wide application of in-context learning easily makes the prompt length explode. Inspired by the language understanding ability of LLMs, this paper proposes SelfCP, which uses the LLM \textbf{itself} to \textbf{C}ompress long \textbf{P}rompt into compact virtual tokens. SelfCP applies a general frozen LLM twice, first as an encoder to compress the prompt and then as a decoder to generate responses. Specifically, given a long prompt, we place special tokens within the lengthy segment for compression and signal the LLM to generate $k$ virtual tokens. Afterward, the virtual tokens concatenate with the uncompressed prompt and are fed into the same LLM to generate the response. In general, SelfCP facilitates the unconditional and conditional compression of prompts, fitting both standard tasks and those with specific objectives. Since the encoder and decoder are frozen, SelfCP only contains 17M trainable parameters and allows for convenient adaptation across various backbones. We implement SelfCP with two LLM backbones and evaluate it in both in- and out-domain tasks. Results show that the compressed virtual tokens can substitute $12 \times$ larger original prompts effectively

![SelfCP：借助冻结的大型语言模型，将冗长提示精简至原长的1/12](../../../paper_images/2405.17052/prompt.png)

![SelfCP：借助冻结的大型语言模型，将冗长提示精简至原长的1/12](../../../paper_images/2405.17052/x1.png)

![SelfCP：借助冻结的大型语言模型，将冗长提示精简至原长的1/12](../../../paper_images/2405.17052/case.png)

![SelfCP：借助冻结的大型语言模型，将冗长提示精简至原长的1/12](../../../paper_images/2405.17052/ratio.jpg)

[Arxiv](https://arxiv.org/abs/2405.17052)