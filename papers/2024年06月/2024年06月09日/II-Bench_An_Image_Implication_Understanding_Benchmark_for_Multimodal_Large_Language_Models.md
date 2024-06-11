# II-Bench：多模态大型语言模型的图像含义理解基准

发布时间：2024年06月09日

`LLM应用

这篇论文主要探讨了多模态大型语言模型（MLLMs）在图像蕴含理解基准（II-Bench）上的表现，并分析了这些模型在处理高阶感知任务时的局限性。论文通过实验评估了MLLMs在理解图像高级语义和情感极性方面的能力，并提出了改进的方向。因此，这篇论文属于LLM应用类别，因为它关注的是大型语言模型在特定任务上的应用和性能评估。` `人工智能` `图像理解`

> II-Bench: An Image Implication Understanding Benchmark for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）的迅猛发展在各类基准测试中屡创佳绩。为了更精准地衡量这些模型的能力，众多挑战性且全面的基准应运而生。然而，MLLMs的高阶感知能力尚未得到充分探索。为此，我们推出了图像蕴含理解基准（II-Bench），旨在检验模型对图像高阶感知的深度。通过在多个MLLMs上对II-Bench进行深入实验，我们获得了重要洞见。首先，MLLMs在II-Bench上的表现与人类相比存在明显差距，其最高准确率为74.8%，而人类平均准确率达90%，峰值高达98%。其次，面对抽象与复杂的图像，MLLMs表现不佳，显示出其在理解高级语义及捕捉图像细节上的局限。最后，当提示中融入图像情感极性时，多数模型的准确率有所提升，这揭示了它们在图像情感理解上的内在缺陷。我们期待II-Bench能激发社区开发新一代MLLMs，推动我们向着专家级人工通用智能（AGI）迈进。II-Bench现已公开，地址为https://huggingface.co/datasets/m-a-p/II-Bench。

> The rapid advancements in the development of multimodal large language models (MLLMs) have consistently led to new breakthroughs on various benchmarks. In response, numerous challenging and comprehensive benchmarks have been proposed to more accurately assess the capabilities of MLLMs. However, there is a dearth of exploration of the higher-order perceptual capabilities of MLLMs. To fill this gap, we propose the Image Implication understanding Benchmark, II-Bench, which aims to evaluate the model's higher-order perception of images. Through extensive experiments on II-Bench across multiple MLLMs, we have made significant findings. Initially, a substantial gap is observed between the performance of MLLMs and humans on II-Bench. The pinnacle accuracy of MLLMs attains 74.8%, whereas human accuracy averages 90%, peaking at an impressive 98%. Subsequently, MLLMs perform worse on abstract and complex images, suggesting limitations in their ability to understand high-level semantics and capture image details. Finally, it is observed that most models exhibit enhanced accuracy when image sentiment polarity hints are incorporated into the prompts. This observation underscores a notable deficiency in their inherent understanding of image sentiment. We believe that II-Bench will inspire the community to develop the next generation of MLLMs, advancing the journey towards expert artificial general intelligence (AGI). II-Bench is publicly available at https://huggingface.co/datasets/m-a-p/II-Bench.

[Arxiv](https://arxiv.org/abs/2406.05862)