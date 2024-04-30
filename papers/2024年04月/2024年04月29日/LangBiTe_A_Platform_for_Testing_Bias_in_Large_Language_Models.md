# LangBiTe：大型语言模型偏见检测的实验平台

发布时间：2024年04月29日

`分类：LLM应用` `人工智能` `道德与偏见检测`

> LangBiTe: A Platform for Testing Bias in Large Language Models

# 摘要

> 大型语言模型（LLMs）的广泛应用可能带来偏见问题，因为它们通常基于网络论坛、网站、社交媒体等来源的海量数据进行训练，这些数据可能包含有害或歧视性内容。为此，我们引入了LangBiTe，这是一个系统化的测试平台，旨在检测LLM中的偏见。该平台允许开发团队根据自定义的道德标准，设计测试场景并自动生成及执行测试案例。每项测试都包括向LLM输入的提示和一个测试预言机，后者将分析LLM的回应，以识别潜在的偏见。LangBiTe不仅为用户评估LLM的偏见情况，还提供了从初始道德要求到最终洞察的完整追溯链。

> The integration of Large Language Models (LLMs) into various software applications raises concerns about their potential biases. Typically, those models are trained on a vast amount of data scrapped from forums, websites, social media and other internet sources, which may instill harmful and discriminating behavior into the model. To address this issue, we present LangBiTe, a testing platform to systematically assess the presence of biases within an LLM. LangBiTe enables development teams to tailor their test scenarios, and automatically generate and execute the test cases according to a set of user-defined ethical requirements. Each test consists of a prompt fed into the LLM and a corresponding test oracle that scrutinizes the LLM's response for the identification of biases. LangBite provides users with the bias evaluation of LLMs, and end-to-end traceability between the initial ethical requirements and the insights obtained.

[Arxiv](https://arxiv.org/abs/2404.18558)