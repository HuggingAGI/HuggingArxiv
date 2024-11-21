# 扩大成员推理：大型语言模型上的攻击何时以及怎样才能成功

发布时间：2024年10月31日

`LLM应用` `语言模型` `会员资格推断攻击`

> Scaling Up Membership Inference: When and How Attacks Succeed on Large Language Models

# 摘要

> 会员资格推断攻击（MIA）旨在验证给定数据样本是否属于某模型训练集。近年来，随着大型语言模型（LLM）的快速发展，MIA 备受关注。很多人担忧训练中使用受版权保护的材料，并呼吁有检测此类使用的方法。然而，近期研究大多表明，当前的 MIA 方法在 LLM 上并不奏效。即便看似有效，通常也是因为实验设置欠佳，存在其他能“作弊”的捷径特征。在本研究中，我们认为 MIA 对 LLM 仍有效，不过仅在测试时呈现多个文档的情况下才行。我们构建了新的基准，以连续的数据样本规模（从句子（n-gram）到文档集合（多个标记块））来衡量 MIA 的表现。为在更大规模上验证当前 MIA 方法的效果，我们将近期关于数据集推断（DI）的工作用于二元会员资格检测任务，它聚合段落级 MIA 特征，从而在文档和文档集合层面实现 MIA。此基线在预训练和微调的 LLM 上首次成功达成了 MIA。

> Membership inference attacks (MIA) attempt to verify the membership of a given data sample in the training set for a model. MIA has become relevant in recent years, following the rapid development of large language models (LLM). Many are concerned about the usage of copyrighted materials for training them and call for methods for detecting such usage. However, recent research has largely concluded that current MIA methods do not work on LLMs. Even when they seem to work, it is usually because of the ill-designed experimental setup where other shortcut features enable "cheating." In this work, we argue that MIA still works on LLMs, but only when multiple documents are presented for testing. We construct new benchmarks that measure the MIA performances at a continuous scale of data samples, from sentences (n-grams) to a collection of documents (multiple chunks of tokens). To validate the efficacy of current MIA approaches at greater scales, we adapt a recent work on Dataset Inference (DI) for the task of binary membership detection that aggregates paragraph-level MIA features to enable MIA at document and collection of documents level. This baseline achieves the first successful MIA on pre-trained and fine-tuned LLMs.

[Arxiv](https://arxiv.org/abs/2411.00154)