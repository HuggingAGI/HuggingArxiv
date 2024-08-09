# MM-Forecast：采用多模态技术，结合大型语言模型进行时间事件预测

发布时间：2024年08月08日

`LLM应用` `时间事件预测` `多模态学习`

> MM-Forecast: A Multimodal Approach to Temporal Event Forecasting with Large Language Models

# 摘要

> 我们探索了一个新兴且引人入胜的领域：利用大型语言模型进行多模态时间事件预测。相较于传统的文本或图形模态，图像在此领域的应用尚未充分开发，尤其是在LLM时代。为此，我们聚焦于两个核心问题：为何图像能助力时间事件预测，以及如何将图像融入LLM预测框架。为解答这些问题，我们识别了图像在预测中的两大关键作用：突出与互补。基于此，我们创新性地构建了MM-Forecast框架，通过多模态LLM将图像功能转化为文字描述，并嵌入预测模型中。为验证其效能，我们扩展了MidEast-TE-mini数据集，新增图像数据，形成MidEast-TE-mm。实证结果显示，MM-Forecast不仅能准确识别图像功能，更通过整合这些文字描述，大幅提升了预测准确性。相关资源已公开于https://github.com/LuminosityX/MM-Forecast。

> We study an emerging and intriguing problem of multimodal temporal event forecasting with large language models. Compared to using text or graph modalities, the investigation of utilizing images for temporal event forecasting has not been fully explored, especially in the era of large language models (LLMs). To bridge this gap, we are particularly interested in two key questions of: 1) why images will help in temporal event forecasting, and 2) how to integrate images into the LLM-based forecasting framework. To answer these research questions, we propose to identify two essential functions that images play in the scenario of temporal event forecasting, i.e., highlighting and complementary. Then, we develop a novel framework, named MM-Forecast. It employs an Image Function Identification module to recognize these functions as verbal descriptions using multimodal large language models (MLLMs), and subsequently incorporates these function descriptions into LLM-based forecasting models. To evaluate our approach, we construct a new multimodal dataset, MidEast-TE-mm, by extending an existing event dataset MidEast-TE-mini with images. Empirical studies demonstrate that our MM-Forecast can correctly identify the image functions, and further more, incorporating these verbal function descriptions significantly improves the forecasting performance. The dataset, code, and prompts are available at https://github.com/LuminosityX/MM-Forecast.

[Arxiv](https://arxiv.org/abs/2408.04388)