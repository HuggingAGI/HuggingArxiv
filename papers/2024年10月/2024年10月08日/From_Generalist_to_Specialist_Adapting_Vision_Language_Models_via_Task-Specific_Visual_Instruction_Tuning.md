# 从全能到专精：通过任务导向的视觉指令微调，让视觉语言模型更上一层楼

发布时间：2024年10月08日

`LLM应用` `计算机视觉`

> From Generalist to Specialist: Adapting Vision Language Models via Task-Specific Visual Instruction Tuning

# 摘要

> 大型视觉语言模型 (VLMs) 结合了语言模型和视觉编码器，展现出广泛的应用潜力。然而，由于预训练与微调之间的领域差异，VLMs 在特定任务中的表现往往不尽如人意。为此，我们推出了 VITask 框架，通过整合特定任务模型 (TSMs)，显著提升了 VLMs 的适应性。VITask 采用三大策略：示例提示 (EP)、响应分布对齐 (RDA) 和对比响应调整 (CRT)，通过优化响应分布，大幅提升 VLMs 的特定任务性能。EP 使 TSM 特征能够引导 VLMs，而 RDA 则让 VLMs 在无 TSM 的情况下也能灵活适应，通过学习示例提示模型。CRT 进一步优化了正确图像-响应对的排序，有效减少不期望响应的生成。实验结果显示，VITask 在 12 个医疗诊断数据集上超越了普通指令调优的 VLMs 和 TSMs，充分展现了其整合两种模型优势的能力。此外，VITask 还具备灵活的 TSM 集成和对不完整指令的强大鲁棒性，成为特定任务 VLM 调优的理想选择。代码已公开，详见 https://github.com/baiyang4/VITask。

> Large vision language models (VLMs) combine large language models with vision encoders, demonstrating promise across various tasks. However, they often underperform in task-specific applications due to domain gaps between pre-training and fine-tuning. We introduce VITask, a novel framework that enhances task-specific adaptability of VLMs by integrating task-specific models (TSMs). VITask employs three key strategies: exemplar prompting (EP), response distribution alignment (RDA), and contrastive response tuning (CRT) to improve the task-specific performance of VLMs by adjusting their response distributions. EP allows TSM features to guide VLMs, while RDA enables VLMs to adapt without TSMs during inference by learning from exemplar-prompted models. CRT further optimizes the ranking of correct image-response pairs, thereby reducing the risk of generating undesired responses. Experiments on 12 medical diagnosis datasets across 9 imaging modalities show that VITask outperforms both vanilla instruction-tuned VLMs and TSMs, showcasing its ability to integrate complementary features from both models effectively. Additionally, VITask offers practical advantages such as flexible TSM integration and robustness to incomplete instructions, making it a versatile and efficient solution for task-specific VLM tuning. Our code are available at https://github.com/baiyang4/VITask.

[Arxiv](https://arxiv.org/abs/2410.06456)