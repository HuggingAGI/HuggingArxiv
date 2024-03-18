# [我们提出了一种混合检索增强生成方法，以实现联邦推荐系统。该方法巧妙结合了检索和生成技术，在保护用户数据隐私的同时，有效提升了推荐系统的性能和准确性。步骤 1：联邦推荐是通过混合检索增强生成技术实现的。步骤 2：在保证用户数据隐私的前提下，一种名为“混合检索增强生成”的创新技术被应用于联邦推荐场景中，旨在融合检索与生成策略，以优化推荐效果并保障数据安全性。]

发布时间：2024年03月07日

`Agent`

> Federated Recommendation via Hybrid Retrieval Augmented Generation

> 为了在保障用户隐私的同时提升推荐效果，新兴的联邦推荐（FR）技术应运而生。不过，传统FR系统在处理用户/项目时，受限于使用离散ID表达，易受数据稀疏与异构的影响，性能大打折扣。与此同时，LLMs已证实其在各类推荐场景下作为推荐器的有效性，但其在真实场景应用时，仍存在推理效率低下及潜在虚幻生成的风险。为此，我们创新设计了GPT-FedRec——一个融合ChatGPT和新颖混合检索增强生成（RAG）机制的联邦推荐框架。GPT-FedRec采取双阶段工作流程，首先通过混合检索手段提炼出基于ID的用户行为模式以及基于文本的项目特征；继而在获取检索结果后，将其转译为文本提示输入至GPT以实现重新排序。这一独创的混合检索机制结合LLM重排序策略，旨在深度挖掘数据中的泛化特征并充分利用LLM内在的预训练知识，有效应对FR中的数据稀疏与异构难题。此外，RAG方法还有助于抑制LLM的虚假生成现象，从而切实提高针对现实用户的推荐表现。在多个权威基准数据集上的实验证明，GPT-FedRec相较于当前最先进方法展现出了卓越的性能优势。

> Federated Recommendation (FR) emerges as a novel paradigm that enables privacy-preserving recommendations. However, traditional FR systems usually represent users/items with discrete identities (IDs), suffering from performance degradation due to the data sparsity and heterogeneity in FR. On the other hand, Large Language Models (LLMs) as recommenders have proven effective across various recommendation scenarios. Yet, LLM-based recommenders encounter challenges such as low inference efficiency and potential hallucination, compromising their performance in real-world scenarios. To this end, we propose GPT-FedRec, a federated recommendation framework leveraging ChatGPT and a novel hybrid Retrieval Augmented Generation (RAG) mechanism. GPT-FedRec is a two-stage solution. The first stage is a hybrid retrieval process, mining ID-based user patterns and text-based item features. Next, the retrieved results are converted into text prompts and fed into GPT for re-ranking. Our proposed hybrid retrieval mechanism and LLM-based re-rank aims to extract generalized features from data and exploit pretrained knowledge within LLM, overcoming data sparsity and heterogeneity in FR. In addition, the RAG approach also prevents LLM hallucination, improving the recommendation performance for real-world users. Experimental results on diverse benchmark datasets demonstrate the superior performance of GPT-FedRec against state-of-the-art baseline methods.

[Arxiv](https://arxiv.org/abs/2403.04256)