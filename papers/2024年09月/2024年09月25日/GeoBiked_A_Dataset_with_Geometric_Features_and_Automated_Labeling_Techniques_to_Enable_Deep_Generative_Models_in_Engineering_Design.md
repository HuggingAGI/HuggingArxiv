# GeoBiked 数据集结合了几何特征与自动化标注技术，为工程设计领域的深度生成模型提供了强大支持。

发布时间：2024年09月25日

`LLM应用` `工程设计` `人工智能`

> GeoBiked: A Dataset with Geometric Features and Automated Labeling Techniques to Enable Deep Generative Models in Engineering Design

# 摘要

> 我们为工程设计中的深度生成模型 (DGM) 提供了一个数据集，并提出了利用大规模基础模型自动化数据标注的方法。GeoBiked 包含 4355 张标注了结构和技术特征的自行车图像，用于研究两种自动化标注技术：利用图像生成模型的整合潜在特征 (Hyperfeatures) 检测结构图像中的几何对应关系，以及生成多样化的文本描述。GPT-4o 是一种视觉语言模型 (VLM)，能够分析图像并生成与系统提示一致的多样化描述。通过将技术图像表示为扩散超特征，可以在它们之间绘制几何对应关系。GPT-4o 能够生成技术图像的准确描述，但仅基于图像生成会导致多样化的描述和幻觉，而基于类别标签生成则会限制多样性。同时使用两者作为输入可以平衡创造力和准确性。成功使用 Hyperfeatures 进行几何对应关系表明，这种方法可以用于技术图像中的一般点检测和标注任务。使用 VLM 对这些图像进行文本描述标注是可能的，但取决于模型的检测能力、提示工程和输入信息的选择。在工程设计中应用基础模型在很大程度上尚未探索。我们的目标是通过一个数据集来弥合这一差距，探索在该领域中训练、微调和条件化 DGM，并提出引导基础模型处理技术图像的方法。

> We provide a dataset for enabling Deep Generative Models (DGMs) in engineering design and propose methods to automate data labeling by utilizing large-scale foundation models. GeoBiked is curated to contain 4 355 bicycle images, annotated with structural and technical features and is used to investigate two automated labeling techniques: The utilization of consolidated latent features (Hyperfeatures) from image-generation models to detect geometric correspondences (e.g. the position of the wheel center) in structural images and the generation of diverse text descriptions for structural images. GPT-4o, a vision-language-model (VLM), is instructed to analyze images and produce diverse descriptions aligned with the system-prompt. By representing technical images as Diffusion-Hyperfeatures, drawing geometric correspondences between them is possible. The detection accuracy of geometric points in unseen samples is improved by presenting multiple annotated source images. GPT-4o has sufficient capabilities to generate accurate descriptions of technical images. Grounding the generation only on images leads to diverse descriptions but causes hallucinations, while grounding it on categorical labels restricts the diversity. Using both as input balances creativity and accuracy. Successfully using Hyperfeatures for geometric correspondence suggests that this approach can be used for general point-detection and annotation tasks in technical images. Labeling such images with text descriptions using VLMs is possible, but dependent on the models detection capabilities, careful prompt-engineering and the selection of input information. Applying foundation models in engineering design is largely unexplored. We aim to bridge this gap with a dataset to explore training, finetuning and conditioning DGMs in this field and suggesting approaches to bootstrap foundation models to process technical images.

[Arxiv](https://arxiv.org/abs/2409.17045)