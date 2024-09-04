# DCIM-AVSR：借助双Conformer交互模块，实现视听语音识别的高效处理

发布时间：2024年08月31日

`Agent` `虚拟助手` `转录服务`

> DCIM-AVSR : Efficient Audio-Visual Speech Recognition via Dual Conformer Interaction Module

# 摘要

> 语音识别技术使机器能够理解和处理人类语音，将其转化为文本或指令，对虚拟助手、转录服务等应用至关重要。音频-视觉语音识别（AVSR）模型通过整合视觉信息如唇动和面部表情，在嘈杂环境中提升了识别能力。尽管传统AVSR模型在大规模数据集上训练，参数众多，准确性高，但训练成本和部署难度也大。为此，我们设计了一种高效AVSR模型，通过双Conformer交互模块减少参数，并采用预训练方法优化性能，显著提升效率。我们的模型直接在架构中融合了音频与视觉模态的关系，既提高了效率，又增强了性能，为AVSR任务提供了更实用、更有效的解决方案。

> Speech recognition is the technology that enables machines to interpret and process human speech, converting spoken language into text or commands. This technology is essential for applications such as virtual assistants, transcription services, and communication tools. The Audio-Visual Speech Recognition (AVSR) model enhances traditional speech recognition, particularly in noisy environments, by incorporating visual modalities like lip movements and facial expressions. While traditional AVSR models trained on large-scale datasets with numerous parameters can achieve remarkable accuracy, often surpassing human performance, they also come with high training costs and deployment challenges. To address these issues, we introduce an efficient AVSR model that reduces the number of parameters through the integration of a Dual Conformer Interaction Module (DCIM). In addition, we propose a pre-training method that further optimizes model performance by selectively updating parameters, leading to significant improvements in efficiency. Unlike conventional models that require the system to independently learn the hierarchical relationship between audio and visual modalities, our approach incorporates this distinction directly into the model architecture. This design enhances both efficiency and performance, resulting in a more practical and effective solution for AVSR tasks.

[Arxiv](https://arxiv.org/abs/2409.00481)