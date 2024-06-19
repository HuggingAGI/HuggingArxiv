# 迈向模拟内存计算中的精确梯度训练之路

发布时间：2024年06月18日

`LLM理论

这篇论文主要探讨了在模拟设备上进行梯度训练的理论基础，特别是在非理想设备上使用随机梯度下降（SGD）算法进行模型训练时遇到的问题。论文通过分析SGD在模拟设备上的非收敛问题，并提出了名为Tiki-Taka的启发式模拟算法来解决这些问题。这些内容主要涉及大型语言模型（LLM）的理论层面，特别是在模拟设备上的训练方法和算法的改进，因此归类为LLM理论。` `人工智能` `节能技术`

> Towards Exact Gradient-based Training on Analog In-memory Computing

# 摘要

> 考虑到大型视觉或语言模型的高昂经济和环境成本，模拟内存加速器成为节能AI的有力候选。尽管模拟加速器上的推理研究已有所进展，但其训练机制仍鲜为人知。最近发现，数字AI训练的主力军——随机梯度下降（SGD）算法，在非理想设备上的模型训练中无法精确收敛。本文为模拟设备上的梯度训练奠定了理论基础。首先，我们揭示了SGD在模拟设备上因不对称更新而导致的非收敛问题。接着，我们通过渐近误差的下界，揭示了SGD基模拟训练的固有性能限制。为克服这一难题，我们探讨了名为Tiki-Taka的启发式模拟算法，该算法近期在实践中表现优于SGD，并证明了其能够精确收敛至临界点，从而消除了渐近误差。模拟实验验证了我们的分析。

> Given the high economic and environmental costs of using large vision or language models, analog in-memory accelerators present a promising solution for energy-efficient AI. While inference on analog accelerators has been studied recently, the training perspective is underexplored. Recent studies have shown that the "workhorse" of digital AI training - stochastic gradient descent (SGD) algorithm converges inexactly when applied to model training on non-ideal devices. This paper puts forth a theoretical foundation for gradient-based training on analog devices. We begin by characterizing the non-convergent issue of SGD, which is caused by the asymmetric updates on the analog devices. We then provide a lower bound of the asymptotic error to show that there is a fundamental performance limit of SGD-based analog training rather than an artifact of our analysis. To address this issue, we study a heuristic analog algorithm called Tiki-Taka that has recently exhibited superior empirical performance compared to SGD and rigorously show its ability to exactly converge to a critical point and hence eliminates the asymptotic error. The simulations verify the correctness of the analyses.

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x1.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x2.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x3.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x4.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x5.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x6.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x7.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x8.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x9.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x10.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x11.png)

![迈向模拟内存计算中的精确梯度训练之路](../../../paper_images/2406.12774/x12.png)

[Arxiv](https://arxiv.org/abs/2406.12774)