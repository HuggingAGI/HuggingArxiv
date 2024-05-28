# 序列模型编辑中的扰动抑制

发布时间：2024年05月27日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在序列模型编辑过程中的理论问题，特别是编辑矩阵的条件数对模型通用能力的影响。论文提出了PRUNE框架来解决这一问题，并通过理论分析和实验验证了其有效性。这属于对LLM进行理论分析和改进的范畴，因此归类为LLM理论。` `人工智能`

> Perturbation-Restrained Sequential Model Editing

# 摘要

> 模型编辑领域正崭露头角，专注于在不进行大规模重新训练的情况下更新大型语言模型（LLMs）的知识。但遗憾的是，随着编辑次数的增多，现有的模型编辑技术会削弱LLMs的通用能力，这对持续学习构成了挑战。本文首先从理论上揭示，序列模型编辑中影响通用能力的关键在于编辑矩阵的条件数，这一数值反映了模型对编辑的敏感度。统计分析进一步证实，随着编辑次数的增加，这一敏感度加剧，导致通用能力的退化。为此，我们提出了PRUNE框架，通过在序列编辑中施加条件数约束，有效控制了编辑对模型知识的扰动，从而保护了通用能力。通过在三个LLMs上应用三种主流编辑方法，并针对四个下游任务进行系统实验，我们验证了PRUNE在保持编辑效果的同时，显著维护了模型的通用能力。相关代码和数据已公开在https://github.com/mjy1111/PRUNE。

> Model editing is an emerging field that focuses on updating the knowledge embedded within large language models (LLMs) without extensive retraining. However, current model editing methods significantly compromise the general abilities of LLMs as the number of edits increases, and this trade-off poses a substantial challenge to the continual learning of LLMs. In this paper, we first theoretically analyze that the factor affecting the general abilities in sequential model editing lies in the condition number of the edited matrix. The condition number of a matrix represents its numerical sensitivity, and therefore can be used to indicate the extent to which the original knowledge associations stored in LLMs are perturbed after editing. Subsequently, statistical findings demonstrate that the value of this factor becomes larger as the number of edits increases, thereby exacerbating the deterioration of general abilities. To this end, a framework termed Perturbation Restraint on Upper bouNd for Editing (PRUNE) is proposed, which applies the condition number restraints in sequential editing. These restraints can lower the upper bound on perturbation to edited models, thus preserving the general abilities. Systematically, we conduct experiments employing three popular editing methods on three LLMs across four representative downstream tasks. Evaluation results show that PRUNE can preserve considerable general abilities while maintaining the editing performance effectively in sequential model editing. The code and data are available at https://github.com/mjy1111/PRUNE.

![序列模型编辑中的扰动抑制](../../../paper_images/2405.16821/x1.png)

![序列模型编辑中的扰动抑制](../../../paper_images/2405.16821/x2.png)

![序列模型编辑中的扰动抑制](../../../paper_images/2405.16821/x3.png)

![序列模型编辑中的扰动抑制](../../../paper_images/2405.16821/x4.png)

[Arxiv](https://arxiv.org/abs/2405.16821)