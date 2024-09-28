# 通过对比语言模型的注意力，我们能更有效地捕捉知识学习中的微妙线索。

发布时间：2024年09月26日

`LLM理论` `人工智能`

> Enhancing elusive clues in knowledge learning by contrasting attention of language models

# 摘要

> 因果语言模型在预训练中从通用文本中汲取大量知识，但知识学习的效率不尽如人意，尤其是在处理知识密集且规模较小的语料库时。这一问题源于语言模型难以捕捉的长距离依赖，以及对训练文本中共现模式和干扰线索的过度拟合。为此，本文提出一种方法，通过增强语言模型自身发现的文本中那些微妙但关键的线索，来提升预训练中的知识学习效率。研究发现，大型语言模型更关注那些常被忽视的重要线索。通过对比大小模型的注意力权重，我们能识别这些线索，并以此指导训练文本的token-dropout数据增强，从而显著提升大小模型的事实记忆能力。这表明，表现优劣不同的语言模型行为对比中蕴含着知识学习的关键线索，通过“放大”这些线索，可直接提升知识学习效率。

> Causal language models acquire vast amount of knowledge from general text corpus during pretraining, but the efficiency of knowledge learning is known to be unsatisfactory, especially when learning from knowledge-dense and small-sized corpora. The deficiency can come from long-distance dependencies which are hard to capture by language models, and overfitting to co-occurrence patterns and distracting clues in the training text. To address these issues, the paper proposes a method to enhance knowledge learning during language model pretraining, by enhancing elusive but important clues in text discovered by the language model themselves. We found that larger language models pay more attention to non-obvious but important clues, which are often overlooked by smaller language models. Therefore, we can identify these clues by contrasting the attention weights of large and small language models. We use the identified clues as a guide to perform token-dropout data augmentation on the training text, and observed a significant boost in both small and large models' performance in fact memorization. This shows that the behavior contrast between more and less-performant language models contains important clues for knowledge learning, and it can be ``amplified" for a straight-forward improvement in knowledge learning efficiency.

[Arxiv](https://arxiv.org/abs/2409.17954)