# 修剪与蒸馏：低资源NLP高效之道

发布时间：2024年09月21日

`LLM应用` `可持续发展`

> On Importance of Pruning and Distillation for Efficient Low Resource NLP

# 摘要

> 大型 transformer 模型在 NLP 领域掀起了一场革命，尤其是在文本分类任务中取得了显著进展。然而，这种进步伴随着巨大的计算资源需求，训练时间和成本也随之飙升。尽管在缩小和加速英语模型方面已有一些尝试（如 Distilbert 和 MobileBert），但对于低资源语言的研究仍显不足。本研究聚焦于低资源语言马拉地语，以 marathi-topic-all-doc-v2 模型为基石，我们采用了一系列优化技术，旨在缩短计算时间和降低内存消耗。我们的目标是在保持高准确性的前提下，提升马拉地语 transformer 模型的效率，并减轻其计算负担。通过 MahaNews 数据集和 L3Cube 的 marathi-topic-all-doc-v2 模型，我们分别及联合应用了块移动剪枝、知识蒸馏和混合精度方法，显著提升了模型效率。研究显示，合理的剪枝策略是实现高效能的关键。此外，我们还探讨了效率提升与环境影响之间的平衡，指出优化模型架构对构建可持续计算生态的重要性。在单 GPU 系统上，我们发现 25% 剪枝结合知识蒸馏的配置最为理想，不仅保持了基准准确性，还将计算速度提升了 2.56 倍。

> The rise of large transformer models has revolutionized Natural Language Processing, leading to significant advances in tasks like text classification. However, this progress demands substantial computational resources, escalating training duration, and expenses with larger model sizes. Efforts have been made to downsize and accelerate English models (e.g., Distilbert, MobileBert). Yet, research in this area is scarce for low-resource languages.
  In this study, we explore the case of the low-resource Indic language Marathi. Leveraging the marathi-topic-all-doc-v2 model as our baseline, we implement optimization techniques to reduce computation time and memory usage. Our focus is on enhancing the efficiency of Marathi transformer models while maintaining top-tier accuracy and reducing computational demands. Using the MahaNews document classification dataset and the marathi-topic-all-doc-v2 model from L3Cube, we apply Block Movement Pruning, Knowledge Distillation, and Mixed Precision methods individually and in combination to boost efficiency. We demonstrate the importance of strategic pruning levels in achieving desired efficiency gains. Furthermore, we analyze the balance between efficiency improvements and environmental impact, highlighting how optimized model architectures can contribute to a more sustainable computational ecosystem. Implementing these techniques on a single GPU system, we determine that the optimal configuration is 25\% pruning + knowledge distillation. This approach yielded a 2.56x speedup in computation time while maintaining baseline accuracy levels.

[Arxiv](https://arxiv.org/abs/2409.14162)