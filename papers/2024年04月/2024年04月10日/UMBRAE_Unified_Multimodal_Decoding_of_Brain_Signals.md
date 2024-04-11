# UMBRAE：一种整合多种模式的脑信号解读技术

发布时间：2024年04月10日

`LLM应用` `脑科学` `神经信号处理`

> UMBRAE: Unified Multimodal Decoding of Brain Signals

# 摘要

> 我们针对脑动力研究中的难题提出了创新解决方案，这些难题包括文献难以精确捕捉空间信息和对特定主题模型的需求。我们提出了UMBRAE，一种新颖的多模态脑信号解码技术。首先，我们设计了一个高效的通用大脑编码器，用以从神经信号中提取具体的概念和空间细节，并借助多模态大型语言模型（MLLM）在不同层次上恢复对象描述。接着，我们开发了一种跨主题训练策略，将个体特征整合到共享特征空间中，使得模型能够在不同个体间通用，且在资源消耗不变的情况下，取得比特定模型更出色的成果。此外，我们展示了UMBRAE在新主题上的弱监督适应能力，仅需极小部分的训练数据即可。实验验证了UMBRAE在新任务上的卓越表现，并在传统任务上也展现出超越现有方法的实力。为了更好地评估和共享我们的方法，我们创建了BrainHub这一全面的脑科学基准，并公开了相关代码和资源，可通过https://weihaox.github.io/UMBRAE访问。

> We address prevailing challenges of the brain-powered research, departing from the observation that the literature hardly recover accurate spatial information and require subject-specific models. To address these challenges, we propose UMBRAE, a unified multimodal decoding of brain signals. First, to extract instance-level conceptual and spatial details from neural signals, we introduce an efficient universal brain encoder for multimodal-brain alignment and recover object descriptions at multiple levels of granularity from subsequent multimodal large language model (MLLM). Second, we introduce a cross-subject training strategy mapping subject-specific features to a common feature space. This allows a model to be trained on multiple subjects without extra resources, even yielding superior results compared to subject-specific models. Further, we demonstrate this supports weakly-supervised adaptation to new subjects, with only a fraction of the total training data. Experiments demonstrate that UMBRAE not only achieves superior results in the newly introduced tasks but also outperforms methods in well established tasks. To assess our method, we construct and share with the community a comprehensive brain understanding benchmark BrainHub. Our code and benchmark are available at https://weihaox.github.io/UMBRAE.

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x1.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x2.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x3.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/0_BLEU-1.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2_CIDEr.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5_RefCLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/6_acc_0.5_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7_IoU_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/1_ROUGE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/3_SPICE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/4_CLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/8_acc_0.5_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/9_IoU_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/category_distribution.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/object_count_salient_creatures.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/object_count_salient_objects.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/object_count_inconspicuous.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/3.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/4.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/24.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/43.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/49.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/181.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/981.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/961.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/207.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/234.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/235.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/237.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/240.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/242.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x4.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x5.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x6.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x7.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x8.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x9.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/10.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/12.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/15.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/19.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/22.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/66.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/64.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/62.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/39.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/63.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/43.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/44.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/93.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/66.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/64.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/62.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/39.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/63.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/43.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/44.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/93.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/66.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/64.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/62.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/39.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/63.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/43.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/44.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/93.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/66.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/64.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/62.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/39.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/63.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/43.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/44.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/93.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/66.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/64.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/62.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/39.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/63.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/43.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/44.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/93.jpg)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/0_BLEU-1.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2_CIDEr.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5_RefCLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/6_acc_0.5_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7_IoU_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/1_ROUGE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/3_SPICE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/4_CLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/8_acc_0.5_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/9_IoU_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/0_BLEU-1.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2_CIDEr.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5_RefCLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/6_acc_0.5_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7_IoU_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/1_ROUGE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/3_SPICE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/4_CLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/8_acc_0.5_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/9_IoU_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/0_BLEU-1.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/2_CIDEr.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/5_RefCLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/6_acc_0.5_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/7_IoU_A.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/1_ROUGE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/3_SPICE.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/4_CLIP-S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/8_acc_0.5_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/9_IoU_S.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x10.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x11.png)

![UMBRAE：一种整合多种模式的脑信号解读技术](../../../paper_images/2404.07202/x12.png)

[Arxiv](https://arxiv.org/abs/2404.07202)