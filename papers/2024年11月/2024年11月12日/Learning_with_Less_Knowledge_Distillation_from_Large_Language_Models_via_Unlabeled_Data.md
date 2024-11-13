# 通过无标签数据从大型语言模型进行知识蒸馏的少样本学习

发布时间：2024年11月12日

`LLM应用` `知识蒸馏`

> Learning with Less: Knowledge Distillation from Large Language Models via Unlabeled Data

# 摘要

> 在现实世界的自然语言处理应用中，大型语言模型（LLMs）由于在大量数据集上进行了广泛的训练，提供了有前景的解决方案。然而，LLMs 的大尺寸和高计算需求限制了它们在许多应用中的实用性，特别是在需要进一步微调时。为了解决这些限制，通常更倾向于部署较小的模型。然而，它们的训练受到标记数据稀缺的阻碍。相比之下，未标记的数据通常很容易获得，可以利用 LLMs 为训练较小的模型生成伪标签。这使得较小的模型（学生）能够从 LLMs（教师）获取知识，同时降低计算成本。这个过程带来了挑战，例如潜在的噪声伪标签。因此，选择高质量和信息丰富的数据对于提高模型性能同时提高数据利用效率至关重要。为了解决这个问题，我们提出了 LLKD，它能够以更少的计算资源和更少的数据从 LLMs 进行知识蒸馏。LLKD 是一种自适应样本选择方法，结合了来自教师和学生的信号。具体来说，它优先选择教师在其标记中表现出高置信度的样本，表明可靠的标签，以及学生表现出高信息需求的样本，识别需要进一步学习的具有挑战性的样本。我们的综合实验表明，LLKD 在具有更高数据效率的各种数据集上实现了卓越的性能。

> In real-world NLP applications, Large Language Models (LLMs) offer promising solutions due to their extensive training on vast datasets. However, the large size and high computation demands of LLMs limit their practicality in many applications, especially when further fine-tuning is required. To address these limitations, smaller models are typically preferred for deployment. However, their training is hindered by the scarcity of labeled data. In contrast, unlabeled data is often readily which can be leveraged by using LLMs to generate pseudo-labels for training smaller models. This enables the smaller models (student) to acquire knowledge from LLMs(teacher) while reducing computational costs. This process introduces challenges, such as potential noisy pseudo-labels. Selecting high-quality and informative data is therefore critical to enhance model performance while improving the efficiency of data utilization. To address this, we propose LLKD that enables Learning with Less computational resources and less data for Knowledge Distillation from LLMs. LLKD is an adaptive sample selection method that incorporates signals from both the teacher and student. Specifically, it prioritizes samples where the teacher demonstrates high confidence in its labeling, indicating reliable labels, and where the student exhibits a high information need, identifying challenging samples that require further learning. Our comprehensive experiments show that LLKD achieves superior performance across various datasets with higher data efficiency.

[Arxiv](https://arxiv.org/abs/2411.08028)