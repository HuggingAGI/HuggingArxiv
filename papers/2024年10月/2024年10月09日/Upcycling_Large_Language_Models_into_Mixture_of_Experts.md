# 将大型语言模型升级为专家混合模型

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Upcycling Large Language Models into Mixture of Experts

# 摘要

> 将预训练的密集语言模型升级为稀疏的专家混合 (MoE) 模型，是提升模型容量的有效途径。然而，大规模升级的最佳策略尚不明朗。我们深入研究了升级方法和超参数，针对十亿参数规模的语言模型。我们创新性地提出了“虚拟组”初始化方案和权重缩放方法，助力模型向细粒度 MoE 架构升级。实验表明，升级效果优于继续密集训练。此外，我们发现 softmax-then-topK 专家路由策略更优，且更高粒度的 MoE 有助于提升准确性。最终，我们将 Nemotron-4 15B 升级至 1T 标记，并与连续训练的版本对比，升级模型在 MMLU 上达到了 67.6%，优于连续训练的 65.3%。我们的研究为 MoE 语言模型的升级提供了宝贵经验和最佳实践。

> Upcycling pre-trained dense language models into sparse mixture-of-experts (MoE) models is an efficient approach to increase the model capacity of already trained models. However, optimal techniques for upcycling at scale remain unclear. In this work, we conduct an extensive study of upcycling methods and hyperparameters for billion-parameter scale language models. We propose a novel "virtual group" initialization scheme and weight scaling approach to enable upcycling into fine-grained MoE architectures. Through ablations, we find that upcycling outperforms continued dense model training. In addition, we show that softmax-then-topK expert routing improves over topK-then-softmax approach and higher granularity MoEs can help improve accuracy. Finally, we upcycled Nemotron-4 15B on 1T tokens and compared it to a continuously trained version of the same model on the same 1T tokens: the continuous trained model achieved 65.3% MMLU, whereas the upcycled model achieved 67.6%. Our results offer insights and best practices to effectively leverage upcycling for building MoE language models.

[Arxiv](https://arxiv.org/abs/2410.07524)