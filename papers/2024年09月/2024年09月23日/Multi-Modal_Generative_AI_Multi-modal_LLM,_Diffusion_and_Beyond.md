# 多模态生成式 AI：探索多模态 LLM、扩散技术及其他前沿领域

发布时间：2024年09月23日

`LLM理论` `人工智能` `计算机视觉`

> Multi-Modal Generative AI: Multi-modal LLM, Diffusion and Beyond

# 摘要

> 多模态生成式AI在学术界和工业界备受瞩目。其中，GPT-4V等MLLM展示了强大的多模态理解能力，而Sora等扩散模型则在视觉生成方面表现出色。这引发了一个问题：能否构建一个既能理解又能生成的统一模型？本文首先详细探讨了MLLM和扩散模型的概率建模、架构设计及应用。接着，我们讨论了统一模型应采用自回归还是扩散建模，以及密集架构或MoE架构的选择。此外，我们提出了构建统一模型的几种策略，并分析了其优缺点。最后，我们总结了现有的大规模多模态数据集，并展望了未来多模态生成式AI的发展方向。

> Multi-modal generative AI has received increasing attention in both academia and industry. Particularly, two dominant families of techniques are: i) The multi-modal large language model (MLLM) such as GPT-4V, which shows impressive ability for multi-modal understanding; ii) The diffusion model such as Sora, which exhibits remarkable multi-modal powers, especially with respect to visual generation. As such, one natural question arises: Is it possible to have a unified model for both understanding and generation? To answer this question, in this paper, we first provide a detailed review of both MLLM and diffusion models, including their probabilistic modeling procedure, multi-modal architecture design, and advanced applications to image/video large language models as well as text-to-image/video generation. Then, we discuss the two important questions on the unified model: i) whether the unified model should adopt the auto-regressive or diffusion probabilistic modeling, and ii) whether the model should utilize a dense architecture or the Mixture of Experts(MoE) architectures to better support generation and understanding, two objectives. We further provide several possible strategies for building a unified model and analyze their potential advantages and disadvantages. We also summarize existing large-scale multi-modal datasets for better model pretraining in the future. To conclude the paper, we present several challenging future directions, which we believe can contribute to the ongoing advancement of multi-modal generative AI.

[Arxiv](https://arxiv.org/abs/2409.14993)