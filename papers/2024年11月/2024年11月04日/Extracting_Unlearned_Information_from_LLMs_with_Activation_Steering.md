# 通过激活引导从大型语言模型中提取未学习的信息

发布时间：2024年11月04日

`LLM应用` `信息安全` `机器学习`

> Extracting Unlearned Information from LLMs with Activation Steering

# 摘要

> 大型语言模型（LLMs）的大量预训练的一个意外后果是对其训练数据片段的逐字记忆，这些数据可能包含敏感或受版权保护的信息。近年来，遗忘学习已成为一种解决方案，用于在训练后有效地从模型中删除敏感知识。然而，最近的工作表明，恶意行为者仍可以通过各种攻击提取本应删除的信息。不过，当前的攻击检索的是可能的候选生成集，无法准确指出包含实际目标信息的输出。我们提出激活引导作为从未学习的 LLMs 中精确检索信息的方法。我们引入了一种生成引导向量的新方法，称为匿名激活引导。此外，我们开发了一种简单的词频方法，用于在检索未学习的信息时从一组候选中准确指出正确答案。我们在多种遗忘学习技术和数据集上的评估表明，激活引导成功恢复了一般知识（例如，广为人知的虚构人物），同时揭示了在检索特定信息（例如，关于非公开个人的详细信息）方面的局限性。总的来说，我们的结果表明从未学习的模型中精确检索信息是可能的，突出了当前遗忘学习技术的严重漏洞。

> An unintended consequence of the vast pretraining of Large Language Models (LLMs) is the verbatim memorization of fragments of their training data, which may contain sensitive or copyrighted information. In recent years, unlearning has emerged as a solution to effectively remove sensitive knowledge from models after training. Yet, recent work has shown that supposedly deleted information can still be extracted by malicious actors through various attacks. Still, current attacks retrieve sets of possible candidate generations and are unable to pinpoint the output that contains the actual target information. We propose activation steering as a method for exact information retrieval from unlearned LLMs. We introduce a novel approach to generating steering vectors, named Anonymized Activation Steering. Additionally, we develop a simple word frequency method to pinpoint the correct answer among a set of candidates when retrieving unlearned information. Our evaluation across multiple unlearning techniques and datasets demonstrates that activation steering successfully recovers general knowledge (e.g., widely known fictional characters) while revealing limitations in retrieving specific information (e.g., details about non-public individuals). Overall, our results demonstrate that exact information retrieval from unlearned models is possible, highlighting a severe vulnerability of current unlearning techniques.

[Arxiv](https://arxiv.org/abs/2411.02631)