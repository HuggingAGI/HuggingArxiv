# 开放词汇分割的可迁移性和原则性高效性

发布时间：2024年04月10日

`RAG` `计算机视觉`

> Transferable and Principled Efficiency for Open-Vocabulary Segmentation

# 摘要

> 预训练基础视觉-语言模型的最新成就让开放词汇分割（OVS）变得触手可及。然而，这一方法因其庞大的模型规模和微调过程中的高昂成本而面临挑战，限制了其在实际应用中的普及和可行性。虽然传统的模型压缩和高效微调技术能够应对这些挑战，但它们往往基于经验法则，难以通用。我们的目标是通过采用更小规模的模型以降低训练成本，实现与基于大型视觉-语言基础模型的先前OVS研究相媲美甚至更优的性能。我们的核心策略是让效率原则化，实现从一种OVS框架到另一种的无缝迁移，无需额外定制。在多个OVS基准测试中进行的广泛实验验证了我们在分割精度与计算成本之间取得的卓越平衡，超越了以往的研究。相关代码已在 https://github.com/Xujxyang/OpenTrans 上发布。

> Recent success of pre-trained foundation vision-language models makes Open-Vocabulary Segmentation (OVS) possible. Despite the promising performance, this approach introduces heavy computational overheads for two challenges: 1) large model sizes of the backbone; 2) expensive costs during the fine-tuning. These challenges hinder this OVS strategy from being widely applicable and affordable in real-world scenarios. Although traditional methods such as model compression and efficient fine-tuning can address these challenges, they often rely on heuristics. This means that their solutions cannot be easily transferred and necessitate re-training on different models, which comes at a cost. In the context of efficient OVS, we target achieving performance that is comparable to or even better than prior OVS works based on large vision-language foundation models, by utilizing smaller models that incur lower training costs. The core strategy is to make our efficiency principled and thus seamlessly transferable from one OVS framework to others without further customization. Comprehensive experiments on diverse OVS benchmarks demonstrate our superior trade-off between segmentation accuracy and computation costs over previous works. Our code is available on https://github.com/Xujxyang/OpenTrans

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/slot4.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/structure9.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/sem_seg_head_2.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/alpha2.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/visualize3.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/Figure6.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/Figure8.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/vis_sup.jpg)

![开放词汇分割的可迁移性和原则性高效性](../../../paper_images/2404.07448/rebuttal-alpha.jpg)

[Arxiv](https://arxiv.org/abs/2404.07448)