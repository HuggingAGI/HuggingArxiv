# LLM 能够自我检查，从而减少交通理解任务中的幻觉现象。

发布时间：2024年09月19日

`LLM应用` `人工智能`

> LLMs Can Check Their Own Results to Mitigate Hallucinations in Traffic Understanding Tasks

# 摘要

> 当今的 LLM 展示了从文本生成到图像处理的全方位卓越能力。这些模型因其处理多模态数据的能力，正被探索用于车载服务，如 ADAS 和 AD 系统中的感知任务。然而，LLM 常生成“幻觉”——无意义或不准确的信息，这是一个亟待解决的问题。本文系统探讨了 SelfCheckGPT 在三种顶尖 LLM（GPT-4o、LLaVA 和 Llama3）分析来自 Waymo 和 PREPER CITY 数据集的视觉汽车数据时，检测幻觉的效果。结果显示，GPT-4o 在生成忠实图像描述方面优于 LLaVA，但在误标非幻觉内容为幻觉方面更为宽松。此外，数据集类型对描述质量和幻觉检测效果影响不大，但模型在白天拍摄的图像上表现更佳。总体而言，SelfCheckGPT 及其适应性可有效过滤 LLM 生成的交通图像描述中的幻觉。

> Today's Large Language Models (LLMs) have showcased exemplary capabilities, ranging from simple text generation to advanced image processing. Such models are currently being explored for in-vehicle services such as supporting perception tasks in Advanced Driver Assistance Systems (ADAS) or Autonomous Driving (AD) systems, given the LLMs' capabilities to process multi-modal data. However, LLMs often generate nonsensical or unfaithful information, known as ``hallucinations'': a notable issue that needs to be mitigated. In this paper, we systematically explore the adoption of SelfCheckGPT to spot hallucinations by three state-of-the-art LLMs (GPT-4o, LLaVA, and Llama3) when analysing visual automotive data from two sources: Waymo Open Dataset, from the US, and PREPER CITY dataset, from Sweden. Our results show that GPT-4o is better at generating faithful image captions than LLaVA, whereas the former demonstrated leniency in mislabeling non-hallucinated content as hallucinations compared to the latter. Furthermore, the analysis of the performance metrics revealed that the dataset type (Waymo or PREPER CITY) did not significantly affect the quality of the captions or the effectiveness of hallucination detection. However, the models showed better performance rates over images captured during daytime, compared to during dawn, dusk or night. Overall, the results show that SelfCheckGPT and its adaptation can be used to filter hallucinations in generated traffic-related image captions for state-of-the-art LLMs.

[Arxiv](https://arxiv.org/abs/2409.12580)