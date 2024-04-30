# AutoMix：智能融合语言模型，实现自动混编

发布时间：2024年03月20日

`LLM应用` `云计算`

> AutoMix: Automatically Mixing Language Models

# 摘要

> 如今，多种规模和配置的大型语言模型（LLMs）可通过云API轻松获取。尽管选择众多，但要高效利用这些资源以优化计算成本和性能并非易事。本研究介绍了AutoMix，这是一种智能路由查询至更大型语言模型的方法，依据是较小语言模型输出的正确性。AutoMix的精髓在于一种少量样本自我验证机制，它能够在无需训练的情况下评估自身输出的可信度。鉴于自我验证可能存在误差，AutoMix采用了元验证器来进一步提升评估的精确度。通过在五个基于上下文的推理数据集上的测试，我们发现AutoMix在提升性价比方面，相比现有基准提升了高达86%的增量效益。相关代码和数据已在 https://github.com/automix-llm/automix 上公开。

> Large language models (LLMs) are now available from cloud API providers in various sizes and configurations. While this diversity offers a broad spectrum of choices, effectively leveraging the options to optimize computational cost and performance remains challenging. In this work, we present AutoMix, an approach that strategically routes queries to larger LMs, based on the approximate correctness of outputs from a smaller LM. Central to AutoMix is a few-shot self-verification mechanism, which estimates the reliability of its own outputs without requiring training. Given that verifications can be noisy, we employ a meta-verifier in AutoMix to refine the accuracy of these assessments. Our experiments using LLAMA2-13B and GPT-4, on five context-grounded reasoning datasets demonstrate that AutoMix surpasses established baselines, improving the incremental benefit per cost by up to 86%. Our code and data are available at https://github.com/automix-llm/automix.

[Arxiv](https://arxiv.org/abs/2310.12963)