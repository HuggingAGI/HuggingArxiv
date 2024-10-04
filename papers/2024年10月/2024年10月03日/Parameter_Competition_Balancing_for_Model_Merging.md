# 模型合并中的参数竞争平衡

发布时间：2024年10月03日

`LLM理论` `人工智能` `机器学习`

> Parameter Competition Balancing for Model Merging

# 摘要

> 尽管微调预训练模型很常见，但它们在特定领域外表现不佳。最近，模型合并技术崭露头角，能将多个针对不同任务微调的模型整合成一个。这种策略无需重新训练，就能提升多任务能力。然而，现有方法在处理任务间的冲突和复杂相关性上力不从心，尤其是在参数调整上，这使得在各任务间平衡参数竞争变得棘手。本文提出的 PCB-Merging 技术，轻巧且无需训练，通过调整参数系数实现高效合并。它通过内部平衡评估单任务参数重要性，通过外部平衡评估跨任务参数相似性。低重要性参数被剔除，剩余参数重新缩放，形成最终合并模型。我们在跨任务、跨领域、跨训练及域外泛化等多种场景中验证了该方法。实验表明，该方法在多模态、多领域、多模型大小、多任务、多微调形式及大语言模型中表现卓越，超越现有合并方法。代码已公开：\url{https://github.com/duguodong7/pcb-merging}。

> While fine-tuning pretrained models has become common practice, these models often underperform outside their specific domains. Recently developed model merging techniques enable the direct integration of multiple models, each fine-tuned for distinct tasks, into a single model. This strategy promotes multitasking capabilities without requiring retraining on the original datasets. However, existing methods fall short in addressing potential conflicts and complex correlations between tasks, especially in parameter-level adjustments, posing a challenge in effectively balancing parameter competition across various tasks. This paper introduces an innovative technique named PCB-Merging (Parameter Competition Balancing), a lightweight and training-free technique that adjusts the coefficients of each parameter for effective model merging. PCB-Merging employs intra-balancing to gauge parameter significance within individual tasks and inter-balancing to assess parameter similarities across different tasks. Parameters with low importance scores are dropped, and the remaining ones are rescaled to form the final merged model. We assessed our approach in diverse merging scenarios, including cross-task, cross-domain, and cross-training configurations, as well as out-of-domain generalization. The experimental results reveal that our approach achieves substantial performance enhancements across multiple modalities, domains, model sizes, number of tasks, fine-tuning forms, and large language models, outperforming existing model merging methods. The code is publicly available at: \url{https://github.com/duguodong7/pcb-merging}.

[Arxiv](https://arxiv.org/abs/2410.02396)