# ParGo：融合视觉与语言，兼顾局部与全局视角

发布时间：2024年08月23日

`LLM应用` `人工智能` `计算机视觉`

> ParGo: Bridging Vision-Language with Partial and Global Views

# 摘要

> 本研究推出 ParGo，一种创新的部分-全局投影仪，专为连接多模态大型语言模型 (MLLMs) 中的视觉与语言模态而设计。不同于以往依赖全局注意力机制的投影仪，ParGo 通过融合全局与局部视角，有效缩小了独立预训练视觉编码器与语言模型间的表示鸿沟，避免了过度关注显著区域的问题。为支持 ParGo 的训练，我们构建了 ParGoCap-1M-PT 数据集，包含百万级高质量图像与描述配对。实验结果显示，ParGo 在多个 MLLM 基准测试中表现卓越，尤其在视觉与语言模态对齐方面领先。相较于传统 Q-Former 投影仪，ParGo 在 MME 基准上提升了 259.96 分。实验还揭示，ParGo 在注重细节感知能力的任务中表现尤为突出。

> This work presents ParGo, a novel Partial-Global projector designed to connect the vision and language modalities for Multimodal Large Language Models (MLLMs). Unlike previous works that rely on global attention-based projectors, our ParGo bridges the representation gap between the separately pre-trained vision encoders and the LLMs by integrating global and partial views, which alleviates the overemphasis on prominent regions. To facilitate the effective training of ParGo, we collect a large-scale detail-captioned image-text dataset named ParGoCap-1M-PT, consisting of 1 million images paired with high-quality captions. Extensive experiments on several MLLM benchmarks demonstrate the effectiveness of our ParGo, highlighting its superiority in aligning vision and language modalities. Compared to conventional Q-Former projector, our ParGo achieves an improvement of 259.96 in MME benchmark. Furthermore, our experiments reveal that ParGo significantly outperforms other projectors, particularly in tasks that emphasize detail perception ability.

[Arxiv](https://arxiv.org/abs/2408.12928)