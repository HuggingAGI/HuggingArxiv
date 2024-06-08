# Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。

发布时间：2024年06月06日

`LLM理论

这篇论文主要探讨了仅解码器的Transformer模型中的信息传播机制，这是大型语言模型（LLMs）的核心架构。通过理论分析，研究了Transformer模型在特定输入序列下的表现，并发现了模型在处理某些序列时的局限性。这些发现涉及到模型的理论性能和潜在的改进方法，因此属于LLM理论分类。` `机器学习`

> Transformers need glasses! Information over-squashing in language tasks

# 摘要

> 我们探讨了信息在仅解码器的Transformer模型中的传播机制，这类模型是众多前沿大型语言模型（LLMs）的核心架构。通过理论信号传播分析，我们特别关注了Transformer最后一层最后一个token的表示，这是用于预测下一个token的关键。研究发现，某些输入序列会导致最后一个token的表示极度接近，这种现象在采用低精度浮点格式的现代LLMs中尤为明显。这使得模型在处理这些序列时无法做出区分，从而在计数或复制等任务中产生错误。此外，我们还发现这些模型可能对输入中的特定token失去敏感性，这与图神经网络中的过度压缩现象相似。我们通过实证研究验证了这些发现，并提出了改善这些问题的简单方法。

> We study how information propagates in decoder-only Transformers, which are the architectural backbone of most existing frontier large language models (LLMs). We rely on a theoretical signal propagation analysis -- specifically, we analyse the representations of the last token in the final layer of the Transformer, as this is the representation used for next-token prediction. Our analysis reveals a representational collapse phenomenon: we prove that certain distinct sequences of inputs to the Transformer can yield arbitrarily close representations in the final token. This effect is exacerbated by the low-precision floating-point formats frequently used in modern LLMs. As a result, the model is provably unable to respond to these sequences in different ways -- leading to errors in, e.g., tasks involving counting or copying. Further, we show that decoder-only Transformer language models can lose sensitivity to specific tokens in the input, which relates to the well-known phenomenon of over-squashing in graph neural networks. We provide empirical evidence supporting our claims on contemporary LLMs. Our theory also points to simple solutions towards ameliorating these issues.

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/x1.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/x2.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/fig2.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/counting-experiments-geminipro15-errors.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/frequency-histogram-geminipro15.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/counting-ones-seq-ones.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/counting-ones-seq-digits.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/copying-ones-seq.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/copying-ones-seq-digits-commas.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/counting-experiments-gemma7b-errors.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/frequency-histogram-gemma7b.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/sinusoidal-convergence.png)

![Transformer 模型或许需要一副“眼镜”，以应对语言任务中信息过度压缩的挑战。](../../../paper_images/2406.04267/decay-of-total-variation.png)

[Arxiv](https://arxiv.org/abs/2406.04267)