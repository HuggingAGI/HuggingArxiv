# Panther：以指令引导的视觉提示为多模态大型语言模型点亮视野

发布时间：2024年11月22日

`LLM应用` `多模态语言模型`

> Panther: Illuminate the Sight of Multimodal LLMs with Instruction-Guided Visual Prompts

# 摘要

> 多模态大型语言模型（MLLMs）正迅速拉近与人类视觉感知能力的距离，不过在留意细微的图像细节、精准定位小物体等方面仍有不足。解决此类问题的常见办法包括部署多个视觉编码器或者处理原始高分辨率图像。鲜少研究聚焦于借助文本指令来优化视觉表征，致使在一些以视觉为核心的任务中出现失焦的情况，我们将此现象称为“弱视”。在本研究中，我们推出了 Panther 这一多模态大型语言模型，它能紧密依照用户指令，精准定位感兴趣的目标，犹如黑豹般出色。具体来说，Panther 包含三个核心组件：Panther-VE、Panther-Bridge 和 Panther-Decoder。Panther-VE 在视觉编码器的早期阶段就融入用户指令信息，进而提取出最相关、最有用的视觉表征。Panther-Bridge 模块具备强大的过滤功能，大幅减少了冗余的视觉信息，显著降低了训练成本。Panther-Decoder 通用性强，能够与任何仅解码器架构的大型语言模型无障碍配合使用。实验结果，尤其是在以视觉为重点的基准测试中，彰显了 Panther 的有效性。

> Multimodal large language models (MLLMs) are closing the gap to human visual perception capability rapidly, while, still lag behind on attending to subtle images details or locating small objects precisely, etc. Common schemes to tackle these issues include deploying multiple vision encoders or operating on original high-resolution images. Few studies have concentrated on taking the textual instruction into improving visual representation, resulting in losing focus in some vision-centric tasks, a phenomenon we herein termed as Amblyopia. In this work, we introduce Panther, a MLLM that closely adheres to user instruction and locates targets of interests precisely, with the finesse of a black panther. Specifically, Panther comprises three integral components: Panther-VE, Panther-Bridge, and Panther-Decoder. Panther-VE integrates user instruction information at the early stages of the vision encoder, thereby extracting the most relevant and useful visual representations. The Panther-Bridge module, equipped with powerful filtering capabilities, significantly reduces redundant visual information, leading to a substantial savings in training costs. The Panther-Decoder is versatile and can be employed with any decoder-only architecture of LLMs without discrimination. Experimental results, particularly on vision-centric benchmarks, have demonstrated the effectiveness of Panther.

[Arxiv](https://arxiv.org/abs/2411.13909)