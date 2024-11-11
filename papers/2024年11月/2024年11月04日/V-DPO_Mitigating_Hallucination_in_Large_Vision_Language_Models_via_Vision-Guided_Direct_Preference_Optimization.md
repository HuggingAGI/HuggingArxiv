# V-DPO：通过视觉引导的直接偏好优化减轻大型视觉语言模型中的幻觉

发布时间：2024年11月04日

`LLM应用` `计算机视觉`

> V-DPO: Mitigating Hallucination in Large Vision Language Models via Vision-Guided Direct Preference Optimization

# 摘要

> 大型视觉语言模型（LVLMs）存在幻觉问题，导致输出的文本响应与输入的视觉内容不一致。最近的研究表明，对大型语言模型（LLM）骨干的过度依赖，作为 LVLMs 产生幻觉的一个原因，本质上引入了来自语言先验的偏差，导致对视觉输入的上下文关注不足。 我们通过偏好学习减轻这种过度依赖来解决幻觉问题。我们提出了视觉引导的直接偏好优化（V-DPO），以在训练时增强视觉上下文学习。为了解释 V-DPO 在不同类型训练数据上的有效性和通用性，我们构建了一个包含响应和图像对比偏好对的合成数据集，并与现有的人工注释的幻觉样本进行比较。我们的方法在各种幻觉基准测试中与基线方法相比取得了显著的改进。我们的分析表明，V-DPO 在从图像对比偏好数据中学习方面表现出色，展示了其引发和理解视觉上下文细微差别的卓越能力。我们的代码可在 https://github.com/YuxiXie/V-DPO 公开获取。

> Large vision-language models (LVLMs) suffer from hallucination, resulting in misalignment between the output textual response and the input visual content. Recent research indicates that the over-reliance on the Large Language Model (LLM) backbone, as one cause of the LVLM hallucination, inherently introduces bias from language priors, leading to insufficient context attention to the visual inputs.
  We tackle this issue of hallucination by mitigating such over-reliance through preference learning. We propose Vision-guided Direct Preference Optimization (V-DPO) to enhance visual context learning at training time. To interpret the effectiveness and generalizability of V-DPO on different types of training data, we construct a synthetic dataset containing both response- and image-contrast preference pairs, compared against existing human-annotated hallucination samples. Our approach achieves significant improvements compared with baseline methods across various hallucination benchmarks. Our analysis indicates that V-DPO excels in learning from image-contrast preference data, demonstrating its superior ability to elicit and understand nuances of visual context. Our code is publicly available at https://github.com/YuxiXie/V-DPO.

[Arxiv](https://arxiv.org/abs/2411.02712)