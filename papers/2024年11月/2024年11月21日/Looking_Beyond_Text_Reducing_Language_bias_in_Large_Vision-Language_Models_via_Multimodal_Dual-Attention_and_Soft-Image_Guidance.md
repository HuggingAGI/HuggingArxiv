# 超越文本：借助多模态双注意力与软图像引导来降低大型视觉语言模型中的语言偏差

发布时间：2024年11月21日

`LLM应用` `计算机视觉`

> Looking Beyond Text: Reducing Language bias in Large Vision-Language Models via Multimodal Dual-Attention and Soft-Image Guidance

# 摘要

> 大型视觉语言模型（LVLMs）在各类视觉语言任务中成绩斐然。不过，尽管性能出色，LVLMs 却因语言偏差产生幻觉，致使对图像的关注度降低，视觉理解效果不佳。造成这种偏差的主要原因有二：其一，LLM 预训练阶段与多模态对齐阶段的训练数据规模存在差异；其二，文本数据的短期依赖导致了学习推理偏差。为此，我们提出了 LACING 这一系统框架，借助多模态双注意力机制（MDA）和软图像引导（IFG）来解决 LVLMs 的语言偏差问题。具体来说，MDA 引入了并行的双注意力机制，强化了模型对视觉输入的整合。IFG 在训练和推理过程中引入可学习的软视觉提示以替代视觉输入，旨在促使 LVLMs 优先处理文本输入。随后，IFG 还进一步提出了一种运用软视觉提示的新型解码策略，以减轻模型对相邻文本输入的过度依赖。综合实验表明，我们的方法能有效消除 LVLMs 的语言偏差，增强视觉理解，减少幻觉，且无需额外的训练资源或数据。代码和模型可在 [lacing-lvlm.github.io](https://lacing-lvlm.github.io) 获得。

> Large vision-language models (LVLMs) have achieved impressive results in various vision-language tasks. However, despite showing promising performance, LVLMs suffer from hallucinations caused by language bias, leading to diminished focus on images and ineffective visual comprehension. We identify two primary reasons for this bias: 1. Different scales of training data between the pretraining stage of LLM and multimodal alignment stage. 2. The learned inference bias due to short-term dependency of text data. Therefore, we propose LACING, a systemic framework designed to address the language bias of LVLMs with muLtimodal duAl-attention meChanIsm (MDA) aNd soft-image Guidance (IFG). Specifically, MDA introduces a parallel dual-attention mechanism that enhances the integration of visual inputs across the model. IFG introduces a learnable soft visual prompt during training and inference to replace visual inputs, designed to compel LVLMs to prioritize text inputs. Then, IFG further proposes a novel decoding strategy using the soft visual prompt to mitigate the model's over-reliance on adjacent text inputs. Comprehensive experiments demonstrate that our method effectively debiases LVLMs from their language bias, enhancing visual comprehension and reducing hallucinations without requiring additional training resources or data. The code and model are available at [lacing-lvlm.github.io](https://lacing-lvlm.github.io).

[Arxiv](https://arxiv.org/abs/2411.14279)