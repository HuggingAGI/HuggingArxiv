# Graph-DPEP：通过思维图推理进行少样本文档关系抽取的分解式即插即用和集成玩法

发布时间：2024年11月05日

`LLM应用` `关系抽取`

> Graph-DPEP: Decomposed Plug and Ensemble Play for Few-Shot Document Relation Extraction with Graph-of-Thoughts Reasoning

# 摘要

> 大型语言模型（LLMs）在大规模语料库上进行预训练，在许多自然语言处理（NLP）任务中展示出了令人印象深刻的少样本学习能力。将一个 NLP 任务重铸为文本到文本生成任务是一种常见做法，以便生成式 LLMs 能够被提示来解决它。然而，由于文档级关系抽取（DocRE）任务的结构化输出格式，使用生成式 LLM 模型执行该任务仍然具有挑战性，这使得向纯文本的转换变得复杂。在少样本和提示指令中可用的有限信息给文档中提到的实体的关系抽取带来了进一步的困难和挑战。在本文中，我们将结构化输出表示为图形样式的三元组，而不是自然语言表达式，并利用生成式 LLMs 来完成 DocRE 任务。我们的方法，即 Graph-DPEP 框架，基于自然语言中呈现的三元组解释思想背后的推理。在这个框架中，我们首先引入一种“分解-插入”方法，通过对带有类型空间分解的提示进行 LLMs 生成，以减轻区分所有关系类型的负担。其次，我们使用一个验证器来校准生成并识别被忽略的查询实体对。第三，我们开发了“集成-发挥”，通过利用与缺失查询对相关联的子图中嵌入的推理思想，在整个类型列表上重新应用生成，以解决缺失问题。通过与现有的提示技术和替代语言模型（LLMs）进行广泛比较，我们的框架在实验中的公开可用基准上表现出了卓越的性能。

> Large language models (LLMs) pre-trained on massive corpora have demonstrated impressive few-shot learning capability on many NLP tasks. Recasting an NLP task into a text-to-text generation task is a common practice so that generative LLMs can be prompted to resolve it. However, performing document-level relation extraction (DocRE) tasks with generative LLM models is still challenging due to the structured output format of DocRE, which complicates the conversion to plain text. Limited information available in few-shot samples and prompt instructions induce further difficulties and challenges in relation extraction for mentioned entities in a document. In this paper, we represent the structured output as a graph-style triplet rather than natural language expressions and leverage generative LLMs for the DocRE task. Our approach, the Graph-DPEP framework is grounded in the reasoning behind triplet explanation thoughts presented in natural language. In this framework, we first introduce a ``decomposed-plug" method for performing the generation from LLMs over prompts with type-space decomposition to alleviate the burden of distinguishing all relation types. Second, we employ a verifier for calibrating the generation and identifying overlooked query entity pairs. Third, we develop "ensemble-play", reapplying generation on the entire type list by leveraging the reasoning thoughts embedded in a sub-graph associated with the missing query pair to address the missingness issue. Through extensive comparisons with existing prompt techniques and alternative Language Models (LLMs), our framework demonstrates superior performance on publicly available benchmarks in experiments.

[Arxiv](https://arxiv.org/abs/2411.02864)