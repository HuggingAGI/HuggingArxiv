# 细微错误不容忽视：借助错误注入的自编辑实现偏好学习

发布时间：2024年10月09日

`LLM应用` `人工智能`

> Subtle Errors Matter: Preference Learning via Error-injected Self-editing

# 摘要

> 大型语言模型（LLM）在数学推理和计算方面表现出色，从基础算术到高级竞赛题都能应对自如。然而，频繁出现的细微错误，如计算失误或替换错误，限制了其数学潜力的充分发挥。现有研究多通过从更强的LLM中提取推理技能或应用偏好学习来提升数学能力，但这些方法往往忽视了那些频繁出现的细微错误。原因在于，采样的偏好对中常包含与错误无关的差异，分散了模型对细微错误的注意力。为此，我们提出了一个名为eRror-Injected Self-Editing（RISE）的新型偏好学习框架。RISE通过在正确解决方案的部分标记中注入预定义的细微错误，构建硬对以缓解错误。具体来说，RISE利用模型自身对解决方案中的少量标记进行编辑，注入设计好的细微错误。然后，结合自我编辑的解决方案及其正确版本，以及通过采样获得的正确与错误解决方案对，进行细微错误感知的DPO训练。与其它偏好学习方法相比，RISE更专注于预定义的错误及其标记，无需细粒度采样或偏好注释。实验结果表明，RISE在Qwen2-7B-Instruct上的偏好学习显著提升了GSM8K和MATH任务的表现，分别提高了3.0%和7.9%。

> Large Language Models (LLMs) have exhibited strong mathematical reasoning and computational prowess, tackling tasks ranging from basic arithmetic to advanced competition-level problems. However, frequently occurring subtle errors, such as miscalculations or incorrect substitutions, limit the models' full mathematical potential. Existing studies to improve mathematical ability typically involve distilling reasoning skills from stronger LLMs or applying preference learning to step-wise response pairs. Although these methods leverage samples of varying granularity to mitigate reasoning errors, they overlook the frequently occurring subtle errors. A major reason is that sampled preference pairs involve differences unrelated to the errors, which may distract the model from focusing on subtle errors. In this work, we propose a novel preference learning framework called eRror-Injected Self-Editing (RISE), which injects predefined subtle errors into partial tokens of correct solutions to construct hard pairs for error mitigation. In detail, RISE uses the model itself to edit a small number of tokens in the solution, injecting designed subtle errors. Then, pairs composed of self-edited solutions and their corresponding correct ones, along with pairs of correct and incorrect solutions obtained through sampling, are used together for subtle error-aware DPO training. Compared with other preference learning methods, RISE further refines the training objective to focus on predefined errors and their tokens, without requiring fine-grained sampling or preference annotation. Extensive experiments validate the effectiveness of RISE, with preference learning on Qwen2-7B-Instruct yielding notable improvements of 3.0% on GSM8K and 7.9% on MATH.

[Arxiv](https://arxiv.org/abs/2410.06638)