# GPT-4Vision引导下的自动化放射治疗规划

发布时间：2024年06月21日

`LLM应用

理由：这篇论文介绍了一个名为GPT-RadPlan的全自动治疗计划框架，该框架利用了大型语言模型（如GPT-4Vision）中的知识来辅助放射治疗计划的制定。这个应用展示了如何将大型语言模型应用于特定的医疗领域，以提高治疗计划的效率和质量。因此，它属于LLM应用类别。` `放射肿瘤学` `医疗自动化`

> Automated radiotherapy treatment planning guided by GPT-4Vision

# 摘要

> 放射治疗计划的制定既耗时又可能主观，需要不断调整模型参数以平衡多重冲突目标。近期，大型基础模型的进步为解决这些挑战提供了新思路。本研究推出的GPT-RadPlan，是一个全自动治疗计划框架，它利用了如OpenAI的GPT-4Vision等多模态大型语言模型中蕴含的放射肿瘤学知识。GPT-RadPlan通过上下文学习，将临床协议融入其中，模拟专家规划者的行为，有效指导治疗计划的制定。我们通过API将其集成到内部逆向治疗计划系统中，并通过多个前列腺癌和头颈癌案例展示了其效果，与临床计划相比，GPT-RadPlan在目标覆盖和风险器官保护方面表现出色。GPT-RadPlan不仅满足了临床协议的剂量学要求，还首次实现了无需额外培训的自动化治疗计划，展现了其在放射肿瘤学领域的巨大潜力。

> Radiotherapy treatment planning is a time-consuming and potentially subjective process that requires the iterative adjustment of model parameters to balance multiple conflicting objectives. Recent advancements in large foundation models offer promising avenues for addressing the challenges in planning and clinical decision-making. This study introduces GPT-RadPlan, a fully automated treatment planning framework that harnesses prior radiation oncology knowledge encoded in multi-modal large language models, such as GPT-4Vision (GPT-4V) from OpenAI. GPT-RadPlan is made aware of planning protocols as context and acts as an expert human planner, capable of guiding a treatment planning process. Via in-context learning, we incorporate clinical protocols for various disease sites as prompts to enable GPT-4V to acquire treatment planning domain knowledge. The resulting GPT-RadPlan agent is integrated into our in-house inverse treatment planning system through an API. The efficacy of the automated planning system is showcased using multiple prostate and head & neck cancer cases, where we compared GPT-RadPlan results to clinical plans. In all cases, GPT-RadPlan either outperformed or matched the clinical plans, demonstrating superior target coverage and organ-at-risk sparing. Consistently satisfying the dosimetric objectives in the clinical protocol, GPT-RadPlan represents the first multimodal large language model agent that mimics the behaviors of human planners in radiation oncology clinics, achieving remarkable results in automating the treatment planning process without the need for additional training.

![GPT-4Vision引导下的自动化放射治疗规划](../../../paper_images/2406.15609/treament_plan_overview_o.png)

![GPT-4Vision引导下的自动化放射治疗规划](../../../paper_images/2406.15609/prostate.png)

![GPT-4Vision引导下的自动化放射治疗规划](../../../paper_images/2406.15609/hn.png)

![GPT-4Vision引导下的自动化放射治疗规划](../../../paper_images/2406.15609/rel.png)

![GPT-4Vision引导下的自动化放射治疗规划](../../../paper_images/2406.15609/traj_prostate.png)

![GPT-4Vision引导下的自动化放射治疗规划](../../../paper_images/2406.15609/traj_hn.png)

[Arxiv](https://arxiv.org/abs/2406.15609)