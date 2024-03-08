# [我们构建了一种基于单个事件声音的精细音频文本数据仿真流程，旨在高效生成高质量的模拟数据。](https://arxiv.org/abs/2403.04594)

发布时间：2024年03月07日

`LLM应用`

> A Detailed Audio-Text Data Simulation Pipeline using Single-Event Sounds

> 近期，音频-文本跨模态学习研究热度攀升，但现存的大部分相关数据集仅提供了对声音事件的基本描述，相较于分类标签，这类描述的信息量有限。本文首先深入剖析了人类描述音频时可能会超越声音事件标签所涵盖的详细信息内容。在此基础上，我们创新性地提出了一个自动化流水线，专门用来构建蕴含丰富细节的音频-文本对。利用声音信号在时间维度上可混合拼接的特点，我们从时间关联性、音量大小、说话者身份以及出现次数四个维度对模拟音频进行精细化控制，并借助大型语言模型将这些细节转换为生动详尽的字幕。最终，我们成功获取了一批文本描述富含细腻信息的音频-文本对。通过小规模模拟数据验证，证明了该流水线的有效性，揭示了模拟数据能够有效训练模型捕捉并生成精细音频字幕的能力。

> Recently, there has been an increasing focus on audio-text cross-modal learning. However, most of the existing audio-text datasets contain only simple descriptions of sound events. Compared with classification labels, the advantages of such descriptions are significantly limited. In this paper, we first analyze the detailed information that human descriptions of audio may contain beyond sound event labels. Based on the analysis, we propose an automatic pipeline for curating audio-text pairs with rich details. Leveraging the property that sounds can be mixed and concatenated in the time domain, we control details in four aspects: temporal relationship, loudness, speaker identity, and occurrence number, in simulating audio mixtures. Corresponding details are transformed into captions by large language models. Audio-text pairs with rich details in text descriptions are thereby obtained. We validate the effectiveness of our pipeline with a small amount of simulated data, demonstrating that the simulated data enables models to learn detailed audio captioning.