# CompassJudger-1：全能评判模型，推动模型评估与进化

发布时间：2024年10月21日

`LLM应用` `人工智能` `开源软件`

> CompassJudger-1: All-in-one Judge Model Helps Model Evaluation and Evolution

# 摘要

> 高效的评估对 LLM 的持续进步至关重要。主观评估因其贴近实际应用和人类偏好而备受关注，但人工评估成本高且难以复现，因此精准的自动化评估器尤为重要。我们推出了首个开源的 **CompassJudger-1**，它是一个全能的 LLM，能进行单一评分、双模型比较、格式化评估、生成批评及执行多样任务。为统一评估不同判断模型的能力，我们创建了 **JudgerBench**，涵盖多种主观评估任务。CompassJudger-1 提供全面的评估解决方案，并能灵活适应各种需求。这些工具已在 https://github.com/open-compass/CompassJudger 开源，旨在促进合作，加速 LLM 评估方法的发展。

> Efficient and accurate evaluation is crucial for the continuous improvement of large language models (LLMs). Among various assessment methods, subjective evaluation has garnered significant attention due to its superior alignment with real-world usage scenarios and human preferences. However, human-based evaluations are costly and lack reproducibility, making precise automated evaluators (judgers) vital in this process. In this report, we introduce \textbf{CompassJudger-1}, the first open-source \textbf{all-in-one} judge LLM. CompassJudger-1 is a general-purpose LLM that demonstrates remarkable versatility. It is capable of: 1. Performing unitary scoring and two-model comparisons as a reward model; 2. Conducting evaluations according to specified formats; 3. Generating critiques; 4. Executing diverse tasks like a general LLM. To assess the evaluation capabilities of different judge models under a unified setting, we have also established \textbf{JudgerBench}, a new benchmark that encompasses various subjective evaluation tasks and covers a wide range of topics. CompassJudger-1 offers a comprehensive solution for various evaluation tasks while maintaining the flexibility to adapt to diverse requirements. Both CompassJudger and JudgerBench are released and available to the research community athttps://github.com/open-compass/CompassJudger. We believe that by open-sourcing these tools, we can foster collaboration and accelerate progress in LLM evaluation methodologies.

[Arxiv](https://arxiv.org/abs/2410.16256)