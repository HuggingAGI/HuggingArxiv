# 大型语言模型中的声明性知识蒸馏技术应用于视觉问答数据集

发布时间：2024年10月12日

`LLM应用` `人工智能` `计算机视觉`

> Declarative Knowledge Distillation from Large Language Models for Visual Question Answering Datasets

# 摘要

> 视觉问答 (VQA) 任务需要处理图像并进行推理以回答问题。模块化解决方案在可解释性上优于端到端系统，但制定规则可能增加开发者负担。我们提出从大型语言模型 (LLM) 中提取声明性知识的方法，通过扩展 VQA 推理的初始理论来满足任务需求。利用 VQA 数据集示例指导 LLM，验证并修正规则。实验证明，该方法在 CLEVR 和 GQA 数据集上有效，表明从 LLM 中提取知识是一个有前景的方向。

> Visual Question Answering (VQA) is the task of answering a question about an image and requires processing multimodal input and reasoning to obtain the answer. Modular solutions that use declarative representations within the reasoning component have a clear advantage over end-to-end trained systems regarding interpretability. The downside is that crafting the rules for such a component can be an additional burden on the developer. We address this challenge by presenting an approach for declarative knowledge distillation from Large Language Models (LLMs). Our method is to prompt an LLM to extend an initial theory on VQA reasoning, given as an answer-set program, to meet the requirements of the VQA task. Examples from the VQA dataset are used to guide the LLM, validate the results, and mend rules if they are not correct by using feedback from the ASP solver. We demonstrate that our approach works on the prominent CLEVR and GQA datasets. Our results confirm that distilling knowledge from LLMs is in fact a promising direction besides data-driven rule learning approaches.

[Arxiv](https://arxiv.org/abs/2410.09428)