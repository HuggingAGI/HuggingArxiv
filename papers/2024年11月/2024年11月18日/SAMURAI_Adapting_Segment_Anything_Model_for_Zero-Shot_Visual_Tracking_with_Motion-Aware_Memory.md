# SAMURAI：为实现具有运动感知记忆的零样本视觉跟踪而对段任何模型进行调整

发布时间：2024年11月18日

`其他` `视觉对象跟踪` `计算机视觉`

> SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory

# 摘要

> 摘要：分段任意模型 2（SAM 2）在对象分割任务中表现卓越，然而在视觉对象跟踪领域却遭遇挑战，尤其是应对有快速移动或自我遮挡对象的拥挤场景时。再者，原模型中的固定窗口内存方式未考量用于为下一帧图像特征提供条件的内存质量，致使视频中出现错误传播。本文推出 SAMURAI，这是专为视觉对象跟踪精心打造的 SAM 2 增强版。借由将时间运动线索与所提的运动感知内存选择机制相融合，SAMURAI 能够有效预测对象运动并优化掩码选择，无需重新训练或微调就能达成强大且精准的跟踪。SAMURAI 实时运作，在各类基准数据集中展现出强劲的零样本性能，凸显其无需微调即可泛化的能力。在评估中，SAMURAI 较现有跟踪器在成功率和精度上有显著提升，在 LaSOT$_{	ext{ext}}$ 上的 AUC 增益达 7.1％，在 GOT-10k 上的 AO 增益为 3.5％。此外，和 LaSOT 上的完全监督方法相较，它取得了颇具竞争力的成果，彰显出其在复杂跟踪场景中的稳健性以及在动态环境中的实际应用潜力。相关代码和结果可在这个 https URL 获取。

> 
Abstract:The Segment Anything Model 2 (SAM 2) has demonstrated strong performance in object segmentation tasks but faces challenges in visual object tracking, particularly when managing crowded scenes with fast-moving or self-occluding objects. Furthermore, the fixed-window memory approach in the original model does not consider the quality of memories selected to condition the image features for the next frame, leading to error propagation in videos. This paper introduces SAMURAI, an enhanced adaptation of SAM 2 specifically designed for visual object tracking. By incorporating temporal motion cues with the proposed motion-aware memory selection mechanism, SAMURAI effectively predicts object motion and refines mask selection, achieving robust, accurate tracking without the need for retraining or fine-tuning. SAMURAI operates in real-time and demonstrates strong zero-shot performance across diverse benchmark datasets, showcasing its ability to generalize without fine-tuning. In evaluations, SAMURAI achieves significant improvements in success rate and precision over existing trackers, with a 7.1% AUC gain on LaSOT$_{\text{ext}}$ and a 3.5% AO gain on GOT-10k. Moreover, it achieves competitive results compared to fully supervised methods on LaSOT, underscoring its robustness in complex tracking scenarios and its potential for real-world applications in dynamic environments. Code and results are available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2411.11922)