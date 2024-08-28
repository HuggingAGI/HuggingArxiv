# 《羊驼中的曼巴》：提炼与加速混合模型

发布时间：2024年08月27日

`LLM应用` `人工智能` `计算机硬件`

> The Mamba in the Llama: Distilling and Accelerating Hybrid Models

# 摘要

> Mamba等线性RNN架构在语言建模中能与Transformer匹敌，且部署优势明显。我们探讨了将预训练Transformer模型转换为部署模型的挑战，并证明利用学术GPU资源，通过重用注意力层的线性投影权重，将大型Transformer蒸馏为线性RNN是可行的。这种混合模型在聊天基准测试中表现与原始Transformer相当，且在各类基准测试中超越了从头训练的Mamba模型。我们还开发了一种硬件感知的推测解码算法，显著提升了Mamba和混合模型的推理速度。最终，我们通过精简注意力层，在有限计算资源下实现了更高效的模型生成。我们的顶级模型在AlpacaEval 2上以29.61的胜率超越GPT-4，在MT-Bench上以7.35的胜率领先于最佳线性RNN模型。

> Linear RNN architectures, like Mamba, can be competitive with Transformer models in language modeling while having advantageous deployment characteristics. Given the focus on training large-scale Transformer models, we consider the challenge of converting these pretrained models for deployment. We demonstrate that it is feasible to distill large Transformers into linear RNNs by reusing the linear projection weights from attention layers with academic GPU resources. The resulting hybrid model, which incorporates a quarter of the attention layers, achieves performance comparable to the original Transformer in chat benchmarks and outperforms open-source hybrid Mamba models trained from scratch with trillions of tokens in both chat benchmarks and general benchmarks. Moreover, we introduce a hardware-aware speculative decoding algorithm that accelerates the inference speed of Mamba and hybrid models. Overall we show how, with limited computation resources, we can remove many of the original attention layers and generate from the resulting model more efficiently. Our top-performing model, distilled from Llama3-8B-Instruct, achieves a 29.61 length-controlled win rate on AlpacaEval 2 against GPT-4 and 7.35 on MT-Bench, surpassing the best instruction-tuned linear RNN model.

[Arxiv](https://arxiv.org/abs/2408.15237)