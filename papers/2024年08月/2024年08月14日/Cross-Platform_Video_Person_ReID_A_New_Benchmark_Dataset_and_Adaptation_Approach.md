# 跨平台视频人物重识别：引入新基准数据集与适应策略

发布时间：2024年08月14日

`Agent` `安防监控` `人工智能`

> Cross-Platform Video Person ReID: A New Benchmark Dataset and Adaptation Approach

# 摘要

> 本文中，我们创建了名为G2A-VReID的大规模基准数据集，专为地面到空中的视频人物再识别设计，包含185,907张图像和5,576个轨迹片段，涵盖2,788个独特身份。这是首个针对此类场景的视频ReID数据集，特点包括剧烈的视角变化、大量标注身份、丰富户外场景及巨大分辨率差异。我们还提出了一种新颖的跨平台ReID方法VSLA-CLIP，通过视觉-语言模型CLIP将视觉对齐问题转化为视觉-语义对齐，并采用高效的Video Set-Level-Adapter模块，使图像基础模型适应视频ReID任务。为缩小平台间差异，设计了平台桥接提示以优化视觉特征对齐。实验表明，我们的方法在所有现有视频ReID数据集及新提出的G2A-VReID数据集上均表现卓越。

> In this paper, we construct a large-scale benchmark dataset for Ground-to-Aerial Video-based person Re-Identification, named G2A-VReID, which comprises 185,907 images and 5,576 tracklets, featuring 2,788 distinct identities. To our knowledge, this is the first dataset for video ReID under Ground-to-Aerial scenarios. G2A-VReID dataset has the following characteristics: 1) Drastic view changes; 2) Large number of annotated identities; 3) Rich outdoor scenarios; 4) Huge difference in resolution. Additionally, we propose a new benchmark approach for cross-platform ReID by transforming the cross-platform visual alignment problem into visual-semantic alignment through vision-language model (i.e., CLIP) and applying a parameter-efficient Video Set-Level-Adapter module to adapt image-based foundation model to video ReID tasks, termed VSLA-CLIP. Besides, to further reduce the great discrepancy across the platforms, we also devise the platform-bridge prompts for efficient visual feature alignment. Extensive experiments demonstrate the superiority of the proposed method on all existing video ReID datasets and our proposed G2A-VReID dataset.

![跨平台视频人物重识别：引入新基准数据集与适应策略](../../../paper_images/2408.07500/x1.png)

![跨平台视频人物重识别：引入新基准数据集与适应策略](../../../paper_images/2408.07500/x2.png)

![跨平台视频人物重识别：引入新基准数据集与适应策略](../../../paper_images/2408.07500/x3.png)

![跨平台视频人物重识别：引入新基准数据集与适应策略](../../../paper_images/2408.07500/x4.png)

[Arxiv](https://arxiv.org/abs/2408.07500)