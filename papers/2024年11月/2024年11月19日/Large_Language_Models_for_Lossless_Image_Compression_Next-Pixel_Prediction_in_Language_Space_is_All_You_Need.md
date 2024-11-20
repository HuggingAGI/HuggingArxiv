# 对于无损图像压缩，大型语言模型足矣：在语言空间中进行下一个像素预测即可

发布时间：2024年11月19日

`LLM应用` `图像压缩` `流媒体`

> Large Language Models for Lossless Image Compression: Next-Pixel Prediction in Language Space is All You Need

# 摘要

> 我们近来发现，“智能”与“压缩”乃同一事物的两面，具备空前智能的语言大型模型（LLM）堪称各类数据模式的通用无损压缩器。在当下的流媒体时代，对高分辨率图像压缩的需求日益增长，此属性尤其吸引了无损图像压缩领域。于是，一个自然的构想应运而生：LLM 的压缩性能能否将无损图像压缩推至新高度？然而，我们的成果显示，在常见基准数据集上，基于 LLM 的无损图像压缩器的简单运用与现有的最先进（SOTA）编解码器相比，存在显著的性能差距。鉴于此，我们致力于为无损图像压缩任务发挥 LLM 前所未有的智能（压缩）能力，从而填补理论与实际压缩性能之间的鸿沟。具体而言，我们提出了 P$^{2}$-LLM，这是一种基于下一个像素预测的 LLM，它融合了多种精心构思的见解和方法，比如像素级先验、LLM 的上下文能力以及像素级语义保留策略，以增强对像素序列的理解能力，从而更出色地进行下一个像素预测。在基准数据集上的大量实验表明，P$^{2}$-LLM 能够超越 SOTA 经典和学习型编解码器。

> We have recently witnessed that ``Intelligence" and `` Compression" are the two sides of the same coin, where the language large model (LLM) with unprecedented intelligence is a general-purpose lossless compressor for various data modalities. This attribute particularly appeals to the lossless image compression community, given the increasing need to compress high-resolution images in the current streaming media era. Consequently, a spontaneous envision emerges: Can the compression performance of the LLM elevate lossless image compression to new heights? However, our findings indicate that the naive application of LLM-based lossless image compressors suffers from a considerable performance gap compared with existing state-of-the-art (SOTA) codecs on common benchmark datasets. In light of this, we are dedicated to fulfilling the unprecedented intelligence (compression) capacity of the LLM for lossless image compression tasks, thereby bridging the gap between theoretical and practical compression performance. Specifically, we propose P$^{2}$-LLM, a next-pixel prediction-based LLM, which integrates various elaborated insights and methodologies, \textit{e.g.,} pixel-level priors, the in-context ability of LLM, and a pixel-level semantic preservation strategy, to enhance the understanding capacity of pixel sequences for better next-pixel predictions. Extensive experiments on benchmark datasets demonstrate that P$^{2}$-LLM can beat SOTA classical and learned codecs.

[Arxiv](https://arxiv.org/abs/2411.12448)