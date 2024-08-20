# 利用因果干预技术，精准定位激活参数，优化模型合并过程

发布时间：2024年08月18日

`LLM理论` `计算机科学` `人工智能`

> Activated Parameter Locating via Causal Intervention for Model Merging

# 摘要

> 模型合并技术通过整合多个同源模型，实现了无需额外训练的出色泛化能力。然而，解决多模型间的参数冗余与冲突是一大难题。现有方法虽通过丢弃部分参数来缓解冲突，但往往忽视了微调模型中的任务特定信息。本文提出的激活参数定位（APL）方法，通过因果干预精准评估参数重要性，有效提升参数丢弃的精确度和冲突缓解效果。同时，为简化大量参数处理的复杂性，我们引入了一种基于理论的梯度近似策略。实验结果表明，无论在域内还是域外，APL均展现出卓越的有效性。

> Model merging combines multiple homologous models into one model, achieving convincing generalization without the necessity of additional training. A key challenge in this problem is resolving parameter redundancies and conflicts across multiple models. Existing models have demonstrated that dropping a portion of delta parameters can alleviate conflicts while maintaining performance. However, these methods often drop parameters either randomly or based on magnitude, overlooking task-specific information embedded in fine-tuned models. In this paper, we propose an Activated Parameter Locating (APL) method that utilizes causal intervention to estimate parameter importance, enabling more precise parameter drops and better conflict mitigation. Moreover, to reduce the computational complexity associated with a large number of parameter partitions, we also introduce a theoretically supported gradient approximation strategy for APL. Experiments on model merging within both in-domain and out-of-domain settings, along with associated analyses, showcase the effectiveness of APL.

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/x1.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/x2.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/pruning.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/ablation.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/few-shot.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/activation.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/tau1.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/tau2.png)

![利用因果干预技术，精准定位激活参数，优化模型合并过程](../../../paper_images/2408.09485/roberta.png)

[Arxiv](https://arxiv.org/abs/2408.09485)