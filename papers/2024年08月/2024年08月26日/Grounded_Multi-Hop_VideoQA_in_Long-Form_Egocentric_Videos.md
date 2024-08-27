# 长篇自我视角视频中的基础多跳视频问答

发布时间：2024年08月26日

`LLM应用` `视频处理` `问答系统`

> Grounded Multi-Hop VideoQA in Long-Form Egocentric Videos

# 摘要

> 本文探讨了长篇自我视角视频中的多跳视频问答（MH-VidQA）挑战。该任务不仅要求解答视觉问题，还需在视频中精准定位多个关键时间点作为视觉证据。为此，我们设计了一套自动化流程，生成包含时间证据的多跳问答对，助力构建大规模指令调优数据集。同时，我们精心打造了MultiHop-EgoQA这一高质量基准，通过人工验证与优化，以监测任务进展。实验表明，现有多模态系统在多跳定位与推理方面存在不足，性能欠佳。为此，我们创新提出GeLM架构，通过集成定位模块，利用灵活定位标记从视频中提取时间证据，显著提升多模态大型语言模型的多跳定位与推理能力，为该难题树立新标杆。此外，该架构在第三人称视角视频训练下，亦在单跳视频问答基准ActivityNet-RTL上创下佳绩，彰显其广泛适用性与高效性。

> This paper considers the problem of Multi-Hop Video Question Answering (MH-VidQA) in long-form egocentric videos. This task not only requires to answer visual questions, but also to localize multiple relevant time intervals within the video as visual evidences. We develop an automated pipeline to create multi-hop question-answering pairs with associated temporal evidence, enabling to construct a large-scale dataset for instruction-tuning. To monitor the progress of this new task, we further curate a high-quality benchmark, MultiHop-EgoQA, with careful manual verification and refinement. Experimental results reveal that existing multi-modal systems exhibit inadequate multi-hop grounding and reasoning abilities, resulting in unsatisfactory performance. We then propose a novel architecture, termed as Grounding Scattered Evidence with Large Language Model (GeLM), that enhances multi-modal large language models (MLLMs) by incorporating a grounding module to retrieve temporal evidence from videos using flexible grounding tokens. Trained on our visual instruction data, GeLM demonstrates improved multi-hop grounding and reasoning capabilities, setting a new baseline for this challenging task. Furthermore, when trained on third-person view videos, the same architecture also achieves state-of-the-art performance on the single-hop VidQA benchmark, ActivityNet-RTL, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2408.14469)