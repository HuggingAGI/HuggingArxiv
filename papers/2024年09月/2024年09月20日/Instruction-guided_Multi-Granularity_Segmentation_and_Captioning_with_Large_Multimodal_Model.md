# 大型多模态模型在指令引导下实现多粒度分割与标题生成

发布时间：2024年09月20日

`LLM应用` `计算机视觉` `人工智能`

> Instruction-guided Multi-Granularity Segmentation and Captioning with Large Multimodal Model

# 摘要

> 大型多模态模型 (LMMs) 通过扩展大型语言模型取得了显著进展。最新进展展示了 LMMs 通过整合分割模型生成密集像素级分割的能力。然而，现有工作的文本响应和分割掩码仍停留在实例级别，细粒度理解和分割能力有限。为此，我们引入了多粒度大型多模态模型 (MGLMM)，它能根据用户指令无缝调整分割和标注 (SegCap) 的粒度，从全景到细粒度。我们将这一新任务命名为多粒度分割和标注 (MGSC)。为填补 MGSC 任务的基准空白，我们使用自定义的自动化标注流水线建立了包含多粒度对齐掩码和标注的基准，包含 10K 张图像和超过 30K 个图像-问题对。此外，我们提出了一种新的统一 SegCap 数据格式，以统一异构分割数据集，促进多任务训练中对象概念与视觉特征的关联。实验表明，MGLMM 在八个以上下游任务中表现出色，并在多个任务中达到最先进性能。MGLMM 的出色表现和多功能性预示着其对推进多模态研究的巨大潜力。

> Large Multimodal Models (LMMs) have achieved significant progress by extending large language models. Building on this progress, the latest developments in LMMs demonstrate the ability to generate dense pixel-wise segmentation through the integration of segmentation models.Despite the innovations, the textual responses and segmentation masks of existing works remain at the instance level, showing limited ability to perform fine-grained understanding and segmentation even provided with detailed textual cues.To overcome this limitation, we introduce a Multi-Granularity Large Multimodal Model (MGLMM), which is capable of seamlessly adjusting the granularity of Segmentation and Captioning (SegCap) following user instructions, from panoptic SegCap to fine-grained SegCap. We name such a new task Multi-Granularity Segmentation and Captioning (MGSC). Observing the lack of a benchmark for model training and evaluation over the MGSC task, we establish a benchmark with aligned masks and captions in multi-granularity using our customized automated annotation pipeline. This benchmark comprises 10K images and more than 30K image-question pairs. We will release our dataset along with the implementation of our automated dataset annotation pipeline for further research.Besides, we propose a novel unified SegCap data format to unify heterogeneous segmentation datasets; it effectively facilitates learning to associate object concepts with visual features during multi-task training. Extensive experiments demonstrate that our MGLMM excels at tackling more than eight downstream tasks and achieves state-of-the-art performance in MGSC, GCG, image captioning, referring segmentation, multiple and empty segmentation, and reasoning segmentation tasks. The great performance and versatility of MGLMM underscore its potential impact on advancing multimodal research.

[Arxiv](https://arxiv.org/abs/2409.13407)