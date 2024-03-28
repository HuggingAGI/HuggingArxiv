# 为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。

发布时间：2024年03月21日

`Agent` `计算机视觉` `机器学习`

> Regularized Adaptive Momentum Dual Averaging with an Efficient Inexact Subproblem Solver for Training Structured Neural Network

# 摘要

> 我们创新性地提出了RAMDA算法，专为训练结构化的神经网络设计。类似已有的正则化自适应方法，RAMDA在计算更新方向时同样面临含有非光滑正则项和对角预条件器的子问题，导致无法得到一般的闭合形式解。为此，我们巧妙地制定了一种保有类似精确解版本收敛性的可实施不精确性条件，并为RAMDA及现有方法的子问题配套研发了一款高效求解器，使之在实践中得以应用。通过运用变分分析中的流形识别理论，我们揭示即使存在不精确性，RAMDA在渐进收敛的稳定点处也能捕获由正则项塑造的理想结构特征，而这一结构在收敛区域是局部最优的。这意味着RAMDA能够在所有指向相同收敛点的方法中确保找到最佳结构模型，从而成为首个兼具卓越预测性能与（局部）最优结构特性的正则化自适应方法。大量现代大规模计算机视觉、语言模型和语音任务的实验证明了RAMDA的有效性和优越性，其性能持续超越当前训练结构化神经网络的顶尖水平。您可以在http://www.github.com/ismoptgroup/RAMDA/访问我们算法的具体实现。

> We propose a Regularized Adaptive Momentum Dual Averaging (RAMDA) algorithm for training structured neural networks. Similar to existing regularized adaptive methods, the subproblem for computing the update direction of RAMDA involves a nonsmooth regularizer and a diagonal preconditioner, and therefore does not possess a closed-form solution in general. We thus also carefully devise an implementable inexactness condition that retains convergence guarantees similar to the exact versions, and propose a companion efficient solver for the subproblems of both RAMDA and existing methods to make them practically feasible. We leverage the theory of manifold identification in variational analysis to show that, even in the presence of such inexactness, the iterates of RAMDA attain the ideal structure induced by the regularizer at the stationary point of asymptotic convergence. This structure is locally optimal near the point of convergence, so RAMDA is guaranteed to obtain the best structure possible among all methods converging to the same point, making it the first regularized adaptive method outputting models that possess outstanding predictive performance while being (locally) optimally structured. Extensive numerical experiments in large-scale modern computer vision, language modeling, and speech tasks show that the proposed RAMDA is efficient and consistently outperforms state of the art for training structured neural network. Implementation of our algorithm is available at http://www.github.com/ismoptgroup/RAMDA/.

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/ResNet50_on_ImageNet_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/Transformer-XL_on_WikiText-103_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/Tacotron2_on_LJSpeech_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/Lin_on_MNIST_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/VGG19_on_CIFAR10_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/VGG19_on_CIFAR100_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/ResNet50_on_CIFAR10_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/ResNet50_on_CIFAR100_All)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/ResNet50_on_ImageNet_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/Transformer-XL_on_WikiText-103_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/Tacotron2_on_LJSpeech_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/Lin_on_MNIST_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/VGG19_on_CIFAR10_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/VGG19_on_CIFAR100_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/ResNet50_on_CIFAR10_Sparsity)

![为优化结构化神经网络训练，我们提出了一种正则化的自适应动量双重平均算法，并配备了高效解决近似子问题的求解器。](../../../paper_images/2403.14398/ResNet50_on_CIFAR100_Sparsity)

[Arxiv](https://arxiv.org/abs/2403.14398)