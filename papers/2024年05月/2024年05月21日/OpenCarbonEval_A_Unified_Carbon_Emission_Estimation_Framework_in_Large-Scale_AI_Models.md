# OpenCarbonEval：大型AI模型中的统一碳排放评估框架

发布时间：2024年05月21日

`LLM应用

这篇论文介绍了OpenCarbonEval框架，这是一个用于评估大规模自回归模型（如在文本和视频生成任务中使用的模型）的环境影响的工具。该框架特别关注这些模型的碳足迹，通过动态吞吐量建模来精确预测训练过程中的碳排放。这种方法有助于AI服务提供商和用户更好地理解和管理这些模型的环境影响，从而推动AI技术的可持续发展。因此，这篇论文属于LLM应用分类，因为它提供了一个实际的工具和方法来应用LLM技术，并关注其环境影响。` `人工智能` `环境保护`

> OpenCarbonEval: A Unified Carbon Emission Estimation Framework in Large-Scale AI Models

# 摘要

> 近年来，大规模自回归模型在文本和视频生成等任务中取得了显著进步，但其环境影响却鲜少被关注，尤其是缺乏对其碳足迹的评估与分析。为此，我们推出了OpenCarbonEval框架，旨在整合多种模态的大规模模型，预测其碳排放，从而帮助AI服务提供商和用户预估排放，减轻环境压力。该框架采用动态吞吐量建模，精确捕捉训练中的工作负载和硬件波动，以更准确地预测排放。评估显示，OpenCarbonEval在预测视觉和语言模型的碳排放方面表现卓越，有助于推动AI的可持续发展，减少环境影响，为AI社区打造一个更加负责任的未来。

> In recent years, large-scale auto-regressive models have made significant progress in various tasks, such as text or video generation. However, the environmental impact of these models has been largely overlooked, with a lack of assessment and analysis of their carbon footprint. To address this gap, we introduce OpenCarbonEval, a unified framework for integrating large-scale models across diverse modalities to predict carbon emissions, which could provide AI service providers and users with a means to estimate emissions beforehand and help mitigate the environmental pressure associated with these models. In OpenCarbonEval, we propose a dynamic throughput modeling approach that could capture workload and hardware fluctuations in the training process for more precise emissions estimates. Our evaluation results demonstrate that OpenCarbonEval can more accurately predict training emissions than previous methods, and can be seamlessly applied to different modal tasks. Specifically, we show that OpenCarbonEval achieves superior performance in predicting carbon emissions for both visual models and language models. By promoting sustainable AI development and deployment, OpenCarbonEval can help reduce the environmental impact of large-scale models and contribute to a more environmentally responsible future for the AI community.

[Arxiv](https://arxiv.org/abs/2405.12843)