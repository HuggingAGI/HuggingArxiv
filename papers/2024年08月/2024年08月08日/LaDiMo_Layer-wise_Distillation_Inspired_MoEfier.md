# LaDiMo：灵感源自层级蒸馏的 MoEfier

发布时间：2024年08月08日

`LLM理论` `人工智能`

> LaDiMo: Layer-wise Distillation Inspired MoEfier

# 摘要

> 大型语言模型的兴起虽然革新了自然语言处理，但其复杂性也带来了高昂的训练成本和环境压力。稀疏的Mixture-of-Experts（MoE）模型因此成为替代密集模型的热门选择。鉴于直接训练MoE模型的成本过高，我们提出了一种名为LaDiMo的新算法，它能将非MoE的Transformer模型高效转换为MoE模型，且成本极低。LaDiMo通过知识蒸馏技术压缩模型，快速恢复性能，并引入自适应路由器优化推理效率。实验证明，使用LaDiMo将LLaMA2-7B模型转换为MoE模型，仅需100K个令牌，就能减少20%以上的激活参数，同时保持模型准确性。这一创新方法为MoE模型的构建与部署提供了灵活且高效的途径。

> The advent of large language models has revolutionized natural language processing, but their increasing complexity has led to substantial training costs, resource demands, and environmental impacts. In response, sparse Mixture-of-Experts (MoE) models have emerged as a promising alternative to dense models. Since training MoE models from scratch can be prohibitively expensive, recent studies have explored leveraging knowledge from pre-trained non-MoE models. However, existing approaches have limitations, such as requiring significant hardware resources and data. We propose a novel algorithm, LaDiMo, which efficiently converts a Transformer-based non-MoE model into a MoE model with minimal additional training cost. LaDiMo consists of two stages: layer-wise expert construction and routing policy decision. By harnessing the concept of Knowledge Distillation, we compress the model and rapidly recover its performance. Furthermore, we develop an adaptive router that optimizes inference efficiency by profiling the distribution of routing weights and determining a layer-wise policy that balances accuracy and latency. We demonstrate the effectiveness of our method by converting the LLaMA2-7B model to a MoE model using only 100K tokens, reducing activated parameters by over 20% while keeping accuracy. Our approach offers a flexible and efficient solution for building and deploying MoE models.

[Arxiv](https://arxiv.org/abs/2408.04278)