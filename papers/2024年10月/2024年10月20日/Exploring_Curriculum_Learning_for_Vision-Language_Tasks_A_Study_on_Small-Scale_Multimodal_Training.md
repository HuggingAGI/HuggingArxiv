# 探索视觉与语言任务中的课程学习：小规模多模态训练研究

发布时间：2024年10月20日

`LLM理论` `机器学习`

> Exploring Curriculum Learning for Vision-Language Tasks: A Study on Small-Scale Multimodal Training

# 摘要

> 在专业领域，训练大型机器学习模型往往面临数据匮乏的挑战。在这种资源有限的情况下，我们探索了多种“以少胜多”的方法，如微调预训练模型、动态调整数据难度（课程学习）以及优化模型类型和大小。我们还借鉴了人类学习的经验，考虑了机器学习系统在处理类似13岁孩子所接触的词汇量（约1亿词）时的表现。在BabyLM挑战的多模态赛道中，我们深入研究了三个关键变量在有限数据环境下的作用，并对比了课程学习、仅文本预训练和模型类型对任务表现的影响。我们发现，课程学习在多模态任务中显著优于非课程学习模型，尤其是在结合仅文本预训练时。而在仅文本任务中，课程学习则有助于提升参数较少的模型的表现。我们推测，这些结果可能与模型架构和训练设计的差异有关。

> For specialized domains, there is often not a wealth of data with which to train large machine learning models. In such limited data / compute settings, various methods exist aiming to $\textit{do more with less}$, such as finetuning from a pretrained model, modulating difficulty levels as data are presented to a model (curriculum learning), and considering the role of model type / size. Approaches to efficient $\textit{machine}$ learning also take inspiration from $\textit{human}$ learning by considering use cases where machine learning systems have access to approximately the same number of words experienced by a 13 year old child (100M words). We investigate the role of 3 primary variables in a limited data regime as part of the multimodal track of the BabyLM challenge. We contrast: (i) curriculum learning, (ii), pretraining (with text-only data), (iii) model type. We modulate these variables and assess them on two types of tasks: (a) multimodal (text+image), and (b) unimodal (text-only) tasks. We find that curriculum learning benefits multimodal evaluations over non-curriclum learning models, particularly when combining text-only pretraining. On text-only tasks, curriculum learning appears to help models with smaller trainable parameter counts. We suggest possible reasons based on architectural differences and training designs as to why one might observe such results.

[Arxiv](https://arxiv.org/abs/2410.15509)