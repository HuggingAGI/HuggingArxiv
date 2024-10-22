# 探究视觉与语言任务中的课程学习：小规模多模态训练研究

发布时间：2024年10月20日

`LLM理论` `人工智能`

> Exploring Curriculum Learning for Vision-Language Tasks: A Study on Small-Scale Multimodal Training

# 摘要

> 在专业领域，训练大型机器学习模型往往缺乏充足数据。在这种情况下，各种方法应运而生，力求“以少胜多”，如微调预训练模型、动态调整数据难度（课程学习）及优化模型类型与规模。高效机器学习方法还借鉴人类学习经验，考虑机器学习系统能接触到的词汇量与13岁儿童相当（约100M单词）的场景。我们参与BabyLM挑战的多模态赛道，探讨了在数据有限环境下三个关键变量的作用，对比了课程学习、仅文本预训练及模型类型。通过调节这些变量，我们在多模态（文本+图像）和单模态（仅文本）任务上进行评估。结果显示，课程学习在多模态评估中表现优异，尤其在结合仅文本预训练时。而在仅文本任务中，课程学习对参数较少的模型有所助益。我们推测，这些结果可能源于模型架构差异及训练设计的不同。

> For specialized domains, there is often not a wealth of data with which to train large machine learning models. In such limited data / compute settings, various methods exist aiming to $\textit{do more with less}$, such as finetuning from a pretrained model, modulating difficulty levels as data are presented to a model (curriculum learning), and considering the role of model type / size. Approaches to efficient $\textit{machine}$ learning also take inspiration from $\textit{human}$ learning by considering use cases where machine learning systems have access to approximately the same number of words experienced by a 13 year old child (100M words). We investigate the role of 3 primary variables in a limited data regime as part of the multimodal track of the BabyLM challenge. We contrast: (i) curriculum learning, (ii), pretraining (with text-only data), (iii) model type. We modulate these variables and assess them on two types of tasks: (a) multimodal (text+image), and (b) unimodal (text-only) tasks. We find that curriculum learning benefits multimodal evaluations over non-curriclum learning models, particularly when combining text-only pretraining. On text-only tasks, curriculum learning appears to help models with smaller trainable parameter counts. We suggest possible reasons based on architectural differences and training designs as to why one might observe such results.

[Arxiv](https://arxiv.org/abs/2410.15509)