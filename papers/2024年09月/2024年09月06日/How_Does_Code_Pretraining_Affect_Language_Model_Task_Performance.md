# 代码预训练对语言模型任务性能有何影响？

发布时间：2024年09月06日

`LLM理论` `人工智能` `软件开发`

> How Does Code Pretraining Affect Language Model Task Performance?

# 摘要

> 大型语言模型越来越多地融合自然语言和非语言数据（如源代码）进行训练。除了提升编程任务，有证据表明，预训练中加入代码还能提升其他不相关任务的性能。然而，至今尚无研究能通过控制语言和代码数据来确立因果关系。我们填补了这一空白。我们在两种模式下预训练模型：一是数据总量不变的加性模式，二是语言数据量不变的竞争模式。我们探讨了预训练中代码与语言的混合比例如何影响（a）BigBench基准中的多样化任务，以及（b）组合性，通过语义解析和句法转换的泛化准确性来衡量。结果显示，高比例代码预训练能提升结构化输出任务（如语义解析）和数学任务的性能，但同时可能损害对语言结构敏感的任务和现实世界知识任务的性能。

> Large language models are increasingly trained on corpora containing both natural language and non-linguistic data like source code. Aside from aiding programming-related tasks, anecdotal evidence suggests that including code in pretraining corpora may improve performance on other, unrelated tasks, yet to date no work has been able to establish a causal connection by controlling between language and code data. Here we do just this. We pretrain language models on datasets which interleave natural language and code in two different settings: additive, in which the total volume of data seen during pretraining is held constant; and competitive, in which the volume of language data is held constant. We study how the pretraining mixture affects performance on (a) a diverse collection of tasks included in the BigBench benchmark, and (b) compositionality, measured by generalization accuracy on semantic parsing and syntactic transformations. We find that pretraining on higher proportions of code improves performance on compositional tasks involving structured output (like semantic parsing), and mathematics. Conversely, increase code mixture can harm performance on other tasks, including on tasks that requires sensitivity to linguistic structure such as syntax or morphology, and tasks measuring real-world knowledge.

[Arxiv](https://arxiv.org/abs/2409.04556)