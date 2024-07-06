# FSM：一种基于有限状态机的零-shot 提示方法，专为多跳问题回答设计
发布时间：2024年07月03日

`RAG`
> FSM: A Finite State Machine Based Zero-Shot Prompting Paradigm for Multi-Hop Question Answering
>
> 结合思维链提示的大型语言模型在简单推理任务上表现卓越，但在多跳问答任务中因幻觉、错误传播等问题表现欠佳。为此，我们引入了有限状态机提示法，通过迭代分解问题并实时自校，显著提升复杂任务的推理精度和可信度。实验表明，该方法在挑战性数据集上超越基线，有效缓解了中间错误导致的幻觉问题，并强化了模型遵循输出格式的能力，大幅简化了答案解读与格式调整的复杂性。
>
> https://arxiv.org/abs/2407.02964

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02964/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02964/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02964/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02964/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.02964/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.02964](https://arxiv.org/abs/2407.02964)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1