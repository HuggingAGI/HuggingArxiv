# 语言模型里对虚构知识的学习与忘却

发布时间：2024年10月29日

`LLM应用` `语言模型` `数据训练`

> Learning and Unlearning of Fabricated Knowledge in Language Models

# 摘要

> 当新的知识片段被引入训练数据时会怎样？在大型语言模型（LM）持续训练期间，它又能存续多久？我们借助从新的探测数据集“Outlandish”向 LMs 注入事实来探究此问题，该数据集旨在对各种不同的事实类型进行测试。研究这些记忆的稳固性时发现，在与世界知识相符和完全随机之间的事实新颖性范畴中，存在一个最佳点，于此注入的记忆最为持久。具体而言，与常识冲突的事实能在数万次训练步骤中被记住，而不与常识冲突的提示（平常的）以及混乱的提示（随机打乱的）都遗忘得更快。另外，与知识冲突的事实能够“引发”语言模型在逻辑上不相关的提示上产生幻觉，展现出其非目标泛化的倾向，而平常和随机打乱的事实引发的程度则小得多。最后，我们表明，尽管语言模型中与知识冲突的事实的影响可能持久，但通过新应用多步稀疏更新，能在很大程度上消除这些影响，同时还能保留模型的训练能力。所以，这个极其简单的流程对减轻训练中的数据中毒影响具有直接意义。

> What happens when a new piece of knowledge is introduced into the training data and how long does it last while a large language model (LM) continues to train? We investigate this question by injecting facts into LMs from a new probing dataset, "Outlandish", which is designed to permit the testing of a spectrum of different fact types. When studying how robust these memories are, there appears to be a sweet spot in the spectrum of fact novelty between consistency with world knowledge and total randomness, where the injected memory is the most enduring. Specifically we show that facts that conflict with common knowledge are remembered for tens of thousands of training steps, while prompts not conflicting with common knowledge (mundane), as well as scrambled prompts (randomly jumbled) are both forgotten much more rapidly. Further, knowledge-conflicting facts can "prime'' how the language model hallucinates on logically unrelated prompts, showing their propensity for non-target generalization, while both mundane and randomly jumbled facts prime significantly less. Finally, we show that impacts of knowledge-conflicting facts in LMs, though they can be long lasting, can be largely erased by novel application of multi-step sparse updates, even while the training ability of the model is preserved. As such, this very simple procedure has direct implications for mitigating the effects of data poisoning in training.

[Arxiv](https://arxiv.org/abs/2410.21750)