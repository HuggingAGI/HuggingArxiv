# 深度伪造检测中的小聪明与大糊涂

发布时间：2024年08月15日

`LLM应用` `人工智能`

> Penny-Wise and Pound-Foolish in Deepfake Detection

# 摘要

> 深度伪造技术的广泛应用引发了对其潜在滥用的严重关切，迫切需要有效的检测手段。然而，许多现有方法过于注重短期效益，牺牲了长期效果。本文指出，仅在单一数据集上微调预训练模型以追求短期目标，忽视了泛化和知识保留的重要性。为此，我们提出了PoundNet框架，旨在提升深度伪造检测的泛化能力。PoundNet通过可学习的提示设计和平衡目标，既保留了上游任务的知识，又增强了下游任务的泛化性。我们在标准数据集上训练PoundNet，并在10个大型公共数据集上进行评估，结果显示，PoundNet在深度伪造检测性能上提升了19%，同时在对象分类任务上保持了63%的高效表现。相关代码和数据已公开在GitHub上。

> The diffusion of deepfake technologies has sparked serious concerns about its potential misuse across various domains, prompting the urgent need for robust detection methods. Despite advancement, many current approaches prioritize short-term gains at expense of long-term effectiveness. This paper critiques the overly specialized approach of fine-tuning pre-trained models solely with a penny-wise objective on a single deepfake dataset, while disregarding the pound-wise balance for generalization and knowledge retention. To address this "Penny-Wise and Pound-Foolish" issue, we propose a novel learning framework (PoundNet) for generalization of deepfake detection on a pre-trained vision-language model. PoundNet incorporates a learnable prompt design and a balanced objective to preserve broad knowledge from upstream tasks (object classification) while enhancing generalization for downstream tasks (deepfake detection). We train PoundNet on a standard single deepfake dataset, following common practice in the literature. We then evaluate its performance across 10 public large-scale deepfake datasets with 5 main evaluation metrics-forming the largest benchmark test set for assessing the generalization ability of deepfake detection models, to our knowledge. The comprehensive benchmark evaluation demonstrates the proposed PoundNet is significantly less "Penny-Wise and Pound-Foolish", achieving a remarkable improvement of 19% in deepfake detection performance compared to state-of-the-art methods, while maintaining a strong performance of 63% on object classification tasks, where other deepfake detection models tend to be ineffective. Code and data are open-sourced at https://github.com/iamwangyabin/PoundNet.

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x1.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x2.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x3.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x4.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x5.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x6.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x7.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x8.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x9.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x10.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x11.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x12.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x13.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x14.png)

![深度伪造检测中的小聪明与大糊涂](../../../paper_images/2408.08412/x15.png)

[Arxiv](https://arxiv.org/abs/2408.08412)