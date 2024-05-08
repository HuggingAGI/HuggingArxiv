# SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的学习和测试平台。通过深入分析不同编辑任务的特点和挑战，我们希望推动图像编辑技术的发展，并促进相关应用的创新。

发布时间：2024年05月07日

`LLM应用

这篇论文摘要介绍了一个名为SEED-Data-Edit的数据集，该数据集旨在支持开放式语言指导图像编辑模型的训练。它包含了自动化生成的编辑样本、互联网采集的真实数据以及人类标注的编辑过程，这些数据共同构成了一个全面的训练集。论文中提到利用这个数据集对预训练的多模态大型语言模型进行了微调，并展示了数据集在推动指令图像编辑技术方面的潜力。因此，这篇论文更偏向于LLM（大型语言模型）的应用领域，因为它关注的是如何通过特定的数据集来改进和应用LLM技术于图像编辑任务。` `图像编辑` `多模态学习`

> SEED-Data-Edit Technical Report: A Hybrid Dataset for Instructional Image Editing

# 摘要

> 本报告介绍了SEED-Data-Edit，一个专为开放式语言指导图像编辑设计的独特混合数据集。它包含三类数据：自动化生成的高质量编辑样本、互联网采集的真实场景数据，以及人类标注的多轮高精度编辑过程。这些数据共同构成了一个全面且灵活的训练集，用于开发语言指导的图像编辑模型。我们利用SEED-Data-Edit对预训练的多模态大型语言模型进行了微调，结果显示该数据集在推动指令图像编辑技术方面具有显著潜力。数据集已公开发布于https://huggingface.co/datasets/AILab-CVC/SEED-Data-Edit。

> In this technical report, we introduce SEED-Data-Edit: a unique hybrid dataset for instruction-guided image editing, which aims to facilitate image manipulation using open-form language. SEED-Data-Edit is composed of three distinct types of data: (1) High-quality editing data produced by an automated pipeline, ensuring a substantial volume of diverse image editing pairs. (2) Real-world scenario data collected from the internet, which captures the intricacies of user intentions for promoting the practical application of image editing in the real world. (3) High-precision multi-turn editing data annotated by humans, which involves multiple rounds of edits for simulating iterative editing processes. The combination of these diverse data sources makes SEED-Data-Edit a comprehensive and versatile dataset for training language-guided image editing model. We fine-tune a pretrained Multimodal Large Language Model (MLLM) that unifies comprehension and generation with SEED-Data-Edit. The instruction tuned model demonstrates promising results, indicating the potential and effectiveness of SEED-Data-Edit in advancing the field of instructional image editing. The datasets are released in https://huggingface.co/datasets/AILab-CVC/SEED-Data-Edit.

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的学习和测试平台。通过深入分析不同编辑任务的特点和挑战，我们希望推动图像编辑技术的发展，并促进相关应用的创新。](../../../paper_images/2405.04007/x1.png)

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的学习和测试平台。通过深入分析不同编辑任务的特点和挑战，我们希望推动图像编辑技术的发展，并促进相关应用的创新。](../../../paper_images/2405.04007/x2.png)

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的学习和测试平台。通过深入分析不同编辑任务的特点和挑战，我们希望推动图像编辑技术的发展，并促进相关应用的创新。](../../../paper_images/2405.04007/x3.png)

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的学习和测试平台。通过深入分析不同编辑任务的特点和挑战，我们希望推动图像编辑技术的发展，并促进相关应用的创新。](../../../paper_images/2405.04007/x4.png)

[Arxiv](https://arxiv.org/abs/2405.04007)