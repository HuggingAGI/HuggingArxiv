# [为提升检索增强型观点摘要的效果，我们引入了层次化索引技术。该方法旨在通过构建多层次的索引结构，有效组织和检索相关文本信息，从而优化观点总结的质量与效率。]

发布时间：2024年03月01日

`LLM应用`

> Hierarchical Indexing for Retrieval-Augmented Opinion Summarization

> 我们创新性地提出了一种名为HIRO的无监督抽象观点摘要方法，它巧妙融合了抽取式方法的优点——可追溯性和规模化处理能力，以及LLMs带来的文本连贯性和自然流畅度。HIRO通过学习构建索引结构，在一个语义有序的离散层次中为各句子定位路径。在实际应用时，我们会充实这个索引，并用它来精准定位及抽取输入评论中蕴含主流观点的句子集合。随后，借助预训练好的LLM，我们将依据这些挖掘出的证据簇生成易于理解且有根有据的摘要。由于HIRO设计上的模块化特性，我们可以逐阶段评估它的效能。实验结果显示，HIRO所构建的编码空间相较于之前的研究具有更强的语义结构，并能生成更贴合原始评论观点的代表性摘要。而进一步的人工评估证实，与同类方法相比，HIRO生成的摘要在连贯性、详尽程度和准确性上均有显著提升，深受注解员们的青睐。

> We propose a method for unsupervised abstractive opinion summarization, that combines the attributability and scalability of extractive approaches with the coherence and fluency of Large Language Models (LLMs). Our method, HIRO, learns an index structure that maps sentences to a path through a semantically organized discrete hierarchy. At inference time, we populate the index and use it to identify and retrieve clusters of sentences containing popular opinions from input reviews. Then, we use a pretrained LLM to generate a readable summary that is grounded in these extracted evidential clusters. The modularity of our approach allows us to evaluate its efficacy at each stage. We show that HIRO learns an encoding space that is more semantically structured than prior work, and generates summaries that are more representative of the opinions in the input reviews. Human evaluation confirms that HIRO generates more coherent, detailed and accurate summaries that are significantly preferred by annotators compared to prior work.

[Arxiv](https://arxiv.org/abs/2403.00435)