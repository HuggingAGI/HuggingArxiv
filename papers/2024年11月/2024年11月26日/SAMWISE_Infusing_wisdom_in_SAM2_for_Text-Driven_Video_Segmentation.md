# SAMWISE：为 SAM2 注入智慧用于文本驱动的视频分割

发布时间：2024年11月26日

`LLM应用` `视频处理`

> SAMWISE: Infusing wisdom in SAM2 for Text-Driven Video Segmentation

# 摘要

> 参考视频对象分割（RVOS）借助自然语言表述来对视频片段中的对象进行分割。现有的方法，要么将推理局限于独立的短片段，从而丢失全局语境，要么离线处理整个视频，这不利于其以流的形式应用。在本研究中，我们致力于突破这些限制，设计出一种能在类似流的场景中有效运作，同时保留过往帧的上下文信息的 RVOS 方法。我们以具备强大分割和跟踪能力、天然适配流处理的 Segment-Anything 2（SAM2）模型为基础。我们让 SAM2 更聪慧，在特征提取阶段赋予其自然语言理解和明确的时间建模能力，无需微调其权重，也无需将模态交互委托给外部模型。为此，我们引入了一个新颖的适配器模块，在特征提取过程中注入时间信息和多模态线索。我们还揭示了 SAM2 中的跟踪偏差现象，并提出一个可学习的模块，当当前帧特征显示出一个与标题更相符的新对象时，调整其跟踪重点。我们提出的 SAMWISE 方法，仅增加了微不足道的 4.2 M 个参数，就在各类基准测试中达到了领先水平。代码可在 https://github.com/ClaudiaCuttano/SAMWISE 获取。

> Referring Video Object Segmentation (RVOS) relies on natural language expressions to segment an object in a video clip. Existing methods restrict reasoning either to independent short clips, losing global context, or process the entire video offline, impairing their application in a streaming fashion. In this work, we aim to surpass these limitations and design an RVOS method capable of effectively operating in streaming-like scenarios while retaining contextual information from past frames. We build upon the Segment-Anything 2 (SAM2) model, that provides robust segmentation and tracking capabilities and is naturally suited for streaming processing. We make SAM2 wiser, by empowering it with natural language understanding and explicit temporal modeling at the feature extraction stage, without fine-tuning its weights, and without outsourcing modality interaction to external models. To this end, we introduce a novel adapter module that injects temporal information and multi-modal cues in the feature extraction process. We further reveal the phenomenon of tracking bias in SAM2 and propose a learnable module to adjust its tracking focus when the current frame features suggest a new object more aligned with the caption. Our proposed method, SAMWISE, achieves state-of-the-art across various benchmarks, by adding a negligible overhead of just 4.2 M parameters. The code is available at https://github.com/ClaudiaCuttano/SAMWISE

[Arxiv](https://arxiv.org/abs/2411.17646)