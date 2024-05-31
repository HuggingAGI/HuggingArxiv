# 一标记之力！探索可扩展与可插拔的虚拟标记，助力大型语言模型检索增强。

发布时间：2024年05月29日

`RAG

理由：这篇论文主要关注的是检索增强生成（RAG）技术在大型语言模型（LLMs）中的应用，特别是提出了一种新的方法来优化RAG，即通过学习可扩展且可插拔的虚拟令牌来优化RAG。这种方法旨在提升模型的性能同时保持其通用生成能力，这与RAG技术的核心目标相符。因此，这篇论文应归类于RAG。` `问答系统`

> One Token Can Help! Learning Scalable and Pluggable Virtual Tokens for Retrieval-Augmented Large Language Models

# 摘要

> 检索增强生成（RAG）为提升大型语言模型（LLMs）生成更准确、及时的内容提供了新途径。现有技术或是通过优化提示引导LLMs利用检索信息，或是直接微调模型以适应RAG环境。虽然微调能提升性能，但往往牺牲了模型的通用生成能力。这一局限在已部署的LLMs中尤为突出，因为参数调整可能影响其原有功能。为此，我们提出了一种创新方法，即通过学习可扩展且可插拔的虚拟令牌来优化RAG。这种方法在保持LLMs原始参数不变的同时，仅微调这些令牌的嵌入，既增强了性能，又保留了模型的通用生成能力。我们还设计了多种训练策略，以增强方法的灵活性和泛化性。在九项问答任务上的广泛实验验证了我们的方法的优越性。

> Retrieval-augmented generation (RAG) is a promising way to improve large language models (LLMs) for generating more factual, accurate, and up-to-date content. Existing methods either optimize prompts to guide LLMs in leveraging retrieved information or directly fine-tune the LLMs to adapt to RAG scenarios. Although fine-tuning can yield better performance, it often compromises the LLMs' general generation capabilities by modifying their parameters. This limitation poses challenges in practical applications, especially when LLMs are already deployed, as parameter adjustments may affect their original functionality. To address this, we propose a novel method that involves learning scalable and pluggable virtual tokens for RAG. By maintaining the LLMs' original parameters and fine-tuning only the embeddings of these pluggable tokens, our approach not only enhances LLMs' performance but also preserves their general generation capacities. Furthermore, we design several training strategies to improve the scalability, flexibility, and generalizability of our method. Comprehensive experiments across nine question-answering tasks demonstrate the superiority of our approach.

![一标记之力！探索可扩展与可插拔的虚拟标记，助力大型语言模型检索增强。](../../../paper_images/2405.19670/x1.png)

![一标记之力！探索可扩展与可插拔的虚拟标记，助力大型语言模型检索增强。](../../../paper_images/2405.19670/x2.png)

![一标记之力！探索可扩展与可插拔的虚拟标记，助力大型语言模型检索增强。](../../../paper_images/2405.19670/x3.png)

![一标记之力！探索可扩展与可插拔的虚拟标记，助力大型语言模型检索增强。](../../../paper_images/2405.19670/x4.png)

![一标记之力！探索可扩展与可插拔的虚拟标记，助力大型语言模型检索增强。](../../../paper_images/2405.19670/x5.png)

[Arxiv](https://arxiv.org/abs/2405.19670)