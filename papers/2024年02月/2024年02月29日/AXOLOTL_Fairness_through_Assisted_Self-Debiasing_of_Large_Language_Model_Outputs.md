# [AXOLOTL项目致力于借助协助大型语言模型进行自我去偏，从而在输出中实现公平性。它聚焦于通过自我校正手段减轻大型语言模型潜在的偏见问题。](https://arxiv.org/abs/2403.00198)

> AXOLOTL: Fairness through Assisted Self-Debiasing of Large Language Model Outputs

发布时间：2024年02月29日

> 预训练的LLMs虽然大大提升了NLP能力，却容易受到训练数据中偏见的影响，导致各类应用产生不公平结果。现有的一些解决偏见的方法虽多，但常常需要大量计算资源且可能牺牲模型表现。为此，我们创新性地提出了AXOLOTL这一通用后处理框架，它不依赖具体任务和模型细节，借助公共API与LLMs互动，无需直接触及内部参数。AXOLOTL运用类似零样本学习的三步法，高效识别偏见、提议修正方案，并引导模型自我校正输出偏见，同时最大程度地节约计算资源且保留原有性能水平。这一方法使得AXOLOTL成为一个广泛应用前景广阔、便捷易用的LLM输出去偏利器。

> Pre-trained Large Language Models (LLMs) have significantly advanced natural language processing capabilities but are susceptible to biases present in their training data, leading to unfair outcomes in various applications. While numerous strategies have been proposed to mitigate bias, they often require extensive computational resources and may compromise model performance. In this work, we introduce AXOLOTL, a novel post-processing framework, which operates agnostically across tasks and models, leveraging public APIs to interact with LLMs without direct access to internal parameters. Through a three-step process resembling zero-shot learning, AXOLOTL identifies biases, proposes resolutions, and guides the model to self-debias its outputs. This approach minimizes computational costs and preserves model performance, making AXOLOTL a promising tool for debiasing LLM outputs with broad applicability and ease of use.

`LLM应用`