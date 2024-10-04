# 元模型：一种通过解析嵌入与自然语言，揭示大型语言模型行为的架构

发布时间：2024年10月03日

`LLM理论` `人工智能` `网络安全`

> Meta-Models: An Architecture for Decoding LLM Behaviors Through Interpreted Embeddings and Natural Language

# 摘要

> 随着 LLM 深入我们的生活，欺骗行为的潜在危害要求我们忠实解读其决策。传统探测方法虽有效，但仅适用于狭窄任务，全面解释仍待完善。为此，我们探索了元模型架构，它从输入模型提取激活，回答其行为相关问题。通过训练与评估，我们发现元模型在分布外任务中表现出色，为未来研究开辟了新方向。

> As Large Language Models (LLMs) become increasingly integrated into our daily lives, the potential harms from deceptive behavior underlie the need for faithfully interpreting their decision-making. While traditional probing methods have shown some effectiveness, they remain best for narrowly scoped tasks while more comprehensive explanations are still necessary. To this end, we investigate meta-models-an architecture using a "meta-model" that takes activations from an "input-model" and answers natural language questions about the input-model's behaviors. We evaluate the meta-model's ability to generalize by training them on selected task types and assessing their out-of-distribution performance in deceptive scenarios. Our findings show that meta-models generalize well to out-of-distribution tasks and point towards opportunities for future research in this area.

[Arxiv](https://arxiv.org/abs/2410.02472)