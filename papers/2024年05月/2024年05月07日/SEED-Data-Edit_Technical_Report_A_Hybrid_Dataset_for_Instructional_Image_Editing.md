# SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的资源，以探索和提升图像编辑技术的教学方法。通过深入分析数据集的构成和应用，我们希望激发更多关于图像编辑教学的创新思路和实践。

发布时间：2024年05月07日

`Agent

这篇论文介绍了一个名为SEED-Data-Edit的混合数据集，用于开发语言指导的图像编辑模型。它通过整合自动化生成的编辑样本、互联网采集的现实场景数据以及人类标注的编辑过程，构建了一个全面的训练平台。论文中提到利用这个数据集对预训练的多模态大型语言模型进行微调，展示了其在推动指令图像编辑技术发展上的潜力。这个数据集的开发和应用，以及对预训练模型的微调，都是为了创建能够理解和执行语言指令的智能Agent，因此将其分类为Agent。` `图像编辑` `多模态学习`

> SEED-Data-Edit Technical Report: A Hybrid Dataset for Instructional Image Editing

# 摘要

> 本报告介绍了SEED-Data-Edit，一个专为开放式语言指导图像编辑设计的独特混合数据集。它汇集了三种数据：自动化生成的高质量编辑样本、互联网采集的现实场景数据，以及人类标注的多轮高精度编辑过程。这些数据共同打造了一个全面且灵活的训练平台，用于开发语言指导的图像编辑模型。我们利用SEED-Data-Edit对预训练的多模态大型语言模型进行了微调，结果显示了其在推动指令图像编辑技术发展上的巨大潜力。数据集已公开发布，供研究者探索。

> In this technical report, we introduce SEED-Data-Edit: a unique hybrid dataset for instruction-guided image editing, which aims to facilitate image manipulation using open-form language. SEED-Data-Edit is composed of three distinct types of data: (1) High-quality editing data produced by an automated pipeline, ensuring a substantial volume of diverse image editing pairs. (2) Real-world scenario data collected from the internet, which captures the intricacies of user intentions for promoting the practical application of image editing in the real world. (3) High-precision multi-turn editing data annotated by humans, which involves multiple rounds of edits for simulating iterative editing processes. The combination of these diverse data sources makes SEED-Data-Edit a comprehensive and versatile dataset for training language-guided image editing model. We fine-tune a pretrained Multimodal Large Language Model (MLLM) that unifies comprehension and generation with SEED-Data-Edit. The instruction tuned model demonstrates promising results, indicating the potential and effectiveness of SEED-Data-Edit in advancing the field of instructional image editing. The datasets are released in https://huggingface.co/datasets/AILab-CVC/SEED-Data-Edit.

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的资源，以探索和提升图像编辑技术的教学方法。通过深入分析数据集的构成和应用，我们希望激发更多关于图像编辑教学的创新思路和实践。](../../../paper_images/2405.04007/x1.png)

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的资源，以探索和提升图像编辑技术的教学方法。通过深入分析数据集的构成和应用，我们希望激发更多关于图像编辑教学的创新思路和实践。](../../../paper_images/2405.04007/x2.png)

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的资源，以探索和提升图像编辑技术的教学方法。通过深入分析数据集的构成和应用，我们希望激发更多关于图像编辑教学的创新思路和实践。](../../../paper_images/2405.04007/x3.png)

![SEED-Data-Edit 技术报告：教学图像编辑的混合数据集探索在这份技术报告中，我们介绍了 SEED-Data-Edit，一个专为教学图像编辑而设计的混合数据集。该数据集结合了多种图像编辑任务，旨在为研究人员和开发者提供一个全面的资源，以探索和提升图像编辑技术的教学方法。通过深入分析数据集的构成和应用，我们希望激发更多关于图像编辑教学的创新思路和实践。](../../../paper_images/2405.04007/x4.png)

[Arxiv](https://arxiv.org/abs/2405.04007)