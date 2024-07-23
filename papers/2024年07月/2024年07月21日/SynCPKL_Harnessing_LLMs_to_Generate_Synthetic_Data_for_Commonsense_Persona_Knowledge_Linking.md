# SynCPKL：借助 LLM 之力，为常识角色知识链接创造合成数据

发布时间：2024年07月21日

`LLM应用` `对话系统`

> SynCPKL: Harnessing LLMs to Generate Synthetic Data for Commonsense Persona Knowledge Linking

# 摘要

> 理解复杂对话需要NLP系统获取相关常识角色知识，但这一过程因上下文复杂和常识隐晦而颇具挑战。为此，我们参与了常识角色知识链接（CPKL）挑战，并提出了一种解决方案，旨在提升开放领域对话系统中角色与常识知识的整合。我们设计的SynCPKL Pipeline利用大型语言模型生成高质量合成数据集，用于训练角色知识链接器。为验证方法有效性，我们专门创建了SynCPKL数据集。实验结果显示，SynCPKL在训练角色知识链接器方面表现出色。我们的顶尖模型Derberta-SynCPKL在CPKL挑战中以16%的F1分数提升夺冠。相关资源已公开于https://github.com/irislin1006/CPKL。

> Understanding rich dialogues often requires NLP systems to access relevant commonsense persona knowledge, but retrieving this knowledge is challenging due to complex contexts and the implicit nature of commonsense. This paper presents our approach to the Commonsense Persona Knowledge Linking (CPKL) challenge, addressing the critical need for integrating persona and commonsense knowledge in open-domain dialogue systems. We introduce SynCPKL Pipeline, a pipeline that leverages Large Language Models to generate high-quality synthetic datasets for training commonsense persona knowledge linkers. To demonstrate the efficacy of our approach, we present SynCPKL, a new dataset specifically designed for this task. Our experiments validate the effectiveness of SynCPKL for training commonsense persona knowledge linkers. Additionally, our top-performing model, Derberta-SynCPKL, secured first place in the CPKL challenge by a 16% improvement in F1 score. We released both SynCPKL and Derberta-SynCPKL at https://github.com/irislin1006/CPKL.

[Arxiv](https://arxiv.org/abs/2407.15281)