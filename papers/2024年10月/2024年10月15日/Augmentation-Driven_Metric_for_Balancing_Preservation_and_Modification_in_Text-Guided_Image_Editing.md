# 增强驱动度量：平衡文本引导图像编辑中的保留与修改

发布时间：2024年10月15日

`LLM应用` `图像编辑` `计算机视觉`

> Augmentation-Driven Metric for Balancing Preservation and Modification in Text-Guided Image Editing

# 摘要

> 视觉-语言和生成模型的发展极大地推动了文本引导的图像编辑技术，这种技术在根据目标文本进行修改的同时，力求保留源图像的核心元素。然而，由于缺乏专门针对此类编辑的评估指标，现有指标在平衡保留与修改的考量上显得力不从心。特别是，我们的研究发现，广泛使用的CLIPScore指标更倾向于强调修改，而忽视了应保留的关键属性，导致评估结果失准。为此，我们提出了\texttt{AugCLIP}，通过估算与目标文本高度匹配且对源图像改动最小的理想编辑图像的表示，来实现保留与修改的平衡。我们利用多模态大语言模型对源图像和目标文本进行详细描述的增强，构建了一个将CLIP空间划分为源或目标的超平面。理想编辑图像的表示则是源图像到该超平面的正交投影，这一过程综合考虑了各属性间的相互依赖关系及其相对重要性。我们在五个涵盖多样编辑场景的基准数据集上进行了广泛实验，结果显示\texttt{AugCLIP}在符合人类评估标准方面显著优于现有指标。我们还将开源评估代码，以回馈社区。

> The development of vision-language and generative models has significantly advanced text-guided image editing, which seeks \textit{preservation} of core elements in the source image while implementing \textit{modifications} based on the target text. However, in the absence of evaluation metrics specifically tailored for text-guided image editing, existing metrics are limited in balancing the consideration of preservation and modification. Especially, our analysis reveals that CLIPScore, the most commonly used metric, tends to favor modification and ignore core attributes to be preserved, resulting in inaccurate evaluations. To address this problem, we propose \texttt{AugCLIP}, \black{which balances preservation and modification by estimating the representation of an ideal edited image that aligns with the target text with minimum alteration on the source image. We augment detailed textual descriptions on the source image and the target text using a multi-modal large language model, to model a hyperplane that separates CLIP space into source or target. The representation of the ideal edited image is an orthogonal projection of the source image into the hyperplane, which encapsulates the relative importance of each attribute considering the interdependent relationships.} Our extensive experiments on five benchmark datasets, encompassing a diverse range of editing scenarios, demonstrate that \texttt{AugCLIP} aligns remarkably well with human evaluation standards compared to existing metrics. The code for evaluation will be open-sourced to contribute to the community.

[Arxiv](https://arxiv.org/abs/2410.11374)