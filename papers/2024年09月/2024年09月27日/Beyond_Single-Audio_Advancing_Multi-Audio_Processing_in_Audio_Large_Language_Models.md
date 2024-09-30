# 超越单一音频，迈向音频大型语言模型中的多音频处理新境界

发布时间：2024年09月27日

`LLM应用` `音频处理` `人工智能`

> Beyond Single-Audio: Advancing Multi-Audio Processing in Audio Large Language Models

# 摘要

> 近期，多种音频-LLM（ALLM）被开发用于单一模型处理多重音频任务。然而，现有评估多聚焦于单一音频任务，而实际应用常需处理多音频流。为此，我们首创了多音频评估（MAE）基准，涵盖11项多音频任务的20个数据集，涉及语音与声音场景。实验显示，尽管ALLM在处理单音频时表现优异，但在多音频场景中却显不足。因此，我们提出了多音频-LLM（MALLM），通过判别学习在合成数据上捕捉多音频间的上下文。结果表明，MALLM在所有基线上表现卓越，且无需人工标注即可高效利用合成数据。MALLM不仅开启了ALLM的多音频处理新纪元，更让我们向机器复制人类听觉能力迈进了一大步。

> Various audio-LLMs (ALLMs) have been explored recently for tackling different audio tasks simultaneously using a single, unified model. While existing evaluations of ALLMs primarily focus on single-audio tasks, real-world applications often involve processing multiple audio streams simultaneously. To bridge this gap, we propose the first multi-audio evaluation (MAE) benchmark that consists of 20 datasets from 11 multi-audio tasks encompassing both speech and sound scenarios. Comprehensive experiments on MAE demonstrate that the existing ALLMs, while being powerful in comprehending primary audio elements in individual audio inputs, struggling to handle multi-audio scenarios. To this end, we propose a novel multi-audio-LLM (MALLM) to capture audio context among multiple similar audios using discriminative learning on our proposed synthetic data. The results demonstrate that the proposed MALLM outperforms all baselines and achieves high data efficiency using synthetic data without requiring human annotations. The proposed MALLM opens the door for ALLMs towards multi-audio processing era and brings us closer to replicating human auditory capabilities in machines.

[Arxiv](https://arxiv.org/abs/2409.18680)