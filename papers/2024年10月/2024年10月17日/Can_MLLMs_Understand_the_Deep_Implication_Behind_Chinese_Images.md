# MLLMs 能洞悉中文图像的深层含义吗？

发布时间：2024年10月17日

`LLM应用` `人工智能` `文化研究`

> Can MLLMs Understand the Deep Implication Behind Chinese Images?

# 摘要

> 随着多模态大型语言模型 (MLLM) 的不断进步，对其高阶能力的评估需求日益增长。然而，目前缺乏对中国视觉内容的高阶感知和理解的研究。为此，我们推出了 **CII-Bench**，一个专门评估 MLLM 对中国图像高阶感知和理解能力的基准。CII-Bench 在多个方面超越了现有基准：图像源自中国互联网并经人工审查，答案也由人工精心制作；同时，它还包含了中国传统文化的图像，如传统绘画，以深入测试模型对中国文化的理解。实验结果显示，MLLM 在 CII-Bench 上的表现与人类存在显著差距，最高准确率为 64.4%，而人类平均为 78.2%，最高达 81.0%。此外，MLLM 在中国传统文化图像上的表现较差，显示出其在高级语义理解和传统文化知识方面的不足。有趣的是，加入图像情感提示后，大多数模型的准确率有所提升。我们相信，CII-Bench 将助力 MLLM 更深入地理解中国语义和中国特有的图像，推动向专家级人工通用智能 (AGI) 的迈进。项目网址：https://cii-bench.github.io/。

> As the capabilities of Multimodal Large Language Models (MLLMs) continue to improve, the need for higher-order capability evaluation of MLLMs is increasing. However, there is a lack of work evaluating MLLM for higher-order perception and understanding of Chinese visual content. To fill the gap, we introduce the **C**hinese **I**mage **I**mplication understanding **Bench**mark, **CII-Bench**, which aims to assess the higher-order perception and understanding capabilities of MLLMs for Chinese images. CII-Bench stands out in several ways compared to existing benchmarks. Firstly, to ensure the authenticity of the Chinese context, images in CII-Bench are sourced from the Chinese Internet and manually reviewed, with corresponding answers also manually crafted. Additionally, CII-Bench incorporates images that represent Chinese traditional culture, such as famous Chinese traditional paintings, which can deeply reflect the model's understanding of Chinese traditional culture. Through extensive experiments on CII-Bench across multiple MLLMs, we have made significant findings. Initially, a substantial gap is observed between the performance of MLLMs and humans on CII-Bench. The highest accuracy of MLLMs attains 64.4%, where as human accuracy averages 78.2%, peaking at an impressive 81.0%. Subsequently, MLLMs perform worse on Chinese traditional culture images, suggesting limitations in their ability to understand high-level semantics and lack a deep knowledge base of Chinese traditional culture. Finally, it is observed that most models exhibit enhanced accuracy when image emotion hints are incorporated into the prompts. We believe that CII-Bench will enable MLLMs to gain a better understanding of Chinese semantics and Chinese-specific images, advancing the journey towards expert artificial general intelligence (AGI). Our project is publicly available at https://cii-bench.github.io/.

[Arxiv](https://arxiv.org/abs/2410.13854)