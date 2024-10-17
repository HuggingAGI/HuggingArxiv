# ProSA：探索与评估 LLM 对提示的敏感性

发布时间：2024年10月16日

`LLM理论` `人工智能`

> ProSA: Assessing and Understanding the Prompt Sensitivity of LLMs

# 摘要

> 大型语言模型（LLM）虽在多任务中表现出色，但其性能对提示极为敏感，这为准确评估和用户满意度带来挑战。现有研究常忽略提示的实例级变化及其对主观评估的影响。为此，我们推出 ProSA 框架，旨在评估并理解 LLM 的提示敏感性。ProSA 引入 PromptSensiScore 指标，并利用解码信心揭示内在机制。研究发现，提示敏感性在不同数据集和模型间波动，大模型更具鲁棒性。少样本示例能缓解此问题，主观评估在复杂推理任务中也易受提示影响。此外，高模型信心与提示鲁棒性正相关。我们相信 ProSA 将成为研究 LLM 提示敏感性的有力工具。项目已发布于：https://github.com/open-compass/ProSA。

> Large language models (LLMs) have demonstrated impressive capabilities across various tasks, but their performance is highly sensitive to the prompts utilized. This variability poses challenges for accurate assessment and user satisfaction. Current research frequently overlooks instance-level prompt variations and their implications on subjective evaluations. To address these shortcomings, we introduce ProSA, a framework designed to evaluate and comprehend prompt sensitivity in LLMs. ProSA incorporates a novel sensitivity metric, PromptSensiScore, and leverages decoding confidence to elucidate underlying mechanisms. Our extensive study, spanning multiple tasks, uncovers that prompt sensitivity fluctuates across datasets and models, with larger models exhibiting enhanced robustness. We observe that few-shot examples can alleviate this sensitivity issue, and subjective evaluations are also susceptible to prompt sensitivities, particularly in complex, reasoning-oriented tasks. Furthermore, our findings indicate that higher model confidence correlates with increased prompt robustness. We believe this work will serve as a helpful tool in studying prompt sensitivity of LLMs. The project is released at: https://github.com/open-compass/ProSA .

[Arxiv](https://arxiv.org/abs/2410.12405)