# SAVEn-Vid：用于长视频情境中强化理解的协同式视听融合

发布时间：2024年11月25日

`LLM应用` `视频分析` `语言模型`

> SAVEn-Vid: Synergistic Audio-Visual Integration for Enhanced Understanding in Long Video Context

# 摘要

> 人们一直致力于探索用于视频分析的大型语言模型（Video-LLMs），尤其是在长视频的理解与诠释方面。然而，现有的 Video-LLMs 在有效整合长视频中丰富多样的固有视听信息时仍面临挑战，而这对于全面理解至关重要。于是就有了这样一个问题：我们怎样借助嵌入的视听信息来强化对长视频的理解？为此，（i）我们推出了 SAVEn-Vid，这是首个包含超 58,000 个视听指令的长视听视频数据集。（ii）从模型角度出发，我们提出了一个具有时间感知能力的视听大型语言模型（AV-LLM）——SAVEnVideo，它在 SAVEn-Vid 上进行了微调。（iii）另外，我们还给出了 AVBench，这是一个包含 2,500 个问答的基准，用于评估模型在长视频增强视听理解任务方面的能力，考验它们处理复杂视听交互的水平。在 AVBench 上的实验揭示了当前 AV-LLMs 的局限性。实验还显示，在零样本长视频任务（Video-MME）中，SAVEnVideo 比最佳的 Video-LLM 高出 3.61％；在零样本视听任务（Music-AVQA）里，超过领先的视听 LLM 1.29％。所以，在 7B 参数规模下，SAVEnVideo 能够实现最先进的性能。我们的数据集和代码在被接收后会在 https://ljungang.github.io/SAVEn-Vid/ 发布。

> Endeavors have been made to explore Large Language Models for video analysis (Video-LLMs), particularly in understanding and interpreting long videos. However, existing Video-LLMs still face challenges in effectively integrating the rich and diverse audio-visual information inherent in long videos, which is crucial for comprehensive understanding. This raises the question: how can we leverage embedded audio-visual information to enhance long video understanding? Therefore, (i) we introduce SAVEn-Vid, the first-ever long audio-visual video dataset comprising over 58k audio-visual instructions. (ii) From the model perspective, we propose a time-aware Audio-Visual Large Language Model (AV-LLM), SAVEnVideo, fine-tuned on SAVEn-Vid. (iii) Besides, we present AVBench, a benchmark containing 2,500 QAs designed to evaluate models on enhanced audio-visual comprehension tasks within long video, challenging their ability to handle intricate audio-visual interactions. Experiments on AVBench reveal the limitations of current AV-LLMs. Experiments also demonstrate that SAVEnVideo outperforms the best Video-LLM by 3.61% on the zero-shot long video task (Video-MME) and surpasses the leading audio-visual LLM by 1.29% on the zero-shot audio-visual task (Music-AVQA). Consequently, at the 7B parameter scale, SAVEnVideo can achieve state-of-the-art performance. Our dataset and code will be released at https://ljungang.github.io/SAVEn-Vid/ upon acceptance.

[Arxiv](https://arxiv.org/abs/2411.16213)