# [CoGenesis 是一种创新框架，它巧妙地整合了大型和小型语言模型的力量，旨在实现安全且具备情境感知能力的指令执行。](https://arxiv.org/abs/2403.03129)

发布时间：2024年03月05日

`Agent`

> CoGenesis: A Framework Collaborating Large and Small Language Models for Secure Context-Aware Instruction Following

> 随着语言模型技术的发展，其对私密数据的接触难以避免，且越来越多的小型模型开始被部署在个人设备上，形成了一股潮流。在满载用户信息的场景下，如何让模型既保证用户隐私安全，又能高效执行任务，成为了亟待研究的关键问题。为此，本文提出了名为CoGenesis的协同生成框架，它巧妙地融合了云端的大规模模型与本地设备上的小型模型，以逻辑化的方式应对隐私难题。首先，我们构建了一条流水线，专门用来生成带有丰富上下文信息的个性化写作指导数据集，用作探究此问题的研究平台。接着，我们基于草图和logits原理，推出了两种CoGenesis的不同版本。实验结果显示，在使用综合数据集以及另外两个开源数据集的基础上，我们可以得出三点结论：1）大规模模型在获得用户上下文时表现卓越，而在缺失这些上下文时则显得力不从心；2）尽管针对合成数据集进行精细调优的小型专业模型颇具潜力，但整体性能仍不及大型模型；3）运用不同规模模型组合而成的CoGenesis框架展现出了强大的竞争力，为解决隐私问题提供了一种切实可行的方案。

> With the advancement of language models (LMs), their exposure to private data is increasingly inevitable, and their deployment (especially for smaller ones) on personal devices, such as PCs and smartphones, has become a prevailing trend. In contexts laden with user information, enabling models to both safeguard user privacy and execute commands efficiently emerges as an essential research imperative. In this paper, we propose CoGenesis, a collaborative generation framework integrating large (hosted on cloud infrastructure) and small models (deployed on local devices) to address privacy concerns logically. Initially, we design a pipeline to create personalized writing instruction datasets enriched with extensive context details as the testbed of this research issue. Subsequently, we introduce two variants of CoGenesis based on sketch and logits respectively. Our experimental findings, based on our synthesized dataset and two additional open-source datasets, indicate that: 1) Large-scale models perform well when provided with user context but struggle in the absence of such context. 2) While specialized smaller models fine-tuned on the synthetic dataset show promise, they still lag behind their larger counterparts. 3) Our CoGenesis framework, utilizing mixed-scale models, showcases competitive performance, providing a feasible solution to privacy issues.

[Arxiv](https://arxiv.org/abs/2403.03129)