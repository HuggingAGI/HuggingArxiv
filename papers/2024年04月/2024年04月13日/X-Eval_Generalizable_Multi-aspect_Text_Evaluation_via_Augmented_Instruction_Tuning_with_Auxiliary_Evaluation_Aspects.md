# X-Eval：一种通过增强指令调整和辅助评估维度，实现文本多方面评估的通用方法。

发布时间：2024年04月13日

`LLM应用` `评估框架`

> X-Eval: Generalizable Multi-aspect Text Evaluation via Augmented Instruction Tuning with Auxiliary Evaluation Aspects

# 摘要

> 自然语言生成（NLG）任务的评估往往需要从多个维度（如文本的连贯性和自然度）对生成的文本进行综合考量。但这种多维度的评估方法颇具挑战，因为它要求评估者即使在训练阶段未接触到某些评估维度，也需对其进行泛化评估。本文提出了X-Eval，这是一个分两阶段的指令调优框架，旨在评估文本在用户自定义的已知和未知维度上的表现。X-Eval包含两个学习阶段：基础的指令调优阶段，旨在提升模型遵循评估指令的能力；以及进阶的指令调优阶段，通过挖掘细粒度评估维度之间的联系，更准确地评估文本质量。为训练X-Eval，我们创建了AspectInstruct数据集，这是首个专为多维度NLG评估设计的指令调优数据集，覆盖了27个不同的评估维度和65个任务。为增加任务多样性，我们采用了一种增强策略，将人工评分注释转换成多样的NLG评估任务形式，包括评分、比较、排序和布尔问题解答。通过在对话生成、摘要和数据到文本这三个关键NLG任务类别上的广泛实验，以及元评估中的21个维度，我们证明了X-Eval能够使即使是轻量级语言模型也能与最先进的NLG评估器（例如GPT-4）相媲美，甚至在与人类判断的相关性上更胜一筹。

> Natural Language Generation (NLG) typically involves evaluating the generated text in various aspects (e.g., consistency and naturalness) to obtain a comprehensive assessment. However, multi-aspect evaluation remains challenging as it may require the evaluator to generalize to any given evaluation aspect even if it's absent during training. In this paper, we introduce X-Eval, a two-stage instruction tuning framework to evaluate the text in both seen and unseen aspects customized by end users. X-Eval consists of two learning stages: the vanilla instruction tuning stage that improves the model's ability to follow evaluation instructions, and an enhanced instruction tuning stage that exploits the connections between fine-grained evaluation aspects to better assess text quality. To support the training of X-Eval, we collect AspectInstruct, the first instruction tuning dataset tailored for multi-aspect NLG evaluation spanning 27 diverse evaluation aspects with 65 tasks. To enhance task diversity, we devise an augmentation strategy that converts human rating annotations into diverse forms of NLG evaluation tasks, including scoring, comparison, ranking, and Boolean question answering. Extensive experiments across three essential categories of NLG tasks: dialogue generation, summarization, and data-to-text coupled with 21 aspects in meta-evaluation, demonstrate that our X-Eval enables even a lightweight language model to achieve a comparable if not higher correlation with human judgments compared to the state-of-the-art NLG evaluators, such as GPT-4.

[Arxiv](https://arxiv.org/abs/2311.08788)