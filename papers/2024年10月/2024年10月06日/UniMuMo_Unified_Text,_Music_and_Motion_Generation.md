# UniMuMo：融合文本、音乐与动作的生成艺术

发布时间：2024年10月06日

`LLM应用` `人工智能`

> UniMuMo: Unified Text, Music and Motion Generation

# 摘要

> 我们推出了 UniMuMo，一个能够处理任意文本、音乐和运动数据的多模态模型，生成跨三种模态的输出。为解决时间同步数据的缺失，我们通过节奏模式对齐未配对音乐和运动数据，充分利用现有的大规模音乐和运动数据集。通过将音乐、运动和文本转换为基于令牌的表示，我们的模型通过统一的编码器-解码器变换器架构连接这些模态。为支持多种生成任务，我们进行了架构改进，如使用音乐码本编码运动，并引入音乐-运动并行生成方案，将所有生成任务统一到一个变换器解码器架构中。此外，通过微调预训练单模态模型，显著降低了计算需求。实验证明，UniMuMo 在音乐、运动和文本模态的单向生成基准测试中表现出色。定量结果详见项目页面。

> We introduce UniMuMo, a unified multimodal model capable of taking arbitrary text, music, and motion data as input conditions to generate outputs across all three modalities. To address the lack of time-synchronized data, we align unpaired music and motion data based on rhythmic patterns to leverage existing large-scale music-only and motion-only datasets. By converting music, motion, and text into token-based representation, our model bridges these modalities through a unified encoder-decoder transformer architecture. To support multiple generation tasks within a single framework, we introduce several architectural improvements. We propose encoding motion with a music codebook, mapping motion into the same feature space as music. We introduce a music-motion parallel generation scheme that unifies all music and motion generation tasks into a single transformer decoder architecture with a single training task of music-motion joint generation. Moreover, the model is designed by fine-tuning existing pre-trained single-modality models, significantly reducing computational demands. Extensive experiments demonstrate that UniMuMo achieves competitive results on all unidirectional generation benchmarks across music, motion, and text modalities. Quantitative results are available in the \href{https://hanyangclarence.github.io/unimumo_demo/}{project page}.

[Arxiv](https://arxiv.org/abs/2410.04534)