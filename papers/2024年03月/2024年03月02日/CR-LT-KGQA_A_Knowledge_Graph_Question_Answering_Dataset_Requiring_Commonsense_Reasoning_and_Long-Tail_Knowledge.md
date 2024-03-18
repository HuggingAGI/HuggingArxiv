# [CR-LT-KGQA 是一个专注于常识推理与长尾知识需求的知识图谱问答数据集，旨在提升模型在解决复杂问题时兼顾广泛而稀疏知识的能力。]

发布时间：2024年03月02日

`LLM应用`

> CR-LT-KGQA: A Knowledge Graph Question Answering Dataset Requiring Commonsense Reasoning and Long-Tail Knowledge

> KGQA作为一个成熟的领域，力图运用KG技术解答NL问题，展现卓越的事实检索能力。然而，当前的KGQA数据集面临两大短板：一是没有要求运用常识推理解决问题的数据集；二是多数数据集聚焦于那些LLMs可以直接、准确且无需参照KG就能作答的热门实体。在此背景下，我们的研究旨在构建一个创新的KGQA数据集——CR-LT-KGQA，它强调常识推理，并特别关注LLMs常出现臆想的长尾实体（如非主流或新近实体），从而催生出利用KG进行严谨事实推断的新方法。我们通过对Wikidata上StrategyQA和CREAK数据集加以拓展，设计出了包含问题回答和命题验证两个子任务的CR-LT-KGQA，以全面突破上述局限（1）和（2）。鉴于现有KGQA方法并不适用于处理常识推理问题，初步评估显示LLMs在CR-LT KGQA上臆想率较高。因此，CR-LT KGQA为检验易臆想的LLMs设定了严峻挑战，同时也为未来探索如何在LLM时代为长尾实体提供精准而有据的事实答案开辟了崭新的研究路径。

> Knowledge graph question answering (KGQA) is a well-established field that seeks to provide factual answers to natural language (NL) questions by leveraging knowledge graphs (KGs). However, existing KGQA datasets suffer from two significant limitations: (1) no existing KGQA dataset requires commonsense reasoning to arrive at an answer and (2) existing KGQA datasets focus on popular entities for which large language models (LLMs) can directly answer without hallucinating and without leveraging the KG. In this work, we seek a novel KGQA dataset that supports commonsense reasoning and focuses on long-tail entities (e.g., non-mainstream and recent entities) where LLMs frequently hallucinate, and thus create the need for novel methodologies that leverage the KG for factual and attributable commonsense inference. We create a novel Commonsense Reasoning (CR) and Long-Tail (LT) KGQA dataset with two subtasks -- question answering and claim verification -- that address both limitations (1) and (2). We construct CR-LT-KGQA by building extensions to existing reasoning datasets StrategyQA and CREAK over Wikidata. While existing KGQA methods are not applicable due to their lack of commonsense inference support, baseline evaluation of LLMs on CR-LT KGQA demonstrate a high rate of hallucination. Thus, CR-LT KGQA poses significant challenges for hallucination-prone LLMs, hence paving the way for future commonsense KGQA research to provide accurate and factual answers for long-tail entities in the era of LLMs.

[Arxiv](https://arxiv.org/abs/2403.01395)