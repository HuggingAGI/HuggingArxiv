# 使用动态 VQA 数据集和自适应规划代理对多模态检索增强生成进行基准测试

发布时间：2024年11月06日

`RAG` `多模态` `视觉问答`

> Benchmarking Multimodal Retrieval Augmented Generation with Dynamic VQA Dataset and Self-adaptive Planning Agent

# 摘要

> 多模态检索增强生成（mRAG）在缓解多模态大型语言模型（MLLMs）固有的“幻觉”问题方面发挥着重要作用。尽管前景看好，但现有的启发式 mRAG 通常预先定义了固定的检索过程，这导致了两个问题：（1）非自适应检索查询。（2）过载的检索查询。然而，这些缺陷无法通过当前的知识寻求视觉问答（VQA）数据集得到充分反映，因为最需要的知识可以通过标准的两步检索轻松获得。为了弥补数据集的差距，我们首先构建 Dyn-VQA 数据集，它由三种类型的“动态”问题组成，这些问题需要在查询、工具和时间上可变的复杂知识检索策略：（1）答案快速变化的问题。（2）需要多模态知识的问题。（3）多跳问题。在 Dyn-VQA 上的实验表明，由于其僵化的检索过程，现有的启发式 mRAG 难以为动态问题提供足够且精确相关的知识。因此，我们进一步提出了第一个用于多模态检索的自适应规划代理，OmniSearch。其基本思想是模拟人类在解决问题时的行为，将复杂的多模态问题动态分解为带有检索动作的子问题链。大量实验证明了我们的 OmniSearch 的有效性，也为推进 mRAG 提供了方向。代码和数据集将在 https://github.com/Alibaba-NLP/OmniSearch 开源。

> Multimodal Retrieval Augmented Generation (mRAG) plays an important role in mitigating the "hallucination" issue inherent in multimodal large language models (MLLMs). Although promising, existing heuristic mRAGs typically predefined fixed retrieval processes, which causes two issues: (1) Non-adaptive Retrieval Queries. (2) Overloaded Retrieval Queries. However, these flaws cannot be adequately reflected by current knowledge-seeking visual question answering (VQA) datasets, since the most required knowledge can be readily obtained with a standard two-step retrieval. To bridge the dataset gap, we first construct Dyn-VQA dataset, consisting of three types of "dynamic" questions, which require complex knowledge retrieval strategies variable in query, tool, and time: (1) Questions with rapidly changing answers. (2) Questions requiring multi-modal knowledge. (3) Multi-hop questions. Experiments on Dyn-VQA reveal that existing heuristic mRAGs struggle to provide sufficient and precisely relevant knowledge for dynamic questions due to their rigid retrieval processes. Hence, we further propose the first self-adaptive planning agent for multimodal retrieval, OmniSearch. The underlying idea is to emulate the human behavior in question solution which dynamically decomposes complex multimodal questions into sub-question chains with retrieval action. Extensive experiments prove the effectiveness of our OmniSearch, also provide direction for advancing mRAG. The code and dataset will be open-sourced at https://github.com/Alibaba-NLP/OmniSearch.

[Arxiv](https://arxiv.org/abs/2411.02937)