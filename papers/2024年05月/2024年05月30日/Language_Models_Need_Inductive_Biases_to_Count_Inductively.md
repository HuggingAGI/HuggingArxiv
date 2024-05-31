# 语言模型若要进行归纳计数，需依赖归纳偏置。

发布时间：2024年05月30日

`LLM理论

这篇论文主要探讨了不同类型的语言模型（从RNN到Transformer）在计数任务上的表现和泛化能力，特别是在处理未知领域（OOD）实例时的能力。论文通过实验研究了这些模型的计数训练方法，并分析了位置嵌入等技术对模型性能的影响。由于论文的核心内容是关于语言模型（LLM）的理论和性能分析，特别是关于计数和泛化能力的理论探讨，因此将其归类为LLM理论。` `认知科学`

> Language Models Need Inductive Biases to Count Inductively

# 摘要

> 计数，作为泛化的基本示例，无论是在数学的Peano公理中定义自然数，还是在认知科学中探讨儿童如何学习计数，都揭示了一个共同点：学习计数即学习无限计数。尽管关于变压器“推理”的简化研究中很少涉及计数，但长度泛化的研究在文献中广泛存在。在NLP领域，“训练短，测试长”的模式下，长度指的是训练句子的长度；而在形式语言识别中，它指的是输入序列的长度或下推自动机引起的最大堆栈大小。在一般问题解决中，长度则关联到演绎推理链的跳数或递归深度。在这些情境中，计数是任务成功的关键。更重要的是，归纳计数的泛化能力是处理未知领域（OOD）实例的关键。本研究通过广泛的实验，探讨了从RNN到Transformer等多种架构的语言模型如何进行计数训练。我们设计了精心的任务格式、辅助任务和位置嵌入，以克服OOD位置和OOD词汇表带来的泛化限制。实验结果显示，传统RNN能轻松实现归纳计数，而Transformer则需依赖位置嵌入来处理域外计数。鉴于计数是评估Transformer表达性的基础，我们的发现促使社区重新考虑形式表征中基本函数的应用范围。此外，现代RNN在归纳计数的泛化上也明显不如传统RNN，这提示我们需重新审视并行化训练设计对RNN循环性质的影响。

> Counting is a fundamental example of generalization, whether viewed through the mathematical lens of Peano's axioms defining the natural numbers or the cognitive science literature for children learning to count. The argument holds for both cases that learning to count means learning to count infinitely. While few papers have tried to distill transformer "reasoning" to the simplest case of counting, investigating length generalization does occur throughout the literature. In the "train short, test long" paradigm of NLP, length refers to the training sentence length. In formal language recognition, length refers to the input sequence length, or the maximum stack size induced by a pushdown automata. In general problem solving, length refers to the number of hops in a deductive reasoning chain or the recursion depth. For all cases, counting is central to task success. And crucially, generalizing counting inductively is central to success on OOD instances. This work provides extensive empirical results on training language models to count. We experiment with architectures ranging from RNNs, Transformers, State-Space Models and RWKV. We present carefully-designed task formats, auxiliary tasks and positional embeddings to avoid limitations in generalization with OOD-position and OOD-vocabulary. We find that while traditional RNNs trivially achieve inductive counting, Transformers have to rely on positional embeddings to count out-of-domain. As counting is the basis for many arguments concerning the expressivity of Transformers, our finding calls for the community to reexamine the application scope of primitive functions defined in formal characterizations. Finally, modern RNNs also largely underperform traditional RNNs in generalizing counting inductively. We discuss how design choices that enable parallelized training of modern RNNs cause them to lose merits of a recurrent nature.

[Arxiv](https://arxiv.org/abs/2405.20131)