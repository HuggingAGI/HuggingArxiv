# 揭秘大型语言模型编辑中的过拟合现象

发布时间：2024年10月10日

`LLM理论` `人工智能`

> Uncovering Overfitting in Large Language Model Editing

# 摘要

> 知识编辑是更新和修正 LLM 内部知识的有效手段，但在处理多跳推理等复杂任务时，现有方法往往力不从心。本文揭示了“编辑过拟合”现象：编辑后的模型对特定目标概率过高，阻碍了新知识在复杂场景中的应用。这一问题源于当前编辑范式对输入提示与编辑目标直接对应关系的过度依赖。为此，我们推出了新基准 EVOKE 和细粒度评估指标，揭示了编辑过拟合的普遍性及现有缓解策略的局限。受 LLM 知识召回机制启发，我们提出了即插即用的 LTI 策略，通过多阶段推理约束模块，使编辑模型能像未编辑 LLM 一样灵活利用新知识。实验证明，LTI 能有效缓解编辑过拟合问题。

> Knowledge editing has been proposed as an effective method for updating and correcting the internal knowledge of Large Language Models (LLMs). However, existing editing methods often struggle with complex tasks, such as multi-hop reasoning. In this paper, we identify and investigate the phenomenon of Editing Overfit, where edited models assign disproportionately high probabilities to the edit target, hindering the generalization of new knowledge in complex scenarios. We attribute this issue to the current editing paradigm, which places excessive emphasis on the direct correspondence between the input prompt and the edit target for each edit sample. To further explore this issue, we introduce a new benchmark, EVOKE (EValuation of Editing Overfit in Knowledge Editing), along with fine-grained evaluation metrics. Through comprehensive experiments and analysis, we demonstrate that Editing Overfit is prevalent in current editing methods and that common overfitting mitigation strategies are of limited effectiveness in knowledge editing. To overcome this, inspired by LLMs' knowledge recall mechanisms, we propose a new plug-and-play strategy called Learn to Inference (LTI), which introduce a Multi-stage Inference Constraint module to guide the edited models in recalling new knowledge similarly to how unedited LLMs leverage knowledge through in-context learning. Extensive experimental results across a wide range of tasks validate the effectiveness of LTI in mitigating Editing Overfit.

[Arxiv](https://arxiv.org/abs/2410.07819)