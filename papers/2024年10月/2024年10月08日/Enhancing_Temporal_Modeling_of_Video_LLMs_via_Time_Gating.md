# 借助时间门控技术，提升视频大型语言模型的时间建模能力

发布时间：2024年10月08日

`LLM应用` `视频分析` `人工智能`

> Enhancing Temporal Modeling of Video LLMs via Time Gating

# 摘要

> 视频大型语言模型 (Video LLMs) 在视频问答等任务上表现出色，但大多忽略了视频中的时间信息，导致时间感知理解能力不足。为此，我们设计了时间门控视频 LLM (TG-Vid)，通过创新的时间门控模块 (TG) 强化时间建模。TG 模块整合了门控空间注意力、门控时间注意力和门控 MLP，使模型能更好地捕捉视频中的时间线索。在 MVBench、TempCompass 和 NExT-QA 等时间敏感基准测试中，TG-Vid 显著超越现有模型。消融研究进一步证实，TG 模块的设计是性能提升的关键。代码已开源，详见 https://github.com/LaVi-Lab/TG-Vid。

> Video Large Language Models (Video LLMs) have achieved impressive performance on video-and-language tasks, such as video question answering. However, most existing Video LLMs neglect temporal information in video data, leading to struggles with temporal-aware video understanding. To address this gap, we propose a Time Gating Video LLM (TG-Vid) designed to enhance temporal modeling through a novel Time Gating module (TG). The TG module employs a time gating mechanism on its sub-modules, comprising gating spatial attention, gating temporal attention, and gating MLP. This architecture enables our model to achieve a robust understanding of temporal information within videos. Extensive evaluation of temporal-sensitive video benchmarks (i.e., MVBench, TempCompass, and NExT-QA) demonstrates that our TG-Vid model significantly outperforms the existing Video LLMs. Further, comprehensive ablation studies validate that the performance gains are attributed to the designs of our TG module. Our code is available at https://github.com/LaVi-Lab/TG-Vid.

[Arxiv](https://arxiv.org/abs/2410.05714)