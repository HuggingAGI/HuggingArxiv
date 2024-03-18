# [Generator：一种“循环中树”文本生成技术，旨在提升语言模型的可解释性及适应能力](https://arxiv.org/abs/2403.07627)

发布时间：2024年03月12日

`LLM应用`

> generAItor: Tree-in-the-Loop Text Generation for Language Model Explainability and Adaptation

> 现今，LLMs 已被广泛应用于各类下游任务，诸如自动补全、辅助写作和聊天式文本生成等。但是，其底层搜索算法产生的输出候选选择过程尚待深入探究与解读。为此，我们创新性地引入一种“树内循环”策略，以束搜索树的可视化为核心手段，助力分析、诠释并优化生成输出。同时，我们推出一款名为 generAItor 的可视化分析技术，该技术通过丰富多样的任务专属小部件强化束搜索树，提供精准可视化的展示及交互功能。借助这一方法，用户可以在不同层级上进行互动操作，通过生成、探索、对比输出候选以及依据反馈数据微调模型，形成一个迭代处理链路。实证案例表明，相较于现有基于模板的方法，我们的工具能挖掘出性别偏见分析领域的崭新洞察。进一步地，在一项定性用户研究中，我们验证了此方法的实际应用价值。最后，我们还从量化角度评估了模型对类似文本生成场景中少量样本的快速适应能力。

> Large language models (LLMs) are widely deployed in various downstream tasks, e.g., auto-completion, aided writing, or chat-based text generation. However, the considered output candidates of the underlying search algorithm are under-explored and under-explained. We tackle this shortcoming by proposing a tree-in-the-loop approach, where a visual representation of the beam search tree is the central component for analyzing, explaining, and adapting the generated outputs. To support these tasks, we present generAItor, a visual analytics technique, augmenting the central beam search tree with various task-specific widgets, providing targeted visualizations and interaction possibilities. Our approach allows interactions on multiple levels and offers an iterative pipeline that encompasses generating, exploring, and comparing output candidates, as well as fine-tuning the model based on adapted data. Our case study shows that our tool generates new insights in gender bias analysis beyond state-of-the-art template-based methods. Additionally, we demonstrate the applicability of our approach in a qualitative user study. Finally, we quantitatively evaluate the adaptability of the model to few samples, as occurring in text-generation use cases.

[Arxiv](https://arxiv.org/abs/2403.07627)