# LLaVA-Critic：掌握多模态模型评估之道

发布时间：2024年10月03日

`LLM应用` `人工智能` `开源软件`

> LLaVA-Critic: Learning to Evaluate Multimodal Models

# 摘要

> 我们推出了 LLaVA-Critic，首个开源的大型多模态模型，专为评估各类多模态任务而设计。LLaVA-Critic 通过融合多样化评估标准和场景的高质量数据集进行训练。实验表明，它在两个关键领域表现出色：一是作为“LMM-as-a-Judge”，提供可靠评估分数，在多个基准测试中与 GPT 模型不相上下甚至更优；二是“偏好学习”，生成奖励信号，提升模型对齐能力。这项研究凸显了开源 LMM 在自我评估中的巨大潜力，为未来探索 LMM 的可扩展、超人类对齐反馈机制铺平了道路。

> We introduce LLaVA-Critic, the first open-source large multimodal model (LMM) designed as a generalist evaluator to assess performance across a wide range of multimodal tasks. LLaVA-Critic is trained using a high-quality critic instruction-following dataset that incorporates diverse evaluation criteria and scenarios. Our experiments demonstrate the model's effectiveness in two key areas: (1) LMM-as-a-Judge, where LLaVA-Critic provides reliable evaluation scores, performing on par with or surpassing GPT models on multiple evaluation benchmarks; and (2) Preference Learning, where it generates reward signals for preference learning, enhancing model alignment capabilities. This work underscores the potential of open-source LMMs in self-critique and evaluation, setting the stage for future research into scalable, superhuman alignment feedback mechanisms for LMMs.

[Arxiv](https://arxiv.org/abs/2410.02712)