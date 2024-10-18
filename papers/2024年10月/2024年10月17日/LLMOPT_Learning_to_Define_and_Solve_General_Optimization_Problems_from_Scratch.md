# LLMOPT：从零开始，学会定义并解决通用优化问题

发布时间：2024年10月17日

`LLM应用` `自动化`

> LLMOPT: Learning to Define and Solve General Optimization Problems from Scratch

# 摘要

> 优化问题无处不在，但由自然语言描述的优化问题往往需要专家介入，限制了其广泛应用。为此，我们提出LLMOPT，一个利用大型语言模型（LLM）的自动化优化框架。LLMOPT通过五元素公式和多指令调优，不仅提升了问题定义和求解的准确性，还增强了模型的泛化能力。为避免LLM的幻觉问题，我们引入了模型对齐和自我修正机制。实验表明，LLMOPT在多个领域的表现优于现有方法，平均求解准确性提升了11.08%。代码已开源，详见https://github.com/caigaojiang/LLMOPT。

> Optimization problems are prevalent across various scenarios. Formulating and then solving optimization problems described by natural language often requires highly specialized human expertise, which could block the widespread application of optimization-based decision making. To make problem formulating and solving automated, leveraging large language models (LLMs) has emerged as a potential way. However, this kind of way suffers from the issue of optimization generalization. Namely, the accuracy of most current LLM-based methods and the generality of optimization problem types that they can model are still limited. In this paper, we propose a unified learning-based framework called LLMOPT to boost optimization generalization. Starting from the natural language descriptions of optimization problems and a pre-trained LLM, LLMOPT constructs the introduced five-element formulation as a universal model for learning to define diverse optimization problem types. Then, LLMOPT employs the multi-instruction tuning to enhance both problem formalization and solver code generation accuracy and generality. After that, to prevent hallucinations in LLMs, such as sacrificing solving accuracy to avoid execution errors, model alignment and self-correction mechanism are adopted in LLMOPT. We evaluate the optimization generalization ability of LLMOPT and compared methods across six real-world datasets covering roughly 20 fields such as health, environment, energy and manufacturing, etc. Extensive experiment results show that LLMOPT is able to model various optimization problem types such as linear/nonlinear programming, mixed integer programming and combinatorial optimization, and achieves a notable 11.08% average solving accuracy improvement compared with the state-of-the-art methods. The code is available at https://github.com/caigaojiang/LLMOPT.

[Arxiv](https://arxiv.org/abs/2410.13213)