# 思考、编程、纠正：运用大型语言模型实现三维情境推理

发布时间：2024年04月22日

`分类：LLM应用

这篇论文提出了一个名为LLM-TPC的创新框架，它利用大型语言模型（LLMs）在视觉推理领域的成功应用，通过“思考-编程-修正”循环来解决3D情境推理问题。这个框架充分发挥了LLMs的规划、工具使用和反思功能，以解决在三维环境中根据第一人称视角的观察回答疑问的任务。论文中提到的实验和分析显示了该方法的有效性、可解释性和鲁棒性，并且代码已经公开发布。因此，这篇论文属于LLM应用类别。` `3D视觉` `人工智能`

> Think-Program-reCtify: 3D Situated Reasoning with Large Language Models

# 摘要

> 本研究致力于解决3D情境推理问题，即在三维环境中根据第一人称视角的观察回答疑问。这一任务颇具挑战，因为它需依赖全面的三维感知和复杂的推理技巧。传统的端到端模型在3D情境推理上受限于数据匮乏和泛化能力不足。借鉴于大型语言模型（LLMs）在视觉推理领域的成功应用，我们提出了LLM-TPC，这是一个创新框架，通过“思考-编程-修正”循环充分发挥LLMs的规划、工具使用和反思功能。在思考阶段，将复杂问题细化为步骤序列；编程阶段则将每个步骤转化为代码，并调用定制的3D视觉感知模块；若程序执行失败，修正阶段将对计划和代码进行调整。在SQA3D基准测试中的实验与分析显示了我们方法的有效性、可解释性和鲁棒性。我们的代码已在 https://qingrongh.github.io/LLM-TPC/ 公开发布。

> This work addresses the 3D situated reasoning task which aims to answer questions given egocentric observations in a 3D environment. The task remains challenging as it requires comprehensive 3D perception and complex reasoning skills. End-to-end models trained on supervised data for 3D situated reasoning suffer from data scarcity and generalization ability. Inspired by the recent success of leveraging large language models (LLMs) for visual reasoning, we propose LLM-TPC, a novel framework that leverages the planning, tool usage, and reflection capabilities of LLMs through a ThinkProgram-reCtify loop. The Think phase first decomposes the compositional question into a sequence of steps, and then the Program phase grounds each step to a piece of code and calls carefully designed 3D visual perception modules. Finally, the Rectify phase adjusts the plan and code if the program fails to execute. Experiments and analysis on the SQA3D benchmark demonstrate the effectiveness, interpretability and robustness of our method. Our code is publicly available at https://qingrongh.github.io/LLM-TPC/.

[Arxiv](https://arxiv.org/abs/2404.14705)