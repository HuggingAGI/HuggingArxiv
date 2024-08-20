# 解毒剂：大型语言模型在有害微调后的安全对齐策略

发布时间：2024年08月18日

`LLM应用` `网络安全` `人工智能`

> Antidote: Post-fine-tuning Safety Alignment for Large Language Models against Harmful Fine-tuning

# 摘要

> 安全对齐的大型语言模型 (LLM) 面临有害微调攻击的风险，少量有害数据即可破坏其安全对齐。现有缓解策略包括对齐阶段和微调阶段的解决方案，但这些策略在特定训练超参数下会失效，如高学习率或长训练周期，而这又是确保微调性能所必需的。为此，我们提出 Antidote，一种微调后的解决方案，不受训练超参数影响。Antidote 的理念是通过移除有害参数来恢复模型的正常行为，无论这些参数如何形成。我们在有害微调后引入一次性剪枝，移除有害权重。尽管方法简单，实证结果表明，Antidote 能在保持下游任务准确性的同时降低有害分数。

> Safety aligned Large Language Models (LLMs) are vulnerable to harmful fine-tuning attacks \cite{qi2023fine}-- a few harmful data mixed in the fine-tuning dataset can break the LLMs's safety alignment. Existing mitigation strategies include alignment stage solutions \cite{huang2024vaccine, rosati2024representation} and fine-tuning stage solutions \cite{huang2024lazy,mukhoti2023fine}. However, our evaluation shows that both categories of defenses fail \textit{when some specific training hyper-parameters are chosen} -- a large learning rate or a large number of training epochs in the fine-tuning stage can easily invalidate the defense, which however, is necessary to guarantee finetune performance. To this end, we propose Antidote, a post-fine-tuning stage solution, which remains \textbf{\textit{agnostic to the training hyper-parameters in the fine-tuning stage}}. Antidote relies on the philosophy that by removing the harmful parameters, the harmful model can be recovered from the harmful behaviors, regardless of how those harmful parameters are formed in the fine-tuning stage. With this philosophy, we introduce a one-shot pruning stage after harmful fine-tuning to remove the harmful weights that are responsible for the generation of harmful content. Despite its embarrassing simplicity, empirical results show that Antidote can reduce harmful score while maintaining accuracy on downstream tasks.

[Arxiv](https://arxiv.org/abs/2408.09600)