# 工具规划器：利用工具聚类，为大型语言模型打造动态解决方案树规划
发布时间：2024年06月06日


> Tool-Planner: Dynamic Solution Tree Planning for Large Language Model with Tool Clustering
>
> 大型语言模型（LLMs）以其卓越的推理能力，成功解决了众多复杂问题。近期，这一能力被应用于工具学习的领域，通过展示工具使用示例及其功能，LLMs能够制定并执行工具调用计划。这种方法使LLMs能够处理原本无法独立完成的任务，从而在多任务环境中发挥更大潜力。然而，此方法也面临两大挑战：一是冗余的错误纠正导致计划不稳定和执行时间延长；二是在多个工具中设计正确计划。为此，我们提出了Tool-Planner框架，该框架根据功能相似的API将工具分组，并允许LLMs跨工具包进行规划。当出现工具错误时，语言模型可依据工具包重新选择和调整工具。实验结果显示，我们的方法在多个数据集上均表现出高通过率和胜率，并优化了GPT-4和Claude 3等模型中工具学习的规划策略，充分展示了我们方法的潜力。
>
> https://arxiv.org/abs/2406.03807


<hr />

- 论文原文: [https://arxiv.org/abs/2406.03807](https://arxiv.org/abs/2406.03807)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886