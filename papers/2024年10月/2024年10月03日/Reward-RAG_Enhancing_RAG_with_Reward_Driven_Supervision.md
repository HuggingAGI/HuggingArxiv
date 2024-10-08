# Reward-RAG：以奖励驱动的方式提升 RAG 的性能

发布时间：2024年10月03日

`RAG` `人工智能`

> Reward-RAG: Enhancing RAG with Reward Driven Supervision

# 摘要

> 本文介绍了一种名为 Reward-RAG 的创新方法，通过奖励驱动的监督机制提升 Retrieval-Augmented Generation (RAG) 模型。与以往依赖外部知识检索的 RAG 方法不同，我们利用 CriticGPT 训练特定领域的奖励模型，从而使检索信息更贴合实际需求。该模型生成的合成数据集进一步微调 RAG 编码器，使其输出更符合人类偏好。这种方法的灵活性使其能广泛应用于不同领域。我们在多领域的公开基准上测试了 Reward-RAG，并展示了其显著优于现有技术的性能提升。这些成果表明，结合奖励模型与 RAG 有望大幅提升自然语言生成任务的效果。

> In this paper, we introduce Reward-RAG, a novel approach designed to enhance the Retrieval-Augmented Generation (RAG) model through Reward-Driven Supervision. Unlike previous RAG methodologies, which focus on training language models (LMs) to utilize external knowledge retrieved from external sources, our method adapts retrieval information to specific domains by employing CriticGPT to train a dedicated reward model. This reward model generates synthesized datasets for fine-tuning the RAG encoder, aligning its outputs more closely with human preferences. The versatility of our approach allows it to be effectively applied across various domains through domain-specific fine-tuning. We evaluate Reward-RAG on publicly available benchmarks from multiple domains, comparing it to state-of-the-art methods. Our experimental results demonstrate significant improvements in performance, highlighting the effectiveness of Reward-RAG in improving the relevance and quality of generated responses. These findings underscore the potential of integrating reward models with RAG to achieve superior outcomes in natural language generation tasks.

[Arxiv](https://arxiv.org/abs/2410.03780)