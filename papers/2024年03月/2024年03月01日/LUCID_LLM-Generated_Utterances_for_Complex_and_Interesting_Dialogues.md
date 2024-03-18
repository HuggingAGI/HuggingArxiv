# [LUCID：针对复杂且引人入胜的对话，利用LLM技术生成高质量话语]

发布时间：2024年03月01日

`LLM应用`

> LUCID: LLM-Generated Utterances for Complex and Interesting Dialogues

> 随着基于变压器的大型语言模型（LLMs）技术的突飞猛进，虚拟助手在对话交互能力上即将实现质的飞跃。但要实现真正的任务导向对话革新，一个关键难题依然存在，那就是高质量且语言复杂度高的对话数据极度匮乏。尽管现有的大规模数据集令人印象深刻，但在领域覆盖及包含真正富有挑战性的对话情境方面却有所欠缺，而且这些复杂情境往往没有明确标注，导致难以准确评估模型性能，只能依赖耗时费力的人工评价。此外，以往构建高质量对话数据集的过程严重依赖人工投入，既限制了数据集的规模，也不利于迅速为新的目标领域生成训练数据。为此，我们引入了一款名为LUCID的模块化、高度自动化LLM驱动的数据生成系统，它可以创造出真实、多样且富有挑战性的对话实例。通过LUCID，我们成功生成了一个涵盖100种意图、由4,277段多领域、多意图对话组成的示范数据集，其中包含了丰富多样的对话难题和用户行为模式，并借助一套简洁明了的回合标签来方便地识别各类现象。另外，我们还分别提供了针对已知意图和未知意图的独立测试集，以便于进行便捷的离分布评估。目前，我们已经公开了LUCID的数据生成代码及其所生成的数据集。

> Virtual assistants are poised to take a dramatic leap forward in terms of their dialogue capabilities, spurred by recent advances in transformer-based Large Language Models (LLMs). Yet a major bottleneck to achieving genuinely transformative task-oriented dialogue capabilities remains the scarcity of high quality and linguistically sophisticated data. Existing datasets, while impressive in scale, have limited domain coverage and contain few genuinely challenging conversational phenomena; those which are present are typically unlabelled, making it difficult to assess the strengths and weaknesses of models without time-consuming and costly human evaluation. Moreover, creating high quality dialogue data has until now required considerable human input, limiting both the scale of these datasets and the ability to rapidly bootstrap data for a new target domain. We aim to overcome these issues with LUCID, a modularised and highly automated LLM-driven data generation system that produces realistic, diverse and challenging dialogues. We use LUCID to generate a seed dataset of 4,277 multi-domain, multi-intent conversations across 100 intents to demonstrate its capabilities. The generated conversations include a wide range of challenging phenomena and diverse user behaviour, conveniently identifiable via a set of turn-level tags. Finally, we provide separate test sets for seen and unseen intents, allowing for convenient out-of-distribution evaluation. We release both the data generation code and the dataset itself.

[Arxiv](https://arxiv.org/abs/2403.00462)