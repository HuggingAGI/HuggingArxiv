# 改进视觉语言模型的思维链推理

发布时间：2024年10月21日

`LLM应用` `视觉语言模型`

> Improve Vision Language Model Chain-of-thought Reasoning

# 摘要

> 摘要：在视觉语言模型（VLMs）中的思维链（CoT）推理对于提高可解释性和可信度至关重要。然而，当前的训练方法缺乏强大的 CoT 推理数据，依赖于以短注释和极少理由为主导的数据集。在这项工作中，我们表明在短答案上训练 VLM 不能很好地推广到需要更详细响应的推理任务。为了解决这个问题，我们提出了一个双重方法。首先，我们从 GPT-4o 模型中提取理由来丰富训练数据并微调 VLM，提高它们的 CoT 性能。其次，我们应用强化学习进一步校准推理质量。具体来说，我们通过将模型生成的推理链的预测与注释的短答案进行比较，构建模型生成的推理链的正（正确）和负（错误）对。使用这个成对数据，我们应用直接偏好优化算法来改进模型的推理能力。我们的实验表明，在基准数据集上的 CoT 推理有显著改进，并且对直接答案预测也有更好的泛化能力。这项工作强调了在训练中纳入详细理由和利用强化学习来加强 VLM 的推理能力的重要性。

> 
Abstract:Chain-of-thought (CoT) reasoning in vision language models (VLMs) is crucial for improving interpretability and trustworthiness. However, current training recipes lack robust CoT reasoning data, relying on datasets dominated by short annotations with minimal rationales. In this work, we show that training VLM on short answers does not generalize well to reasoning tasks that require more detailed responses. To address this, we propose a two-fold approach. First, we distill rationales from GPT-4o model to enrich the training data and fine-tune VLMs, boosting their CoT performance. Second, we apply reinforcement learning to further calibrate reasoning quality. Specifically, we construct positive (correct) and negative (incorrect) pairs of model-generated reasoning chains, by comparing their predictions with annotated short answers. Using this pairwise data, we apply the Direct Preference Optimization algorithm to refine the model's reasoning abilities. Our experiments demonstrate significant improvements in CoT reasoning on benchmark datasets and better generalization to direct answer prediction as well. This work emphasizes the importance of incorporating detailed rationales in training and leveraging reinforcement learning to strengthen the reasoning capabilities of VLMs.
    

[Arxiv](https://arxiv.org/pdf/2410.16198)