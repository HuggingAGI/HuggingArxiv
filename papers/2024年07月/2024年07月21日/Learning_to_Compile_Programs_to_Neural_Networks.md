# 探索程序到神经网络的编译学习

发布时间：2024年07月21日

`Agent` `计算机科学` `人工智能`

> Learning to Compile Programs to Neural Networks

# 摘要

> 我们提出了一种名为$\textit{神经代理编译}$的新技术，它能够直接从程序文本生成神经代理，无需将生成和执行过程绑定。通过在C程序数据集上训练的超网络实现的神经代理编译器，我们发现这些代理在数据效率上提升了1.9至9.5倍，生成的视觉结果与真实情况更为接近，提高了1.0至1.3倍，且训练周期缩短了4.3至7.3倍，相较于传统从头开始训练的神经代理。这一创新方法不仅优化了资源消耗与准确性之间的平衡，还显著提升了神经代理的性能和效率。

> A $\textit{neural surrogate of a program}$ is a neural network that mimics the behavior of a program. Researchers have used these neural surrogates to automatically tune program inputs, adapt programs to new settings, and accelerate computations. Researchers traditionally develop neural surrogates by training on input-output examples from a single program. Alternatively, language models trained on a large dataset including many programs can consume program text, to act as a neural surrogate. Using a language model to both generate a surrogate and act as a surrogate, however, leading to a trade-off between resource consumption and accuracy. We present $\textit{neural surrogate compilation}$, a technique for producing neural surrogates directly from program text without coupling neural surrogate generation and execution. We implement neural surrogate compilers using hypernetworks trained on a dataset of C programs and find that they produce neural surrogates that are $1.9$-$9.5\times$ as data-efficient, produce visual results that are $1.0$-$1.3\times$ more similar to ground truth, and train in $4.3$-$7.3\times$ fewer epochs than neural surrogates trained from scratch.

[Arxiv](https://arxiv.org/abs/2407.15078)