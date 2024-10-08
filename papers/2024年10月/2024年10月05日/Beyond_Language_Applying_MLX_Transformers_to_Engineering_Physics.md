# 超越语言界限：探索 MLX Transformers 在工程物理领域的应用

发布时间：2024年10月05日

`LLM应用` `工程物理` `热传导`

> Beyond Language: Applying MLX Transformers to Engineering Physics

# 摘要

> Transformer 神经网络正在 LLM 领域掀起热潮，但在工程物理学中的应用却寥寥无几。为此，我们推出了一款专为物理学设计的 Transformer 模型，用于解决二维板的热传导问题，并设定了 Dirichlet 边界条件。该模型基于 MLX 框架，并充分利用了 Apple M 系列处理器的统一内存，使得模型在个人电脑上也能高效运行。我们通过中心有限差分法来训练、验证和测试模型，每个解都随机初始化边界条件和内部温度分布。训练过程中实时验证，防止过拟合。最终，模型在未见过的测试条件下，成功预测了温度场向稳态的演变，表现出色。

> Transformer Neural Networks are driving an explosion of activity and discovery in the field of Large Language Models (LLMs). In contrast, there have been only a few attempts to apply Transformers in engineering physics. Aiming to offer an easy entry point to physics-centric Transformers, we introduce a physics-informed Transformer model for solving the heat conduction problem in a 2D plate with Dirichlet boundary conditions. The model is implemented in the machine learning framework MLX and leverages the unified memory of Apple M-series processors. The use of MLX means that the models can be trained and perform predictions efficiently on personal machines with only modest memory requirements. To train, validate and test the Transformer model we solve the 2D heat conduction problem using central finite differences. Each finite difference solution in these sets is initialized with four random Dirichlet boundary conditions, a uniform but random internal temperature distribution and a randomly selected thermal diffusivity. Validation is performed in-line during training to monitor against over-fitting. The excellent performance of the trained model is demonstrated by predicting the evolution of the temperature field to steady state for the unseen test set of conditions.

[Arxiv](https://arxiv.org/abs/2410.04167)