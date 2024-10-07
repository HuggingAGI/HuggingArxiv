# 大规模模型合并的关键何在？

发布时间：2024年10月04日

`LLM理论` `人工智能` `机器学习`

> What Matters for Model Merging at Scale?

# 摘要

> 模型合并旨在将多个专家模型融合成一个更强大的单一模型，带来存储和服务成本降低、泛化能力提升及支持去中心化开发等好处。尽管前景看好，但以往研究多聚焦于少数小型模型的合并，留下了关于模型规模扩展及其与基础模型质量和专家模型数量等关键因素相互作用如何影响合并模型性能的诸多疑问。本研究系统评估了大规模模型合并的效果，探讨了这些因素的影响。我们采用四种主流合并方法——平均、任务算术、Dare和TIES，在1B至64B参数范围内合并完全微调的模型，最多合并8个专家模型。我们在专家训练任务和零样本泛化到未见任务上评估合并模型。实验揭示了以下新见解：首先，专家模型源自强大基础模型时合并更有效；其次，大模型更易合并；第三，合并持续提升泛化能力，尤其在合并8个大型专家模型时，合并模型泛化优于多任务训练模型；第四，大模型支持更多专家模型合并；第五，不同合并方法在大规模下表现相似。总体而言，研究揭示了模型合并的有趣特性，也指出了其局限。我们期望本研究能为未来大规模合并研究提供参考。

> Model merging aims to combine multiple expert models into a more capable single model, offering benefits such as reduced storage and serving costs, improved generalization, and support for decentralized model development. Despite its promise, previous studies have primarily focused on merging a few small models. This leaves many unanswered questions about the effect of scaling model size and how it interplays with other key factors -- like the base model quality and number of expert models -- , to affect the merged model's performance. This work systematically evaluates the utility of model merging at scale, examining the impact of these different factors. We experiment with merging fully fine-tuned models using 4 popular merging methods -- Averaging, Task~Arithmetic, Dare, and TIES -- across model sizes ranging from 1B-64B parameters and merging up to 8 different expert models. We evaluate the merged models on both held-in tasks, i.e., the expert's training tasks, and zero-shot generalization to unseen held-out tasks. Our experiments provide several new insights about model merging at scale and the interplay between different factors. First, we find that merging is more effective when experts are created from strong base models, i.e., models with good zero-shot performance. Second, larger models facilitate easier merging. Third merging consistently improves generalization capabilities. Notably, when merging 8 large expert models, the merged models often generalize better compared to the multitask trained models. Fourth, we can better merge more expert models when working with larger models. Fifth, different merging methods behave very similarly at larger scales. Overall, our findings shed light on some interesting properties of model merging while also highlighting some limitations. We hope that this study will serve as a reference point on large-scale merging for upcoming research.

[Arxiv](https://arxiv.org/abs/2410.03617)