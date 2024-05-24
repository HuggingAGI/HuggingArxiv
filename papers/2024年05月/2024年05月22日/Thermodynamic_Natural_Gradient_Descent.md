# 热力学自然梯度下降法

发布时间：2024年05月22日

`LLM理论

这篇论文主要探讨了自然梯度下降（NGD）这一二阶训练方法在大规模神经网络训练中的应用，特别是在硬件支持下的优化。论文提出了一种创新的混合数字-模拟算法，用于神经网络训练，这种方法在特定条件下等同于NGD，并且避免了传统线性系统求解的高成本。此外，该算法利用了平衡模拟系统的热力学特性，需要模拟热力学计算机来实现。论文通过数值实验展示了这种方法在分类和语言模型微调任务上的优越性能，超越了现有的数字一阶与二阶训练技术。因此，这篇论文的内容更偏向于大型语言模型（LLM）的理论研究，特别是在训练算法和硬件优化方面的深入探讨。` `人工智能` `机器学习`

> Thermodynamic Natural Gradient Descent

# 摘要

> 尽管二阶训练方法在收敛性上优于梯度下降，但因其计算负担，在大规模训练实践中鲜有应用。这实质上是硬件的限制。我们发现，通过合适的硬件支持，自然梯度下降（NGD）这一二阶方法的每次迭代计算复杂度可与一阶方法媲美。我们创新性地提出了一种混合数字-模拟算法，用于神经网络训练，它在特定参数条件下等同于NGD，同时巧妙规避了线性系统求解的高成本。该算法巧妙利用了平衡模拟系统的热力学特性，因此需要模拟热力学计算机。训练过程在混合数字-模拟循环中进行，期间模拟动态与梯度及费雪信息矩阵（或其他正半定曲率矩阵）的计算交替进行。数值实验表明，此方法在分类及语言模型微调任务上均超越了当前最优的数字一阶与二阶训练技术。

> Second-order training methods have better convergence properties than gradient descent but are rarely used in practice for large-scale training due to their computational overhead. This can be viewed as a hardware limitation (imposed by digital computers). Here we show that natural gradient descent (NGD), a second-order method, can have a similar computational complexity per iteration to a first-order method, when employing appropriate hardware. We present a new hybrid digital-analog algorithm for training neural networks that is equivalent to NGD in a certain parameter regime but avoids prohibitively costly linear system solves. Our algorithm exploits the thermodynamic properties of an analog system at equilibrium, and hence requires an analog thermodynamic computer. The training occurs in a hybrid digital-analog loop, where the gradient and Fisher information matrix (or any other positive semi-definite curvature matrix) are calculated at given time intervals while the analog dynamics take place. We numerically demonstrate the superiority of this approach over state-of-the-art digital first- and second-order training methods on classification tasks and language model fine-tuning tasks.

[Arxiv](https://arxiv.org/abs/2405.13817)