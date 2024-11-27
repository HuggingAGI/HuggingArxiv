# 借助 MLLMs 的强大力量实现无注释手语翻译

发布时间：2024年11月25日

`LLM应用` `手语翻译` `多模态语言模型`

> Leveraging the Power of MLLMs for Gloss-Free Sign Language Translation

# 摘要

> 手语翻译（SLT）是个颇具挑战性的任务，要把手语图像转化为口语。要让 SLT 模型顺利完成这一任务，就得弥合模态差异，识别出手语成分的细微变化，从而精准理解其含义。为应对这些难题，我们提出了一个名为多模态手语翻译（MMSLT）的全新无注释手语翻译框架，它借助了现成的多模态大型语言模型（MLLMs）的表征能力。具体来说，我们利用 MLLMs 生成手语成分的详细文本描述。接着，通过我们提出的多模态语言预训练模块，将这些描述特征与手语视频特征相融合，使其在口语句子空间中达成对齐。我们的方法在基准数据集 PHOENIX14T 和 CSL-Daily 上表现出色，达到了最先进水平，凸显了 MLLMs 在 SLT 中有效运用的潜力。

> Sign language translation (SLT) is a challenging task that involves translating sign language images into spoken language. For SLT models to perform this task successfully, they must bridge the modality gap and identify subtle variations in sign language components to understand their meanings accurately. To address these challenges, we propose a novel gloss-free SLT framework called Multimodal Sign Language Translation (MMSLT), which leverages the representational capabilities of off-the-shelf multimodal large language models (MLLMs). Specifically, we generate detailed textual descriptions of sign language components using MLLMs. Then, through our proposed multimodal-language pre-training module, we integrate these description features with sign video features to align them within the spoken sentence space. Our approach achieves state-of-the-art performance on benchmark datasets PHOENIX14T and CSL-Daily, highlighting the potential of MLLMs to be effectively utilized in SLT.

[Arxiv](https://arxiv.org/abs/2411.16789)