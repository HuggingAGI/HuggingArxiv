# 探索程序向神经网络的编译学习之道

发布时间：2024年07月21日

`LLM应用` `软件开发` `人工智能`

> Learning to Compile Programs to Neural Networks

# 摘要

> 我们提出了一种新技术——$\textit{神经替代品编译}$，它能够直接从程序文本生成神经网络替代品，无需将生成和执行过程绑定。通过在C程序数据集上训练的超网络实现的编译器，我们发现这些替代品在数据效率上提升了$1.9$至$9.5$倍，生成的视觉结果更接近真实情况$1.0$至$1.3$倍，且训练周期缩短了$4.3$至$7.3$倍。这一创新方法有效解决了资源消耗与准确性之间的权衡问题。

> A $\textit{neural surrogate of a program}$ is a neural network that mimics the behavior of a program. Researchers have used these neural surrogates to automatically tune program inputs, adapt programs to new settings, and accelerate computations. Researchers traditionally develop neural surrogates by training on input-output examples from a single program. Alternatively, language models trained on a large dataset including many programs can consume program text, to act as a neural surrogate. Using a language model to both generate a surrogate and act as a surrogate, however, leading to a trade-off between resource consumption and accuracy. We present $\textit{neural surrogate compilation}$, a technique for producing neural surrogates directly from program text without coupling neural surrogate generation and execution. We implement neural surrogate compilers using hypernetworks trained on a dataset of C programs and find that they produce neural surrogates that are $1.9$-$9.5\times$ as data-efficient, produce visual results that are $1.0$-$1.3\times$ more similar to ground truth, and train in $4.3$-$7.3\times$ fewer epochs than neural surrogates trained from scratch.

[Arxiv](https://arxiv.org/abs/2407.15078)