# 用 Koopman 理论解释时间图神经网络

发布时间：2024年10月17日

`其他` `流行病学` `时空图神经网络`

> Interpreting Temporal Graph Neural Networks with Koopman Theory

# 摘要

> 摘要：时空图神经网络（STGNNs）在从预测到流行病学的许多领域都显示出了有希望的结果。然而，理解这些模型所学习的动态以及解释它们的行为比处理静态数据的模型要复杂得多。受 Koopman 理论的启发，该理论允许对复杂的非线性动力系统进行更简单的描述，我们为时间图引入了一种可解释性方法。我们提出了两种方法来解释 STGNN 的决策过程，并确定手头任务输入中最相关的空间和时间模式。第一种方法依赖于动态模式分解（DMD），这是一种受 Koopman 启发的降维方法。第二种方法依赖于非线性动力学的稀疏识别（SINDy），这是一种发现控制方程的流行方法，我们首次将其用作一般的可解释性工具。我们展示了我们的方法如何在传播过程的背景下正确识别可解释的特征，如感染时间和受感染的节点。

> 
Abstract:Spatiotemporal graph neural networks (STGNNs) have shown promising results in many domains, from forecasting to epidemiology. However, understanding the dynamics learned by these models and explaining their behaviour is significantly more complex than for models dealing with static data. Inspired by Koopman theory, which allows a simpler description of intricate, nonlinear dynamical systems, we introduce an explainability approach for temporal graphs. We present two methods to interpret the STGNN's decision process and identify the most relevant spatial and temporal patterns in the input for the task at hand. The first relies on dynamic mode decomposition (DMD), a Koopman-inspired dimensionality reduction method. The second relies on sparse identification of nonlinear dynamics (SINDy), a popular method for discovering governing equations, which we use for the first time as a general tool for explainability. We show how our methods can correctly identify interpretable features such as infection times and infected nodes in the context of dissemination processes.
    

[Arxiv](https://arxiv.org/pdf/2410.13469)