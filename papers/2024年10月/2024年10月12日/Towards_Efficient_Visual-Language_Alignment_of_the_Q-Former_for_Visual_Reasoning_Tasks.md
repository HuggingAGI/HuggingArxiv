# 探索 Q-Former 在视觉推理任务中视觉与语言对齐的高效路径

发布时间：2024年10月12日

`LLM应用` `人工智能` `计算机视觉`

> Towards Efficient Visual-Language Alignment of the Q-Former for Visual Reasoning Tasks

# 摘要

> 近期，大型语言模型通过引入多模态对齐的额外编码器，显著提升了视觉推理能力。尽管 Q-Former 作为多模态对齐的通用编码器已被广泛应用，但其高效训练和组件分析的研究仍显不足。本研究利用 InstructBLIP 和 ScienceQA、IconQA 等视觉推理基准，探讨了 Q-Former 的参数高效微调 (PEFT) 效果。结果显示，PEFT 仅需不到 2% 的可训练参数，即可达到与全面微调相当的性能。此外，通过 AdaLoRA 动态调整参数预算，我们分析了 Q-Former 各子层在不同基准测试中的重要性。研究发现，自注意力层在视觉-语言推理任务中尤为关键，而 FFN 层的重要性则与任务的视觉-语言模式复杂性密切相关。相关代码已公开于 https://github.com/AttentionX/InstructBLIP_PEFT。

> Recent advancements in large language models have demonstrated enhanced capabilities in visual reasoning tasks by employing additional encoders for aligning different modalities. While the Q-Former has been widely used as a general encoder for aligning several modalities including image, video, audio, and 3D with large language models, previous works on its efficient training and the analysis of its individual components have been limited. In this work, we investigate the effectiveness of parameter efficient fine-tuning (PEFT) the Q-Former using InstructBLIP with visual reasoning benchmarks ScienceQA and IconQA. We observe that applying PEFT to the Q-Former achieves comparable performance to full fine-tuning using under 2% of the trainable parameters. Additionally, we employ AdaLoRA for dynamic parameter budget reallocation to examine the relative importance of the Q-Former's sublayers with 4 different benchmarks. Our findings reveal that the self-attention layers are noticeably more important in perceptual visual-language reasoning tasks, and relative importance of FFN layers depends on the complexity of visual-language patterns involved in tasks. The code is available at https://github.com/AttentionX/InstructBLIP_PEFT.

[Arxiv](https://arxiv.org/abs/2410.09489)