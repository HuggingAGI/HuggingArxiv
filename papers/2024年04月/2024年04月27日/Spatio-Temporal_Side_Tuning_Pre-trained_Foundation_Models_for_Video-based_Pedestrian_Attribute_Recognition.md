# 为视频驱动的行人属性识别任务，我们采用了时空侧向调整技术来优化预训练的基础模型。

发布时间：2024年04月27日

`Agent` `行人识别` `视频分析`

> Spatio-Temporal Side Tuning Pre-trained Foundation Models for Video-based Pedestrian Attribute Recognition

# 摘要

> 传统行人属性识别算法多建立在静态图像之上，面对重度遮挡或运动模糊等复杂情境时，其识别效果不尽人意。本研究提出一种新方法，通过视频帧捕捉时间信息，辅以高效微调的预训练多模态基础模型，以提升识别准确性。我们将视频驱动的PAR问题视作视觉与语言融合的挑战，并使用预训练模型CLIP来抽取视觉特征。此外，我们引入了一种创新的时空边调策略，优化了预训练视觉模型的参数效率。为了充分挖掘语义信息，我们将待识别的属性列表作为额外输入，通过分割、扩展和提示操作，将其转换为句子形式，再由CLIP的文本编码器进行嵌入处理。随后，视觉和文本标记的融合通过Transformer进行多模态交互学习，最终输出用于行人属性的预测分类。在两大视频基PAR数据集上的广泛实验，全面证实了我们框架的有效性。本研究的源代码已在GitHub发布，地址为：https://github.com/Event-AHU/OpenPAR。

> Existing pedestrian attribute recognition (PAR) algorithms are mainly developed based on a static image, however, the performance is unreliable in challenging scenarios, such as heavy occlusion, motion blur, etc. In this work, we propose to understand human attributes using video frames that can fully use temporal information by fine-tuning a pre-trained multi-modal foundation model efficiently. Specifically, we formulate the video-based PAR as a vision-language fusion problem and adopt a pre-trained foundation model CLIP to extract the visual features. More importantly, we propose a novel spatiotemporal side-tuning strategy to achieve parameter-efficient optimization of the pre-trained vision foundation model. To better utilize the semantic information, we take the full attribute list that needs to be recognized as another input and transform the attribute words/phrases into the corresponding sentence via split, expand, and prompt operations. Then, the text encoder of CLIP is utilized for embedding processed attribute descriptions. The averaged visual tokens and text tokens are concatenated and fed into a fusion Transformer for multi-modal interactive learning. The enhanced tokens will be fed into a classification head for pedestrian attribute prediction. Extensive experiments on two large-scale video-based PAR datasets fully validated the effectiveness of our proposed framework. The source code of this paper is available at https://github.com/Event-AHU/OpenPAR.

[Arxiv](https://arxiv.org/abs/2404.17929)