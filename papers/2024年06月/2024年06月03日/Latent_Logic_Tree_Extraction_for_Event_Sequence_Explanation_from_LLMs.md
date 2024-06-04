# 从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑

发布时间：2024年06月03日

`Agent

理由：这篇论文主要描述了一个基于大型语言模型（LLMs）的工具，该工具能够生成基于逻辑树的解释，为高风险系统中的事件序列提供定制化洞察。这个工具通过使用LLMs的先验知识和事件序列的似然性来评估逻辑树的后验分布，并利用GFlowNet生成逻辑树样本。这个过程涉及到对事件序列的实时处理和适应性调整，这表明该工具具有一定的自主性和适应性，类似于一个智能Agent的行为。因此，将其归类为Agent是合适的。` `医疗保健` `机器人`

> Latent Logic Tree Extraction for Event Sequence Explanation from LLMs

# 摘要

> 在医疗保健或机器人等高风险系统中，大量的事件序列不断涌现。我们旨在开发一种高效且即插即用的工具，利用大型语言模型（LLMs）生成基于逻辑树的解释，为每个事件序列提供定制化洞察。基于时间点过程模型，我们的方法通过似然函数评估逻辑树的质量。我们提出了一种摊销期望最大化（EM）学习框架，将逻辑树作为潜在变量处理。在E步骤中，我们利用LLM的先验知识和事件序列的似然性来评估逻辑树的后验分布。尽管LLM提供了高质量的先验，但后验分布的离散组合性质使得无法获得封闭解。因此，我们采用可学习的GFlowNet生成逻辑树样本，这是一种专为结构化离散变量设计的多样性寻求生成器。在M步骤中，通过生成的逻辑规则近似后验边缘化，优化模型参数和LLM先验参数。在线环境中，我们的轻量级模型将通过几次迭代，从LLMs中提取每个序列的关键规则。实证结果表明，我们的框架具有出色的性能和适应性。

> Modern high-stakes systems, such as healthcare or robotics, often generate vast streaming event sequences. Our goal is to design an efficient, plug-and-play tool to elicit logic tree-based explanations from Large Language Models (LLMs) to provide customized insights into each observed event sequence. Built on the temporal point process model for events, our method employs the likelihood function as a score to evaluate generated logic trees. We propose an amortized Expectation-Maximization (EM) learning framework and treat the logic tree as latent variables. In the E-step, we evaluate the posterior distribution over the latent logic trees using an LLM prior and the likelihood of the observed event sequences. LLM provides a high-quality prior for the latent logic trees, however, since the posterior is built over a discrete combinatorial space, we cannot get the closed-form solution. We propose to generate logic tree samples from the posterior using a learnable GFlowNet, which is a diversity-seeking generator for structured discrete variables. The M-step employs the generated logic rules to approximate marginalization over the posterior, facilitating the learning of model parameters and refining the tunable LLM prior parameters. In the online setting, our locally built, lightweight model will iteratively extract the most relevant rules from LLMs for each sequence using only a few iterations. Empirical demonstrations showcase the promising performance and adaptability of our framework.

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x1.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x2.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x3.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x4.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x5.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x6.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x7.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x8.png)

![从大型语言模型中提取潜在逻辑树，揭示事件序列的内在逻辑](../../../paper_images/2406.01124/x9.png)

[Arxiv](https://arxiv.org/abs/2406.01124)