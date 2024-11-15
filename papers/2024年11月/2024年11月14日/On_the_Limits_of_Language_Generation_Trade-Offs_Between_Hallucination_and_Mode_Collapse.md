# 论语言生成的局限性：幻觉与模式崩溃之间的权衡

发布时间：2024年11月14日

`LLM理论` `语言模型`

> On the Limits of Language Generation: Trade-Offs Between Hallucination and Mode Collapse

# 摘要

> 指定语言模型的所有理想特性颇具难度，但有些要求显然至关重要。给定来自未知语言的样本，训练后的模型应当生成训练中未出现过的有效字符串，且要有足够的表现力来涵盖该语言的丰富内涵。否则，输出无效字符串就构成了“幻觉”，而无法涵盖全部范围则会导致“模式崩溃”。我们来探讨语言模型能否满足这两项要求。

我们在基于 Gold 和 Angluin 的统计语言生成情境中展开研究。在此，模型从可能无限的语言集合中未知的语言 K 的分布接收随机样本，目标是从 K 生成未曾见过的字符串。若随着训练规模增大，其输出收敛至 K 中的所有未见过的字符串，我们就说该模型从 K 生成具有一致性和广度。

Kleinberg 和 Mullainathan [KM24]曾询问语言生成中的一致性和广度是否可行。我们给出否定答案：对于包括下一个标记预测模型在内的众多语言模型，对于大多数候选语言集合而言这都不可行。这与 [KM24] 的结果形成对照，表明对于任何可数的语言集合，没有广度的一致生成是能够实现的。我们的发现凸显出具有广度的生成与没有广度的生成存在根本差异。

作为附带成果，我们为有或没有广度的生成所需的样本数量确立了近乎严格的界限。

最后，我们的结果带来了希望：当负例（K 之外的字符串）与正例一同存在时，对于任何可数的语言集合，实现具有广度的一致生成是可行的。这表明编码负例的训练后反馈对于减少幻觉并限制模式崩溃可能极为关键。

> Specifying all desirable properties of a language model is challenging, but certain requirements seem essential. Given samples from an unknown language, the trained model should produce valid strings not seen in training and be expressive enough to capture the language's full richness. Otherwise, outputting invalid strings constitutes "hallucination," and failing to capture the full range leads to "mode collapse." We ask if a language model can meet both requirements.
  We investigate this within a statistical language generation setting building on Gold and Angluin. Here, the model receives random samples from a distribution over an unknown language K, which belongs to a possibly infinite collection of languages. The goal is to generate unseen strings from K. We say the model generates from K with consistency and breadth if, as training size increases, its output converges to all unseen strings in K.
  Kleinberg and Mullainathan [KM24] asked if consistency and breadth in language generation are possible. We answer this negatively: for a large class of language models, including next-token prediction models, this is impossible for most collections of candidate languages. This contrasts with [KM24]'s result, showing consistent generation without breadth is possible for any countable collection of languages. Our finding highlights that generation with breadth fundamentally differs from generation without breadth.
  As a byproduct, we establish near-tight bounds on the number of samples needed for generation with or without breadth.
  Finally, our results offer hope: consistent generation with breadth is achievable for any countable collection of languages when negative examples (strings outside K) are available alongside positive ones. This suggests that post-training feedback, which encodes negative examples, can be crucial in reducing hallucinations while limiting mode collapse.

[Arxiv](https://arxiv.org/abs/2411.09642)