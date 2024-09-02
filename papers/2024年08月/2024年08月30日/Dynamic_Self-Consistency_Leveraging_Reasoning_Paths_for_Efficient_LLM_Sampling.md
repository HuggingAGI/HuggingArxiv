# 动态自一致性：借助推理路径提升 LLM 采样效率

发布时间：2024年08月30日

`LLM应用` `问答系统` `人工智能`

> Dynamic Self-Consistency: Leveraging Reasoning Paths for Efficient LLM Sampling

# 摘要

> Self-Consistency (SC) 通过多次采样 LLM 并输出最频繁的解决方案来减轻幻觉，但计算成本与样本数量成正比。我们提出的 Reasoning-Aware Self-Consistency (RASC) 框架，通过考虑输出答案和推理路径，动态调整样本生成数量，优化样本使用并增强答案可靠性。在多个 LLM 和 QA 数据集上的测试显示，RASC 不仅优于现有方法，还平均减少了 80% 的样本使用量，同时保持或提升了高达 5% 的准确性。

> Self-Consistency (SC) is a widely used method to mitigate hallucinations in Large Language Models (LLMs) by sampling the LLM multiple times and outputting the most frequent solution. Despite its benefits, SC results in significant computational costs proportional to the number of samples generated. Previous early-stopping approaches, such as Early Stopping Self Consistency and Adaptive Consistency, have aimed to reduce these costs by considering output consistency, but they do not analyze the quality of the reasoning paths (RPs) themselves. To address this issue, we propose Reasoning-Aware Self-Consistency (RASC), an innovative early-stopping framework that dynamically adjusts the number of sample generations by considering both the output answer and the RPs from Chain of Thought (CoT) prompting. RASC assigns confidence scores sequentially to the generated samples, stops when certain criteria are met, and then employs weighted majority voting to optimize sample usage and enhance answer reliability. We comprehensively test RASC with multiple LLMs across varied QA datasets. RASC outperformed existing methods and significantly reduces sample usage by an average of 80% while maintaining or improving accuracy up to 5% compared to the original SC

[Arxiv](https://arxiv.org/abs/2408.17017)