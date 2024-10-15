# EasyJudge：一款易用的工具，专为全面评估 LLM 响应而设计

发布时间：2024年10月13日

`LLM应用` `人工智能` `软件开发`

> EasyJudge: an Easy-to-use Tool for Comprehensive Response Evaluation of LLMs

# 摘要

> 近期，利用大型语言模型（LLM）评估其他 LLM 质量的趋势愈发明显。多数研究依赖于闭源的 GPT-4 模型，但其闭源特性带来了透明度、可控性和成本效益的挑战。为此，一些研究者转向开源 LLM 进行评估，但现有开源模型缺乏友好的可视化工具，且未针对加速推理优化，给资源有限或跨领域的研究者带来不便。本文推出的 EasyJudge 模型，轻巧、精准、高效且用户友好，配备直观可视化界面，便于部署与使用。通过详细数据集和精炼提示优化，EasyJudge 与人类及专有模型评估高度一致，并能在消费级 GPU 或 CPU 上高效运行。此外，我们还通过详细分析和案例研究，进一步展示了该方法的潜力。

> Recently, there has been a growing trend of employing large language models (LLMs) to judge the quality of other LLMs. Many studies have adopted closed-source models, mainly using GPT-4 as the evaluator. However, due to the closed-source nature of the GPT-4 model, employing it as an evaluator has resulted in issues including transparency, controllability, and cost-effectiveness. Some researchers have turned to using fine-tuned open-source LLMs as evaluators. However, existing open-source evaluation LLMs generally lack a user-friendly visualization tool, and they have not been optimized for accelerated model inference, which causes inconvenience for researchers with limited resources and those working across different fields. This paper presents EasyJudge, a model developed to evaluate significant language model responses. It is lightweight, precise, efficient, and user-friendly, featuring an intuitive visualization interface for ease of deployment and use. EasyJudge uses detailed datasets and refined prompts for model optimization, achieving strong consistency with human and proprietary model evaluations. The model optimized with quantitative methods enables EasyJudge to run efficiently on consumer-grade GPUs or even CPUs. We also provide detailed analysis and case studies to further reveal the potential of our method.

[Arxiv](https://arxiv.org/abs/2410.09775)