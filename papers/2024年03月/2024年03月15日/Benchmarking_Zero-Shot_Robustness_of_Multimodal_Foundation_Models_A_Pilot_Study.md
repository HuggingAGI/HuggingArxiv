# 本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。

发布时间：2024年03月15日

`Agent` `图像识别` `鲁棒性分析`

> Benchmarking Zero-Shot Robustness of Multimodal Foundation Models: A Pilot Study

# 摘要

> 预训练利用描述图像的原始文本构建图像表征，使得模型能够在零样本条件下将学习到的知识迁移到下游视觉任务中。诸如 CLIP 等多模态基础模型，在大量网络数据集上经过预训练，其零样本表现达到了前所未有的水平，甚至在无需针对具体任务进行训练时也能与全监督方法一较高下。除了在分类准确率上表现出色，研究发现这类模型在面临自然分布转移时，其鲁棒性已能接近专门基于 ImageNet 训练的全监督模型。鉴于鲁棒性在实际应用尤其是关乎安全的关键领域至关重要，本篇论文借助包含7类自然分布转移、3类合成分布转移及11种对抗攻击的大规模鲁棒性基准，对 CLIP 模型进行了深入探索。实验揭示，相较于基于 ImageNet 的全监督模型，CLIP 在我们的基准测试中，尤其在面对合成分布转移和对抗攻击时，鲁棒性出现了显著下滑。进一步的数据重叠分析表明，CLIP 在自然分布转移下展现出的鲁棒性部分可归因于数据重叠现象。综上所述，本研究强调了全面评估模型鲁棒性的必要性，并指出提升零样本多模态模型鲁棒性的重要性和迫切性。

> Pre-training image representations from the raw text about images enables zero-shot vision transfer to downstream tasks. Through pre-training on millions of samples collected from the internet, multimodal foundation models, such as CLIP, produce state-of-the-art zero-shot results that often reach competitiveness with fully supervised methods without the need for task-specific training. Besides the encouraging performance on classification accuracy, it is reported that these models close the robustness gap by matching the performance of supervised models trained on ImageNet under natural distribution shift. Because robustness is critical to real-world applications, especially safety-critical ones, in this paper, we present a comprehensive evaluation based on a large-scale robustness benchmark covering 7 natural, 3 synthetic distribution shifts, and 11 adversarial attacks. We use CLIP as a pilot study. We show that CLIP leads to a significant robustness drop compared to supervised ImageNet models on our benchmark, especially under synthetic distribution shift and adversarial attacks. Furthermore, data overlap analysis suggests that the observed robustness under natural distribution shifts could be attributed, at least in part, to data overlap. In summary, our evaluation shows a comprehensive evaluation of robustness is necessary; and there is a significant need to improve the robustness of zero-shot multimodal models.

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x1.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x2.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x3.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x4.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x5.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x6.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x7.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x3.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x8.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x9.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x10.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x3.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x11.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x12.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x3.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x13.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x14.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x15.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x16.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x17.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x18.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x19.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x20.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x21.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x3.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x22.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x23.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x3.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x24.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x25.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x26.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x27.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x28.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x29.png)

![本研究作为一项先导性探索，致力于对多模态基础模型在零样本条件下的鲁棒性进行基准评估。](../../../paper_images/2403.10499/x30.png)

[Arxiv](https://arxiv.org/abs/2403.10499)