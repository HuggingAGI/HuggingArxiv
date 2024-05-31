# RapVerse：文本驱动，创造连贯声乐与全身动作的完美融合

发布时间：2024年05月30日

`LLM应用

这篇论文的研究内容涉及从文本歌词生成3D全身动作与歌唱声音，这是一个具体的应用场景，涉及到语言模型（LLM）在多模态任务中的应用。虽然文中提到了使用变压器模型和自编码器等技术，但这些技术的应用是为了解决特定的实际问题，即生成连贯且真实的歌唱表演。因此，这篇论文更符合LLM应用的分类，而不是Agent、RAG或LLM理论。` `虚拟现实`

> RapVerse: Coherent Vocals and Whole-Body Motions Generations from Text

# 摘要

> 本研究提出了一项创新任务：从文本歌词直接生成3D全身动作与歌唱声音，突破了以往分别处理声音与动作的传统。我们创建了RapVerse数据集，包含同步的说唱声音、歌词及高质量的3D人体模型，以此探索多模态变压器在语言、音频和动作上的扩展如何提升声音与动作生成的真实感与连贯性。通过向量量化变分自编码器和声音到单元模型，我们将动作与声音分别转换为离散令牌，确保内容的保留与歌手特征的体现。我们的框架通过统一处理这三种模态，实现了声音与动作的和谐融合。实验证明，该框架不仅能够从文本输入直接生成连贯且真实的歌唱表演，其性能亦可与单模态系统媲美，为联合声音-动作生成领域树立了新标杆。项目详情请访问：https://vis-www.cs.umass.edu/RapVerse。

> In this work, we introduce a challenging task for simultaneously generating 3D holistic body motions and singing vocals directly from textual lyrics inputs, advancing beyond existing works that typically address these two modalities in isolation. To facilitate this, we first collect the RapVerse dataset, a large dataset containing synchronous rapping vocals, lyrics, and high-quality 3D holistic body meshes. With the RapVerse dataset, we investigate the extent to which scaling autoregressive multimodal transformers across language, audio, and motion can enhance the coherent and realistic generation of vocals and whole-body human motions. For modality unification, a vector-quantized variational autoencoder is employed to encode whole-body motion sequences into discrete motion tokens, while a vocal-to-unit model is leveraged to obtain quantized audio tokens preserving content, prosodic information, and singer identity. By jointly performing transformer modeling on these three modalities in a unified way, our framework ensures a seamless and realistic blend of vocals and human motions. Extensive experiments demonstrate that our unified generation framework not only produces coherent and realistic singing vocals alongside human motions directly from textual inputs but also rivals the performance of specialized single-modality generation systems, establishing new benchmarks for joint vocal-motion generation. The project page is available for research purposes at https://vis-www.cs.umass.edu/RapVerse.

![RapVerse：文本驱动，创造连贯声乐与全身动作的完美融合](../../../paper_images/2405.20336/x1.png)

![RapVerse：文本驱动，创造连贯声乐与全身动作的完美融合](../../../paper_images/2405.20336/x2.png)

![RapVerse：文本驱动，创造连贯声乐与全身动作的完美融合](../../../paper_images/2405.20336/x3.png)

![RapVerse：文本驱动，创造连贯声乐与全身动作的完美融合](../../../paper_images/2405.20336/x4.png)

[Arxiv](https://arxiv.org/abs/2405.20336)