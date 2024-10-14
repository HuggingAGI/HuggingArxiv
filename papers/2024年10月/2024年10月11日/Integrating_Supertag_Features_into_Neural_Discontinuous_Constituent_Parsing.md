# 融合 Supertag 特征至神经断续成分解析

发布时间：2024年10月11日

`其他` `句法分析`

> Integrating Supertag Features into Neural Discontinuous Constituent Parsing

# 摘要

> 句法分析在自然语言处理中至关重要，成分结构是广泛使用的句法描述之一。传统观点要求成分由相邻单词组成，但在分析德语等语言中的非局部依赖关系时存在挑战。因此，多个树库通过交叉边表示长距离依赖。基于转换的解析通过消除显式语法需求，利用神经网络在大规模标注语料库上生成树结构。Coavoux和Cohen（2019）提出的无栈解析器在二次时间内推导出不连续成分树。本研究旨在探讨将超标签信息引入不连续成分解析。在CCG等词汇化语法中，超标签指示单词的结构角色和句法关系。研究通过专用超标签器和联合训练神经模型来整合超标签信息。此外，还将比较其他框架和序列标注任务在作为解析辅助任务方面的适用性。

> Syntactic parsing is essential in natural-language processing, with constituent structure being one widely used description of syntax. Traditional views of constituency demand that constituents consist of adjacent words, but this poses challenges in analysing syntax with non-local dependencies, common in languages like German. Therefore, in a number of treebanks like NeGra and TIGER for German and DPTB for English, long-range dependencies are represented by crossing edges. Various grammar formalisms have been used to describe discontinuous trees - often with high time complexities for parsing. Transition-based parsing aims at reducing this factor by eliminating the need for an explicit grammar. Instead, neural networks are trained to produce trees given raw text input using supervised learning on large annotated corpora. An elegant proposal for a stack-free transition-based parser developed by Coavoux and Cohen (2019) successfully allows for the derivation of any discontinuous constituent tree over a sentence in worst-case quadratic time.
  The purpose of this work is to explore the introduction of supertag information into transition-based discontinuous constituent parsing. In lexicalised grammar formalisms like CCG (Steedman, 1989) informative categories are assigned to the words in a sentence and act as the building blocks for composing the sentence's syntax. These supertags indicate a word's structural role and syntactic relationship with surrounding items. The study examines incorporating supertag information by using a dedicated supertagger as additional input for a neural parser (pipeline) and by jointly training a neural model for both parsing and supertagging (multi-task). In addition to CCG, several other frameworks (LTAG-spinal, LCFRS) and sequence labelling tasks (chunking, dependency parsing) will be compared in terms of their suitability as auxiliary tasks for parsing.

[Arxiv](https://arxiv.org/abs/2410.08766)