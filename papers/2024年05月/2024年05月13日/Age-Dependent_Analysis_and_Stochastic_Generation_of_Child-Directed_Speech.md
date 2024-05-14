# 针对儿童言语的年龄相关分析与随机生成在这项研究中，我们探讨了儿童言语的年龄依赖性特征，并开发了一种随机生成模型，旨在更自然地模拟儿童导向的交流方式。通过深入分析不同年龄段儿童的言语特点，我们的模型能够生成更符合儿童理解和接受能力的语言，为儿童语言学习和交流提供了新的工具。

发布时间：2024年05月13日

`LLM应用

理由：这篇论文探讨了如何利用语言模型（LM）来分析儿童导向言语（CDS）的年龄相关特性，并通过模型生成符合儿童年龄特点的合成CDS。这表明研究是应用层面的，即如何将大型语言模型（LLM）应用于特定的语言分析任务，而不是专注于LLM的理论研究或Agent的设计与实现，也不是关于检索增强生成（RAG）的研究。因此，它属于LLM应用分类。` `儿童语言发展` `语言模型`

> Age-Dependent Analysis and Stochastic Generation of Child-Directed Speech

# 摘要

> 儿童导向言语（CDS）是成人对幼儿说话时采用的一种特殊语言形式，其特点会随着儿童年龄等非语言因素的变化而变化。本研究利用语言模型（LM）分析了CDS的年龄相关特性，该模型基于CHILDES数据库中的CDS转录和儿童年龄数据进行训练。通过该模型，我们能够生成符合儿童年龄特点的合成CDS，从而在数据规模上超越原始资源。研究比较了合成CDS与实际儿童言语的特征，发现LM成功捕捉了CDS随年龄的变化，尽管在词汇量上略有差异。此外，我们还系统性地分析了CHILDES中CDS随年龄变化的特性，揭示了CDS各方面如何与儿童成长同步演变。

> Child-directed speech (CDS) is a particular type of speech that adults use when addressing young children. Its properties also change as a function of extralinguistic factors, such as age of the child being addressed. Access to large amounts of representative and varied CDS would be useful for child language research, as this would enable controlled computational modeling experiments of infant language acquisition with realistic input in terms of quality and quantity. In this study, we describe an approach to model age-dependent linguistic properties of CDS using a language model (LM) trained on CDS transcripts and ages of the recipient children, as obtained from North American English corpora of the CHILDES database. The created LM can then be used to stochastically generate synthetic CDS transcripts in an age-appropriate manner, thereby scaling beyond the original datasets in size. We compare characteristics of the generated CDS against the real speech addressed at children of different ages, showing that the LM manages to capture age-dependent changes in CDS, except for a slight difference in the effective vocabulary size. As a side product, we also provide a systematic characterization of age-dependent linguistic properties of CDS in CHILDES, illustrating how all measured aspects of the CDS change with children's age.

[Arxiv](https://arxiv.org/abs/2405.07700)