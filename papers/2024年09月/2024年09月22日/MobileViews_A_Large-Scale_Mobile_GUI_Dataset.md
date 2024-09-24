# MobileViews：一款大规模的移动界面数据集

发布时间：2024年09月22日

`LLM应用` `移动设备` `人工智能`

> MobileViews: A Large-Scale Mobile GUI Dataset

# 摘要

> 移动屏幕助手通过解读屏幕并响应用户需求，助力智能手机用户。然而，屏幕上繁多的私人信息要求小型设备模型来驱动这些助手。目前，缺乏一个全面且多样化的移动屏幕数据集来训练和提升这些模型。为此，我们采用 LLM 增强的自动应用遍历工具，减少人工干预，并利用两个 SoC 集群构建高保真移动环境，涵盖 200 多个 Android 实例，以并行处理应用交互。通过收集 81,600 设备小时的屏幕数据，我们推出了 MobileViews，这是最大的移动屏幕数据集，包含超过 60 万张截图和视图层次结构，来自 2 万多个现代 Android 应用。我们在 MobileViews 和 Rico 数据集上训练了 SOTA 多模态 LLM，验证了 MobileViews 在提升移动屏幕助手性能方面的显著优势。该数据集将全面开源。

> Mobile screen assistants help smartphone users by interpreting mobile screens and responding to user requests. The excessive private information on mobile screens necessitates small, on-device models to power these assistants. However, there is a lack of a comprehensive and large-scale mobile screen dataset with high diversity to train and enhance these models. To efficiently construct such a dataset, we utilize an LLM-enhanced automatic app traversal tool to minimize human intervention. We then employ two SoC clusters to provide high-fidelity mobile environments, including more than 200 Android instances to parallelize app interactions. By utilizing the system to collect mobile screens over 81,600 device-hours, we introduce MobileViews, the largest mobile screen dataset, which includes over 600K screenshot-view hierarchy pairs from more than 20K modern Android apps. We demonstrate the effectiveness of MobileViews by training SOTA multimodal LLMs that power mobile screen assistants on it and the Rico dataset, which was introduced seven years ago. Evaluation results on mobile screen tasks show that the scale and quality of mobile screens in MobileViews demonstrate significant advantages over Rico in augmenting mobile screen assistants. The dataset will be fully open-sourced.

[Arxiv](https://arxiv.org/abs/2409.14337)