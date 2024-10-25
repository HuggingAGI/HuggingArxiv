# Mod-Squad：将专家混合设计为模块化多任务学习者

发布时间：2022年12月15日

`其他` `多任务学习`

> Mod-Squad: Designing Mixture of Experts As Modular Multi-Task Learners

# 摘要

> 摘要：多任务学习（MTL）中的优化比单任务学习（STL）更具挑战性，因为来自不同任务的梯度可能相互矛盾。当任务相关时，在它们之间共享一些参数（合作）可能是有益的。然而，一些任务需要具有特定类型数据或判别专业知识的额外参数（专业化）。为了应对 MTL 挑战，我们提出了 Mod-Squad，这是一种新的模型，被模块化到专家小组（一个“小队”）中。这种结构使我们能够将合作和专业化形式化为匹配专家和任务的过程。我们在单个模型的训练过程中优化这种匹配过程。具体来说，我们将专家混合（MoE）层纳入到一个 Transformer 模型中，并带有一个新的损失，该损失包含了任务和专家之间的相互依赖关系。结果，每个任务仅激活一小部分专家。这防止了所有任务之间共享整个骨干模型，这增强了模型，特别是当训练集大小和任务数量增加时。更有趣的是，对于每个任务，我们可以提取出这一小部分专家作为一个独立模型，其性能与大型模型相同。在具有 13 个视觉任务的 Taskonomy 数据集和具有 5 个视觉任务的 PASCAL-Context 数据集上进行的大量实验表明了我们方法的优越性。

> 
Abstract:Optimization in multi-task learning (MTL) is more challenging than single-task learning (STL), as the gradient from different tasks can be contradictory. When tasks are related, it can be beneficial to share some parameters among them (cooperation). However, some tasks require additional parameters with expertise in a specific type of data or discrimination (specialization). To address the MTL challenge, we propose Mod-Squad, a new model that is Modularized into groups of experts (a 'Squad'). This structure allows us to formalize cooperation and specialization as the process of matching experts and tasks. We optimize this matching process during the training of a single model. Specifically, we incorporate mixture of experts (MoE) layers into a transformer model, with a new loss that incorporates the mutual dependence between tasks and experts. As a result, only a small set of experts are activated for each task. This prevents the sharing of the entire backbone model between all tasks, which strengthens the model, especially when the training set size and the number of tasks scale up. More interestingly, for each task, we can extract the small set of experts as a standalone model that maintains the same performance as the large model. Extensive experiments on the Taskonomy dataset with 13 vision tasks and the PASCAL-Context dataset with 5 vision tasks show the superiority of our approach.
    

[Arxiv](https://arxiv.org/pdf/2212.08066)