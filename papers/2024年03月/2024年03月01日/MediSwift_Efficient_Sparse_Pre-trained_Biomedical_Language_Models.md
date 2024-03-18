# [MediSwift 是一种高效、预先训练的稀疏型生物医学语言模型，专为提升处理领域内大规模数据的效率而设计。]

发布时间：2024年03月01日

`LLM应用`

> MediSwift: Efficient Sparse Pre-trained Biomedical Language Models

> 现今LLMs大多基于通用数据训练，但在生物医学这类特定领域任务中，专用LLMs崭露头角，其性能已超乎传统通用模型。尽管领域特化预训练能提升效率并缩小模型规模，但训练此类LLMs所需的计算资源仍居高不下，给预算带来不小压力。为此，我们推出了MediSwift——一套专注于生物医学领域的稀疏预训练语言模型系列。MediSwift在预训练阶段借助高达75%的权重稀疏化技术，成功减少了2至2.5倍的训练FLOPs，所有预训练过程均在专为充分利用无结构权重稀疏加速效益而设计的Cerebras CS-2系统上运行，极大地提升了模型效能。经过精心的密集微调与策略性软提示调整后，MediSwift模型在面对如PubMedQA等生物医学任务时，即使面对高达70亿参数的现有LLMs也能脱颖而出，树立起新效率-准确率基准。研究结果显示，结合密集微调与软提示的稀疏预训练方式，为在专业领域打造高效、性能卓越的模型开辟了一条切实可行的道路。

> Large language models (LLMs) are typically trained on general source data for various domains, but a recent surge in domain-specific LLMs has shown their potential to outperform general-purpose models in domain-specific tasks (e.g., biomedicine). Although domain-specific pre-training enhances efficiency and leads to smaller models, the computational costs of training these LLMs remain high, posing budgeting challenges. We introduce MediSwift, a suite of biomedical LMs that leverage sparse pre-training on domain-specific biomedical text data. By inducing up to 75% weight sparsity during the pre-training phase, MediSwift achieves a 2-2.5x reduction in training FLOPs. Notably, all sparse pre-training was performed on the Cerebras CS-2 system, which is specifically designed to realize the acceleration benefits from unstructured weight sparsity, thereby significantly enhancing the efficiency of the MediSwift models. Through subsequent dense fine-tuning and strategic soft prompting, MediSwift models outperform existing LLMs up to 7B parameters on biomedical tasks, setting new benchmarks w.r.t efficiency-accuracy on tasks such as PubMedQA. Our results show that sparse pre-training, along with dense fine-tuning and soft prompting, offers an effective method for creating high-performing, computationally efficient models in specialized domains.

[Arxiv](https://arxiv.org/abs/2403.00952)