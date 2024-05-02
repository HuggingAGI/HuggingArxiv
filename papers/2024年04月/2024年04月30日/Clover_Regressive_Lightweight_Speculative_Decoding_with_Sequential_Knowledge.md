# Clover：一种结合顺序知识，采用回归式轻量级推测性解码的方法。

发布时间：2024年04月30日

`LLM理论` `计算效率`

> Clover: Regressive Lightweight Speculative Decoding with Sequential Knowledge

# 摘要

> 大型语言模型（LLMs）因自回归解码需求与现代GPU设计不匹配，导致效率不高。具体而言，为了计算，必须通过有限的内存带宽将数十亿至数万亿参数加载到GPU缓存中，但实际只处理一小部分令牌，导致GPU在内存传输上耗费的时间远超计算。近期，一种名为并行解码的推测性解码算法因其在生成任务中的显著效率提升而日益受到青睐。该算法通过增加额外的解码头，使得大型模型能够同时预测多个后续令牌，并在单一解码步骤中对这些候选续接进行验证。然而，这种方法与预训练阶段的下一个令牌预测目标有所偏离，从而降低了候选令牌的命中率。本文提出了一种名为Clover的新型推测性解码算法，它将序列知识融入并行解码流程中，有效提升了投机者的命中率及整体效率。Clover通过回归连接传递预推测令牌的序列知识，并利用注意力解码器整合这些推测令牌。此外，Clover还引入了一个增强模块，优化隐藏状态以更好地适应推测生成而非单一令牌预测。实验结果显示，Clover在Baichuan-Small数据集上的性能提升高达91%，在Baichuan-Large数据集上提升高达146%，并且在两个数据集上均超过了之前领先的Medusa方法，分别高出37%和57%。

> Large language models (LLMs) suffer from low efficiency as the mismatch between the requirement of auto-regressive decoding and the design of most contemporary GPUs. Specifically, billions to trillions of parameters must be loaded to the GPU cache through its limited memory bandwidth for computation, but only a small batch of tokens is actually computed. Consequently, the GPU spends most of its time on memory transfer instead of computation. Recently, parallel decoding, a type of speculative decoding algorithms, is becoming more popular and has demonstrated impressive efficiency improvement in generation. It introduces extra decoding heads to large models, enabling them to predict multiple subsequent tokens simultaneously and verify these candidate continuations in a single decoding step. However, this approach deviates from the training objective of next token prediction used during pre-training, resulting in a low hit rate for candidate tokens. In this paper, we propose a new speculative decoding algorithm, Clover, which integrates sequential knowledge into the parallel decoding process. This enhancement improves the hit rate of speculators and thus boosts the overall efficiency. Clover transmits the sequential knowledge from pre-speculated tokens via the Regressive Connection, then employs an Attention Decoder to integrate these speculated tokens. Additionally, Clover incorporates an Augmenting Block that modifies the hidden states to better align with the purpose of speculative generation rather than next token prediction. The experiment results demonstrate that Clover outperforms the baseline by up to 91% on Baichuan-Small and 146% on Baichuan-Large, respectively, and exceeds the performance of the previously top-performing method, Medusa, by up to 37% on Baichuan-Small and 57% on Baichuan-Large, respectively.

[Arxiv](https://arxiv.org/abs/2405.00263)