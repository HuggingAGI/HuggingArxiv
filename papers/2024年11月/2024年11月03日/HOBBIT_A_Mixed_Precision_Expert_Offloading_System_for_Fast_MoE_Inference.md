# HOBBIT ：一个用于快速 MoE 推理的混合精度专家卸载系统

发布时间：2024年11月03日

`LLM应用` `语言模型` `边缘设备`

> HOBBIT: A Mixed Precision Expert Offloading System for Fast MoE Inference

# 摘要

> 在大型语言模型（LLMs）时代，专家混合（MoE）架构优势显著，既能增强能力，又能降低推理成本。但由于内存需求大，在内存受限的边缘设备上部署基于MoE的LLMs颇具挑战。现有的专家卸载方法虽能缓解内存需求，却常带来较高的专家加载成本或影响模型准确性。我们推出了HOBBIT，这是一个混合精度专家卸载系统，能实现灵活高效的MoE推理。我们的关键发现是，用低精度版本动态替换不太关键的缓存未命中专家，能在保证模型准确性的同时大幅降低专家加载延迟。HOBBIT引入了三项创新技术，对应MoE计算的自然层次结构：（1）令牌级动态专家加载机制；（2）层级自适应专家预取技术；（3）序列级多维专家缓存策略。这些创新充分发挥了混合精度专家推理的优势。在知名的LLM推理框架Llama.cpp基础上实现HOBBIT后，我们用不同边缘设备上的代表性MoE模型对其性能进行了评估。结果显示，与最先进的MoE卸载系统相比，HOBBIT在解码方面的速度最高提升了9.93倍。

> The Mixture-of-Experts (MoE) architecture has demonstrated significant advantages in the era of Large Language Models (LLMs), offering enhanced capabilities with reduced inference costs. However, deploying MoE-based LLMs on memoryconstrained edge devices remains challenging due to their substantial memory requirements. While existing expertoffloading methods alleviate the memory requirements, they often incur significant expert-loading costs or compromise model accuracy. We present HOBBIT, a mixed precision expert offloading system to enable flexible and efficient MoE inference. Our key insight is that dynamically replacing less critical cache-miss experts with low precision versions can substantially reduce expert-loading latency while preserving model accuracy. HOBBIT introduces three innovative techniques that map the natural hierarchy of MoE computation: (1) a token-level dynamic expert loading mechanism, (2) a layer-level adaptive expert prefetching technique, and (3) a sequence-level multidimensional expert caching policy. These innovations fully leverage the benefits of mixedprecision expert inference. By implementing HOBBIT on top of the renowned LLM inference framework Llama.cpp, we evaluate its performance across different edge devices with representative MoE models. The results demonstrate that HOBBIT achieves up to a 9.93x speedup in decoding compared to state-of-the-art MoE offloading systems.

[Arxiv](https://arxiv.org/abs/2411.01433)