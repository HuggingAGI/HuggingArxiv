# 对于语言模型而言，水印强度与推测采样效率之间存在着不可避免的权衡。

发布时间：2024年10月27日

`LLM理论` `语言模型` `水印技术`

> Inevitable Trade-off between Watermark Strength and Speculative Sampling Efficiency for Language Models

# 摘要

> 大型语言模型属于概率模型，其生成内容的过程实质上是对语言模型输出分布的抽样。现有的水印技术能在不影响输出质量的前提下，把水印注入生成的内容里。另一方面，现有的加速技术，尤其是推测抽样，借助草案模型加快抽样进程，同时维持输出分布。但目前尚无已知方法能同时加速抽样过程并给生成的内容注入水印。在本文中，我们对此方向展开研究，发现水印与加速的融合并非轻而易举。我们证明了一个“不可行定理”，即无法同时保持最高的水印强度和最高的抽样效率。此外，我们提出了两种方法，分别维持抽样效率或水印强度，无法两者兼顾。我们的工作为理解大型语言模型在加速生成水印标记时水印强度与抽样效率之间的内在权衡，提供了严谨的理论基础。我们还开展了数值实验，以验证我们的理论成果并展现所提方法的有效性。

> Large language models are probabilistic models, and the process of generating content is essentially sampling from the output distribution of the language model. Existing watermarking techniques inject watermarks into the generated content without altering the output quality. On the other hand, existing acceleration techniques, specifically speculative sampling, leverage a draft model to speed up the sampling process while preserving the output distribution. However, there is no known method to simultaneously accelerate the sampling process and inject watermarks into the generated content. In this paper, we investigate this direction and find that the integration of watermarking and acceleration is non-trivial. We prove a no-go theorem, which states that it is impossible to simultaneously maintain the highest watermark strength and the highest sampling efficiency. Furthermore, we propose two methods that maintain either the sampling efficiency or the watermark strength, but not both. Our work provides a rigorous theoretical foundation for understanding the inherent trade-off between watermark strength and sampling efficiency in accelerating the generation of watermarked tokens for large language models. We also conduct numerical experiments to validate our theoretical findings and demonstrate the effectiveness of the proposed methods.

[Arxiv](https://arxiv.org/abs/2410.20418)