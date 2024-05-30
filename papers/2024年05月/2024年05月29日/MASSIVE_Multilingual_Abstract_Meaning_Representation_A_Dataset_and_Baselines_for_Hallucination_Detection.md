# 大规模多语言抽象意义表示：幻觉检测的数据集与基准

发布时间：2024年05月29日

`LLM应用

这篇论文介绍了MASSIVE-AMR数据集的开发，这是一个大规模的多语言AMR（抽象意义表示）数据集，用于支持多语言的语义分析。论文中提到了利用大型语言模型（LLMs）进行多语言AMR和SPARQL解析的实验，以及在知识库问答中应用AMR检测幻觉的成效。这些内容表明，该论文主要关注的是LLM在实际应用中的使用，特别是在多语言语义分析和知识库问答领域的应用，因此将其归类为LLM应用。` `知识图谱`

> MASSIVE Multilingual Abstract Meaning Representation: A Dataset and Baselines for Hallucination Detection

# 摘要

> 抽象意义表示（AMR）是一种能够捕捉话语核心意义的语义形式。尽管AMR语料库的开发在英语及其他语言中已取得显著进展，但现有数据集的规模有限及注释成本高昂，仍是一大挑战。为此，我们推出了MASSIVE-AMR，一个包含超过84,000个文本至图形注释的数据集，是目前最大且最多样的AMR资源：涵盖1,685个信息寻求话语，并映射至50多种语言。我们详细介绍了该资源的构建过程及其独特之处，并报告了利用大型语言模型进行多语言AMR和SPARQL解析的实验结果，以及在知识库问答中应用AMR检测幻觉的成效，这些结果为我们揭示了使用LLMs进行结构化解析时面临的持续挑战。

> Abstract Meaning Representation (AMR) is a semantic formalism that captures the core meaning of an utterance. There has been substantial work developing AMR corpora in English and more recently across languages, though the limited size of existing datasets and the cost of collecting more annotations are prohibitive. With both engineering and scientific questions in mind, we introduce MASSIVE-AMR, a dataset with more than 84,000 text-to-graph annotations, currently the largest and most diverse of its kind: AMR graphs for 1,685 information-seeking utterances mapped to 50+ typologically diverse languages. We describe how we built our resource and its unique features before reporting on experiments using large language models for multilingual AMR and SPARQL parsing as well as applying AMRs for hallucination detection in the context of knowledge base question answering, with results shedding light on persistent issues using LLMs for structured parsing.

![大规模多语言抽象意义表示：幻觉检测的数据集与基准](../../../paper_images/2405.19285/x1.png)

[Arxiv](https://arxiv.org/abs/2405.19285)