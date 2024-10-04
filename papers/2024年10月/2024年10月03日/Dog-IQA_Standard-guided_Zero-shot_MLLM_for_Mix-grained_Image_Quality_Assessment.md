# Dog-IQA：一种标准引导的零-shot MLLM，专为混合粒度图像质量评估设计

发布时间：2024年10月03日

`LLM应用` `计算机视觉` `图像处理`

> Dog-IQA: Standard-guided Zero-shot MLLM for Mix-grained Image Quality Assessment

# 摘要

> 图像质量评估 (IQA) 是计算机视觉领域中衡量模型性能的黄金标准，但仍面临分布外泛化能力差和训练成本高的问题。为此，我们推出了 Dog-IQA，一种无需训练的零-shot 混合粒度 IQA 方法，充分利用了多模态大型语言模型 (MLLM) 的先验知识。为确保评分与人类感知一致，我们设计了基于 MLLM 的推理流程，模拟人类专家的判断。Dog-IQA 通过两种技术实现：一是依据 MLLM 行为模式客观评分，减少主观因素影响；二是综合考虑局部语义对象和整体图像，融合局部与全局信息。实验表明，Dog-IQA 在无需训练的方法中表现卓越，并在跨数据集场景中与基于训练的方法不相上下。代码和模型即将在 https://github.com/Kai-Liu001/Dog-IQA 发布。

> Image quality assessment (IQA) serves as the golden standard for all models' performance in nearly all computer vision fields. However, it still suffers from poor out-of-distribution generalization ability and expensive training costs. To address these problems, we propose Dog-IQA, a standard-guided zero-shot mix-grained IQA method, which is training-free and utilizes the exceptional prior knowledge of multimodal large language models (MLLMs). To obtain accurate IQA scores, namely scores consistent with humans, we design an MLLM-based inference pipeline that imitates human experts. In detail, Dog-IQA applies two techniques. First, Dog-IQA objectively scores with specific standards that utilize MLLM's behavior pattern and minimize the influence of subjective factors. Second, Dog-IQA comprehensively takes local semantic objects and the whole image as input and aggregates their scores, leveraging local and global information. Our proposed Dog-IQA achieves state-of-the-art (SOTA) performance compared with training-free methods, and competitive performance compared with training-based methods in cross-dataset scenarios. Our code and models will be available at https://github.com/Kai-Liu001/Dog-IQA.

[Arxiv](https://arxiv.org/abs/2410.02505)