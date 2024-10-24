# 没有过度参数化的神经网络的损失景观特征

发布时间：2024年10月16日

`LLM理论` `机器学习`

> Loss Landscape Characterization of Neural Networks without Over-Parametrization

# 摘要

> 摘要：优化方法在现代机器学习中起着至关重要的作用，为深度学习模型的显著经验成就提供了动力。考虑到这些模型的损失情况的复杂非凸性质，这些成功更加引人注目。然而，确保优化方法的收敛需要目标函数的特定结构条件，而这些条件在实践中很少得到满足。一个突出的例子是近年来广受关注的 Polyak-Lojasiewicz（PL）不等式。然而，为深度神经网络验证此类假设需要大量且往往不切实际的过度参数化。为了解决这一限制，我们提出了一类新的函数，可以表征现代深度模型的损失情况，不需要大量的过度参数化，并且可以包括鞍点。至关重要的是，我们证明了在这个假设下基于梯度的优化器具有收敛的理论保证。最后，我们通过对各种深度学习模型的理论分析和实证实验验证了我们新函数类的合理性。

> 
Abstract:Optimization methods play a crucial role in modern machine learning, powering the remarkable empirical achievements of deep learning models. These successes are even more remarkable given the complex non-convex nature of the loss landscape of these models. Yet, ensuring the convergence of optimization methods requires specific structural conditions on the objective function that are rarely satisfied in practice. One prominent example is the widely recognized Polyak-Lojasiewicz (PL) inequality, which has gained considerable attention in recent years. However, validating such assumptions for deep neural networks entails substantial and often impractical levels of over-parametrization. In order to address this limitation, we propose a novel class of functions that can characterize the loss landscape of modern deep models without requiring extensive over-parametrization and can also include saddle points. Crucially, we prove that gradient-based optimizers possess theoretical guarantees of convergence under this assumption. Finally, we validate the soundness of our new function class through both theoretical analysis and empirical experimentation across a diverse range of deep learning models.
    

[Arxiv](https://arxiv.org/pdf/2410.12455)