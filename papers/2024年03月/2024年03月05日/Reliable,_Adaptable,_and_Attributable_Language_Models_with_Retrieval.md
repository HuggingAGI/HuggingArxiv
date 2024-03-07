# [致力于构建可靠、灵活且具有明确来源的检索型语言模型，以提升其性能和可信度。](https://arxiv.org/abs/2403.03187)

> Reliable, Adaptable, and Attributable Language Models with Retrieval

发布时间：2024年03月05日

> 参数化语言模型（LMs）凭借海量网络数据的训练展现出了非凡的灵活度和功能，但仍然受到诸如产生幻觉、难于适应新数据分布及缺乏可验证性等问题的困扰。本文主张下一代LM应以增强检索型LM替代参数LM，其在推理过程中融入大规模数据存储库，从而提高可靠性、适应性和可溯源性。尽管前景广阔，增强检索型LM因诸多难题尚未普及，特别是在知识密集型任务如问答之外，如何有效利用辅助文本、检索与LM组件间交互不足以及缺乏规模化训练和推理所需基础设施等方面存在问题。为此，我们提出了一项构建通用型增强检索LM的发展规划，内容涵盖重新审视数据存储和检索机制、探究强化检索器与LM互动的流程设计，以及大力投资建设高效训练和推理所需的基础设施。

> Parametric language models (LMs), which are trained on vast amounts of web data, exhibit remarkable flexibility and capability. However, they still face practical challenges such as hallucinations, difficulty in adapting to new data distributions, and a lack of verifiability. In this position paper, we advocate for retrieval-augmented LMs to replace parametric LMs as the next generation of LMs. By incorporating large-scale datastores during inference, retrieval-augmented LMs can be more reliable, adaptable, and attributable. Despite their potential, retrieval-augmented LMs have yet to be widely adopted due to several obstacles: specifically, current retrieval-augmented LMs struggle to leverage helpful text beyond knowledge-intensive tasks such as question answering, have limited interaction between retrieval and LM components, and lack the infrastructure for scaling. To address these, we propose a roadmap for developing general-purpose retrieval-augmented LMs. This involves a reconsideration of datastores and retrievers, the exploration of pipelines with improved retriever-LM interaction, and significant investment in infrastructure for efficient training and inference.

`RAG`