# Img-Diff：为多模态大型语言模型打造对比数据合成

发布时间：2024年08月08日

`LLM应用` `计算机视觉` `人工智能`

> Img-Diff: Contrastive Data Synthesis for Multimodal Large Language Models

# 摘要

> 本研究通过引入Img-Diff数据集，提升了多模态大型语言模型（MLLMs）的细粒度图像识别能力。该数据集利用对比学习和图像差异描述技术，通过分析相似图像间的对象差异，挑战模型识别匹配与不同元素。我们采用Stable-Diffusion-XL模型及高级图像编辑技巧，生成强调对象替换的相似图像对，并设计了差异区域与描述生成器，构建了一个小而精的“对象替换”样本集。经此数据集微调的MGM-7B等SOTA MLLMs，在图像差异与视觉问答任务中，性能超越了使用更大规模数据集训练的模型，如在MMVP基准上显著领先于GPT-4V和Gemini。此外，我们还探索了通过“对象移除”生成差异数据的方法，并进行了全面评估，确保数据集的多样性、质量与鲁棒性，为对比数据集的合成提供了新见解。为推动多模态数据合成研究及MLLMs图像理解能力的提升，我们在GitHub上公开了相关代码与数据集。

> High-performance Multimodal Large Language Models (MLLMs) rely heavily on data quality. This study introduces a novel dataset named Img-Diff, designed to enhance fine-grained image recognition in MLLMs by leveraging insights from contrastive learning and image difference captioning. By analyzing object differences between similar images, we challenge models to identify both matching and distinct components. We utilize the Stable-Diffusion-XL model and advanced image editing techniques to create pairs of similar images that highlight object replacements. Our methodology includes a Difference Area Generator for object differences identifying, followed by a Difference Captions Generator for detailed difference descriptions. The result is a relatively small but high-quality dataset of "object replacement" samples. We use the the proposed dataset to fine-tune state-of-the-art (SOTA) MLLMs such as MGM-7B, yielding comprehensive improvements of performance scores over SOTA models that trained with larger-scale datasets, in numerous image difference and Visual Question Answering tasks. For instance, our trained models notably surpass the SOTA models GPT-4V and Gemini on the MMVP benchmark. Besides, we investigate alternative methods for generating image difference data through "object removal" and conduct thorough evaluation to confirm the dataset's diversity, quality, and robustness, presenting several insights on synthesis of such contrastive dataset. To encourage further research and advance the field of multimodal data synthesis and enhancement of MLLMs' fundamental capabilities for image understanding, we release our codes and dataset at https://github.com/modelscope/data-juicer/tree/ImgDiff.

[Arxiv](https://arxiv.org/abs/2408.04594)