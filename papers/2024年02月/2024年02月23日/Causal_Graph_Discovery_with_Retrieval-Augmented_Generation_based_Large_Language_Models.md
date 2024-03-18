# 借助大规模检索增强型生成语言模型，探索和揭示因果图结构

发布时间：2024年02月23日

`RAG`

> Causal Graph Discovery with Retrieval-Augmented Generation based Large Language Models

> 因果图还原技术在因果推理领域扮演着核心角色，但传统的基于知识或统计推断的方法受限于数据偏见和个人对影响变量间关系因素的认知深度。如今，大型语言模型（LLMs）的进步为此类问题的解决带来了新的机遇。我们创新性地提出了一种新方法，它能深入挖掘庞大科学文献库中的丰富知识，从而有效应对通用因果图还原任务。此方法采用基于检索增强生成（RAG）的LLMs，系统地梳理和抽取海量研究论文中的关键信息。首先，我们从整合的文献资源中抽取出相关的文本片段；随后，LLM承担起识别与标注各因素间潜在联系的任务；最后，我们给出了一种融合这些关联关系以构建因果图的方法。实验证明，我们的方法仅依靠文献资料，便能在知名的SACHS数据集上成功构建出高质量的因果图。

> Causal graph recovery is essential in the field of causal inference. Traditional methods are typically knowledge-based or statistical estimation-based, which are limited by data collection biases and individuals' knowledge about factors affecting the relations between variables of interests. The advance of large language models (LLMs) provides opportunities to address these problems. We propose a novel method that utilizes the extensive knowledge contained within a large corpus of scientific literature to deduce causal relationships in general causal graph recovery tasks. This method leverages Retrieval Augmented-Generation (RAG) based LLMs to systematically analyze and extract pertinent information from a comprehensive collection of research papers. Our method first retrieves relevant text chunks from the aggregated literature. Then, the LLM is tasked with identifying and labelling potential associations between factors. Finally, we give a method to aggregate the associational relationships to build a causal graph. We demonstrate our method is able to construct high quality causal graphs on the well-known SACHS dataset solely from literature.

[Arxiv](https://arxiv.org/abs/2402.15301)