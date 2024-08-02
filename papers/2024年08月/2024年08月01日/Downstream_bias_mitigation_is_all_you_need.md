# 只需解决下游偏差，一切问题迎刃而解。

发布时间：2024年08月01日

`LLM理论` `人工智能`

> Downstream bias mitigation is all you need

# 摘要

> 随着基于transformer的架构和大语言模型（LLMs）的兴起，自然语言处理（NLP）的性能得到了显著提升。然而，这些模型在海量网络数据上的训练也引发了关于潜在有害偏见传递的担忧。在实际应用中，LLMs常在特定任务数据集上进行微调，这可能加剧偏见问题。本文探讨了LLMs在预训练阶段吸收的偏见及其微调后的行为。研究发现，预训练后对LLMs的干预对减少偏见效果有限，而特定领域数据集中的偏见影响更为显著，因此在这一阶段进行偏见缓解措施更为有效。尽管预训练至关重要，但模型预训练后，微调数据集中共现率的细微变化也能显著影响模型的偏见程度。

> The advent of transformer-based architectures and large language models (LLMs) have significantly advanced the performance of natural language processing (NLP) models. Since these LLMs are trained on huge corpuses of data from the web and other sources, there has been a major concern about harmful prejudices that may potentially be transferred from the data. In many applications, these pre-trained LLMs are fine-tuned on task specific datasets, which can further contribute to biases. This paper studies the extent of biases absorbed by LLMs during pre-training as well as task-specific behaviour after fine-tuning. We found that controlled interventions on pre-trained LLMs, prior to fine-tuning, have minimal effect on lowering biases in classifiers. However, the biases present in domain-specific datasets play a much bigger role, and hence mitigating them at this stage has a bigger impact. While pre-training does matter, but after the model has been pre-trained, even slight changes to co-occurrence rates in the fine-tuning dataset has a significant effect on the bias of the model.

[Arxiv](https://arxiv.org/abs/2408.00612)