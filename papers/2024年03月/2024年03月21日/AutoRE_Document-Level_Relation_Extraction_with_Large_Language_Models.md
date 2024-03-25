# AutoRE 是一种运用大型语言模型实现的文档级关系抽取技术。

发布时间：2024年03月21日

`LLM应用` `信息抽取` `文档理解`

> AutoRE: Document-Level Relation Extraction with Large Language Models

> LLMs在理解和生成文本方面成就斐然，使得大量研究者开始探索其在信息抽取（如RE）领域的应用。不过，当前多数方法主要针对包含单一句子内部有限关系和三元事实的句子级关系抽取（SentRE）任务设计。而在面对需要处理文档内多个关系及分布广泛的三元组事实的文档级关系抽取（DocRE）任务时，一些基于候选关系选择融入提示模板的方法往往显得效率不高且性能不尽人意。为此，我们提出了AutoRE——一种采用创新的RHF（关系-头-事实）抽取范式的端到端DocRE模型。与众不同的是，AutoRE无需预设已知关系选项，从而更贴合实际应用场景。同时，我们借助参数高效微调算法QLoRA构建了一个易拓展的RE框架。实验证明，在RE-DocRED数据集上，AutoRE展现出了卓越性能，分别在验证集和测试集上取得了比TAG高出10.03%和9.03%的最新研究成果。

> Large Language Models (LLMs) have demonstrated exceptional abilities in comprehending and generating text, motivating numerous researchers to utilize them for Information Extraction (IE) purposes, including Relation Extraction (RE). Nonetheless, most existing methods are predominantly designed for Sentence-level Relation Extraction (SentRE) tasks, which typically encompass a restricted set of relations and triplet facts within a single sentence. Furthermore, certain approaches resort to treating relations as candidate choices integrated into prompt templates, leading to inefficient processing and suboptimal performance when tackling Document-Level Relation Extraction (DocRE) tasks, which entail handling multiple relations and triplet facts distributed across a given document, posing distinct challenges. To overcome these limitations, we introduce AutoRE, an end-to-end DocRE model that adopts a novel RE extraction paradigm named RHF (Relation-Head-Facts). Unlike existing approaches, AutoRE does not rely on the assumption of known relation options, making it more reflective of real-world scenarios. Additionally, we have developed an easily extensible RE framework using a Parameters Efficient Fine Tuning (PEFT) algorithm (QLoRA). Our experiments on the RE-DocRED dataset showcase AutoRE's best performance, achieving state-of-the-art results, surpassing TAG by 10.03% and 9.03% respectively on the dev and test set.

[Arxiv](https://arxiv.org/abs/2403.14888)