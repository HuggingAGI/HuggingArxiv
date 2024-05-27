# 融合提示的上下文学习，提升端到端任务导向型对话系统的协同效应
发布时间：2024年05月24日

`提示工程`
> Synergizing In-context Learning with Hints for End-to-end Task-oriented Dialog Systems
>
> 当训练数据稀缺时，基于LLM的端到端任务导向对话系统通过情境学习展现出优于传统监督模型的性能。这得益于LLM通过少量示例学习任何任务的内在能力。然而，随着训练对话量的增加，监督模型因其能更好地模仿训练数据中的系统响应风格而超越了LLM。为此，我们推出了SyncTOD，它巧妙地结合了LLM与任务相关的提示，以优化对齐效果。具体而言，SyncTOD通过训练辅助模型来提供这些提示，并为情境学习选择合适的示例。借助ChatGPT，SyncTOD在数据稀缺环境下超越了其他基于LLM的系统和最新模型，同时在数据充足时也保持了竞争力。
>
> https://arxiv.org/abs/2405.15585

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15585/arch3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15585/smd_entity_f1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15585/multiwoz_entity_f1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15585/bitod_entity_f1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15585/portal.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.15585](https://arxiv.org/abs/2405.15585)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886