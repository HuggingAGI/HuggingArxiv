# Video-STaR：通过自训练，视频指令调优可利用任意监督方式进行。

发布时间：2024年07月08日

`LLM应用` `视频处理` `人工智能`

> Video-STaR: Self-Training Enables Video Instruction Tuning with Any Supervision

# 摘要

> 大型视觉语言模型 (LVLMs) 的性能受其训练数据集的大小和质量影响。现有视频指令调优数据集因依赖于通过视频字幕生成问答对而缺乏多样性，多为描述性内容。同时，虽有许多标记视频数据集具备多样标签和监督，但其整合至 LVLMs 并非简单任务。为此，我们首创了增强推理的视频自训练方法 (Video-STaR)，它允许利用任何标记视频数据集进行指令调优。Video-STaR 通过在指令生成与微调间循环，不仅提升视频理解能力，还能使模型适应新下游任务。在生成阶段，模型提出答案后，仅保留含原始视频标签的答案进行再训练，以此利用现有视频标签作为弱监督。实验显示，Video-STaR 增强的 LVLMs 在一般视频问答中性能提升显著，如 TempCompass 性能提高 10%，在下游任务如 Kinetics700-QA 准确性提升 20%，FineDiving 动作质量评估提升 15%。

> The performance of Large Vision Language Models (LVLMs) is dependent on the size and quality of their training datasets. Existing video instruction tuning datasets lack diversity as they are derived by prompting large language models with video captions to generate question-answer pairs, and are therefore mostly descriptive. Meanwhile, many labeled video datasets with diverse labels and supervision exist - however, we find that their integration into LVLMs is non-trivial. Herein, we present Video Self-Training with augmented Reasoning (Video-STaR), the first video self-training approach. Video-STaR allows the utilization of any labeled video dataset for video instruction tuning. In Video-STaR, an LVLM cycles between instruction generation and finetuning, which we show (I) improves general video understanding and (II) adapts LVLMs to novel downstream tasks with existing supervision. During generation, an LVLM is prompted to propose an answer. The answers are then filtered only to those that contain the original video labels, and the LVLM is then re-trained on the generated dataset. By only training on generated answers that contain the correct video labels, Video-STaR utilizes these existing video labels as weak supervision for video instruction tuning. Our results demonstrate that Video-STaR-enhanced LVLMs exhibit improved performance in (I) general video QA, where TempCompass performance improved by 10%, and (II) on downstream tasks, where Video-STaR improved Kinetics700-QA accuracy by 20% and action quality assessment on FineDiving by 15%.

[Arxiv](https://arxiv.org/abs/2407.06189)