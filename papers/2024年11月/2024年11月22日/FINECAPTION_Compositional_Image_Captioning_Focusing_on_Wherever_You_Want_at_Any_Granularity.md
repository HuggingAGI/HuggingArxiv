# FINECAPTION：专注于在任何粒度上您所期望的任何地方的组合图像字幕

发布时间：2024年11月22日

`LLM应用` `多模态`

> FINECAPTION: Compositional Image Captioning Focusing on Wherever You Want at Any Granularity

# 摘要

> 大型视觉语言模型（VLMs）的问世显著推动了多模态任务的发展，让包括图像和视频字幕生成、视觉问答以及跨模态检索等各类应用能够实现更复杂、更精准的推理。尽管VLMs能力出众，但在细粒度图像区域组合信息的感知上却遭遇难题。具体来说，它们难以将分割掩码与对应的语义精准匹配，也无法精确描述所指区域的组合情况。
  然而，组合性——即理解和生成已知视觉与文本组件新组合的能力，对于促进VLMs在跨模态间的连贯推理和理解至关重要。为解决这一问题，我们提出了FINECAPTION，这一新型VLM能够将任意掩码视作参考输入，并处理高分辨率图像，以达成不同粒度级别的组合图像字幕生成。为助力此项工作，我们引入了COMPOSITIONCAP，这是一个用于多粒度区域组合图像字幕的新数据集，它带来了组合属性感知区域图像字幕的任务。
  实证结果显示，与其他前沿的VLMs相比，我们所提出的模型效果显著。此外，我们还分析了当前VLMs在识别各类用于组合区域图像字幕的视觉提示方面的能力，突出了VLM设计和训练中有待改进的地方。

> The advent of large Vision-Language Models (VLMs) has significantly advanced multimodal tasks, enabling more sophisticated and accurate reasoning across various applications, including image and video captioning, visual question answering, and cross-modal retrieval. Despite their superior capabilities, VLMs struggle with fine-grained image regional composition information perception. Specifically, they have difficulty accurately aligning the segmentation masks with the corresponding semantics and precisely describing the compositional aspects of the referred regions.
  However, compositionality - the ability to understand and generate novel combinations of known visual and textual components - is critical for facilitating coherent reasoning and understanding across modalities by VLMs. To address this issue, we propose FINECAPTION, a novel VLM that can recognize arbitrary masks as referential inputs and process high-resolution images for compositional image captioning at different granularity levels. To support this endeavor, we introduce COMPOSITIONCAP, a new dataset for multi-grained region compositional image captioning, which introduces the task of compositional attribute-aware regional image captioning.
  Empirical results demonstrate the effectiveness of our proposed model compared to other state-of-the-art VLMs. Additionally, we analyze the capabilities of current VLMs in recognizing various visual prompts for compositional region image captioning, highlighting areas for improvement in VLM design and training.

[Arxiv](https://arxiv.org/abs/2411.15411)