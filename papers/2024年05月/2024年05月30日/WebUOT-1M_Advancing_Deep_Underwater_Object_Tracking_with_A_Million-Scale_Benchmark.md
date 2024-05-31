# WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术

发布时间：2024年05月30日

`Agent

理由：这篇论文主要关注的是水下目标跟踪（UOT）任务，并提出了一个新的数据集WebUOT-1M以及一个全知识蒸馏框架来提升跟踪器的性能。这个工作更侧重于开发和优化特定环境下的跟踪算法，即水下环境，这通常是Agent领域的工作，因为Agent系统需要在这样的环境中进行自主决策和行动。虽然论文中提到了语言提示和视觉-语言跟踪，但这并不是论文的核心内容，而是作为提升跟踪器性能的一个方面。因此，这篇论文更适合归类为Agent。` `水下目标跟踪` `计算机视觉`

> WebUOT-1M: Advancing Deep Underwater Object Tracking with A Million-Scale Benchmark

# 摘要

> 水下目标跟踪（UOT）是识别水下视频中潜藏实体的关键任务，但现有数据集因规模和多样性不足而限制了算法的发展。为此，我们推出了WebUOT-1M，一个包含110万帧、覆盖408个目标类别的庞大基准，远超以往。通过精细的手动标注，我们确保了数据的高质量，并引入了语言提示，拓宽了应用如水下视觉-语言跟踪。然而，大多数跟踪器因露天环境设计而在水下表现不佳，且因数据限制难以优化。为此，我们创新性地提出了全知识蒸馏框架，有效转移露天知识至UOT，显著提升了性能。通过30个深度跟踪器的全面测试，WebUOT-1M不仅验证了其作为研究基准的价值，也为未来研究开辟了新天地。所有资源将公开，以促进UOT领域的进一步发展。

> Underwater object tracking (UOT) is a foundational task for identifying and tracing submerged entities in underwater video sequences. However, current UOT datasets suffer from limitations in scale, diversity of target categories and scenarios covered, hindering the training and evaluation of modern tracking algorithms. To bridge this gap, we take the first step and introduce WebUOT-1M, \ie, the largest public UOT benchmark to date, sourced from complex and realistic underwater environments. It comprises 1.1 million frames across 1,500 video clips filtered from 408 target categories, largely surpassing previous UOT datasets, \eg, UVOT400. Through meticulous manual annotation and verification, we provide high-quality bounding boxes for underwater targets. Additionally, WebUOT-1M includes language prompts for video sequences, expanding its application areas, \eg, underwater vision-language tracking. Most existing trackers are tailored for open-air environments, leading to performance degradation when applied to UOT due to domain gaps. Retraining and fine-tuning these trackers are challenging due to sample imbalances and limited real-world underwater datasets. To tackle these challenges, we propose a novel omni-knowledge distillation framework based on WebUOT-1M, incorporating various strategies to guide the learning of the student Transformer. To the best of our knowledge, this framework is the first to effectively transfer open-air domain knowledge to the UOT model through knowledge distillation, as demonstrated by results on both existing UOT datasets and the newly proposed WebUOT-1M. Furthermore, we comprehensively evaluate WebUOT-1M using 30 deep trackers, showcasing its value as a benchmark for UOT research by presenting new challenges and opportunities for future studies. The complete dataset, codes and tracking results, will be made publicly available.

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x1.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x2.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x3.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x4.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x5.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x6.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x7.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x8.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x9.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x10.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x11.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x12.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x13.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x14.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x15.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x16.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x17.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x18.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x19.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x20.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x21.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x22.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x23.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x24.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x25.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x26.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x27.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x28.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x29.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x30.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x31.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x32.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x33.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x34.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x35.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x36.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x37.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x38.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x39.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x40.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x41.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x42.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x43.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x44.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x45.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x46.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x47.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x48.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x49.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x50.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x51.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x52.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x53.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x54.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x55.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x56.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x57.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x58.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x59.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x60.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x61.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x62.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x63.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x64.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x65.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x66.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x67.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x68.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x69.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x70.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x71.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x72.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x73.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x74.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x75.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x76.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x77.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x78.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x79.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x80.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x81.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x82.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x83.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x84.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x85.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x86.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x87.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x88.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x89.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x90.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x91.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x92.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x93.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x94.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x95.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x96.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x97.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x98.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x99.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x100.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x101.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x102.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x103.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x104.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x105.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x106.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x107.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x108.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x109.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x110.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x111.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x112.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x113.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x114.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x115.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x116.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x117.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x118.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x119.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x120.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x121.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x122.png)

![WebUOT-1M：借助百万级基准，深度推进深海物体跟踪技术](../../../paper_images/2405.19818/x123.png)

[Arxiv](https://arxiv.org/abs/2405.19818)