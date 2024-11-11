# Interaction2Code：我们距离自动交互式网页生成还有多远？

发布时间：2024年11月05日

`LLM应用` `网页开发` `交互设计`

> Interaction2Code: How Far Are We From Automatic Interactive Webpage Generation?

# 摘要

> 将网页设计转换为功能性的用户界面（UI）代码是构建网站的关键步骤，这可能是劳动密集型和耗时的。为了使这个设计到代码的转换过程自动化，已经提出了使用基于学习的网络和多模态大型语言模型（MLLMs）的各种自动化方法。然而，这些研究仅仅在狭窄范围的静态网页上进行了评估，并忽略了动态交互元素，使得它们在现实世界的网站部署中不太实用。

为了填补空白，我们对 MLLMs 在生成交互式网页方面进行了首次系统研究。具体来说，我们首先制定了交互到代码任务，并构建了包含 97 个独特网页和 213 种不同交互的 Interaction2Code 基准，涵盖 15 种网页类型和 30 个交互类别。然后，我们使用自动指标和人工评估对三个最先进的（SOTA）MLLMs 进行了全面实验，从而相应地总结了六个发现。我们的实验结果突出了 MLLMs 在生成细粒度交互特征以及处理具有复杂变换和微妙视觉修改的交互方面的局限性。我们进一步分析了失败案例及其根本原因，确定了 10 种常见的失败类型并评估了它们的严重程度。此外，我们的发现揭示了三个关键的影响因素，即提示、视觉显著性和文本描述，它们可以提高 MLLMs 的交互生成性能。基于这些发现，我们为研究人员和开发人员得出了启示，为该领域的未来发展提供了基础。数据集和源代码可在 https://github.com/WebPAI/Interaction2Code 获得。

> Converting webpage design into functional UI code is a critical step for building websites, which can be labor-intensive and time-consuming. To automate this design-to-code transformation process, various automated methods using learning-based networks and multi-modal large language models (MLLMs) have been proposed. However, these studies were merely evaluated on a narrow range of static web pages and ignored dynamic interaction elements, making them less practical for real-world website deployment.
  To fill in the blank, we present the first systematic investigation of MLLMs in generating interactive webpages. Specifically, we first formulate the Interaction-to-Code task and build the Interaction2Code benchmark that contains 97 unique web pages and 213 distinct interactions, spanning 15 webpage types and 30 interaction categories. We then conduct comprehensive experiments on three state-of-the-art (SOTA) MLLMs using both automatic metrics and human evaluations, thereby summarizing six findings accordingly. Our experimental results highlight the limitations of MLLMs in generating fine-grained interactive features and managing interactions with complex transformations and subtle visual modifications. We further analyze failure cases and their underlying causes, identifying 10 common failure types and assessing their severity. Additionally, our findings reveal three critical influencing factors, i.e., prompts, visual saliency, and textual descriptions, that can enhance the interaction generation performance of MLLMs. Based on these findings, we elicit implications for researchers and developers, providing a foundation for future advancements in this field. Datasets and source code are available at https://github.com/WebPAI/Interaction2Code.

[Arxiv](https://arxiv.org/abs/2411.03292)