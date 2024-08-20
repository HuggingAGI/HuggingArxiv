# 通过组合实现分布外泛化，这一视角通过 Transformer 中的归纳头得以透视。

发布时间：2024年08月18日

`LLM理论` `人工智能` `机器学习`

> Out-of-distribution generalization via composition: a lens through induction heads in Transformers

# 摘要

> GPT-4等大型语言模型有时展现出创造力，仅需几个示例就能解决新任务，这要求模型在训练数据之外的分布上进行泛化，即分布外（OOD）泛化。尽管LLMs成就斐然，其OOD泛化机制仍待深入探索。我们研究了基于隐藏规则生成实例的情境下的OOD泛化，包括符号推理的上下文学习。模型需在不微调的情况下推断隐藏规则。  通过合成示例和预训练LLMs的广泛实验，我们聚焦于归纳头部组件，发现OOD泛化与组合紧密相关——模型通过组合自注意力层学习规则，实现OOD泛化。嵌入空间中的共享潜在子空间通过对齐层间关系，成为组合的桥梁，即共同桥梁表示假设。

> Large language models (LLMs) such as GPT-4 sometimes appear to be creative, solving novel tasks often with a few demonstrations in the prompt. These tasks require the models to generalize on distributions different from those from training data -- which is known as out-of-distribution (OOD) generalization. Despite the tremendous success of LLMs, how they approach OOD generalization remains an open and underexplored question. We examine OOD generalization in settings where instances are generated according to hidden rules, including in-context learning with symbolic reasoning. Models are required to infer the hidden rules behind input prompts without any fine-tuning.
  We empirically examined the training dynamics of Transformers on a synthetic example and conducted extensive experiments on a variety of pretrained LLMs, focusing on a type of components known as induction heads. We found that OOD generalization and composition are tied together -- models can learn rules by composing two self-attention layers, thereby achieving OOD generalization. Furthermore, a shared latent subspace in the embedding (or feature) space acts as a bridge for composition by aligning early layers and later layers, which we refer to as the common bridge representation hypothesis.

[Arxiv](https://arxiv.org/abs/2408.09503)