# 大型语言模型助力数学推理的多工具集成应用

发布时间：2024年08月22日

`LLM应用` `人工智能`

> Multi-tool Integration Application for Math Reasoning Using Large Language Model

# 摘要

> 数学推理在人工智能领域占据重要地位。本文创新性地提出一个多工具框架，通过大型语言模型（LLM）与多种外部工具的协同作用，旨在提升数学推理的全面性与准确性。首先，数学工具在推理过程中与LLM互动，执行基础计算。其次，代码工具生成并执行符合语法规则的代码片段，助力解决复杂数学问题。随后，CoT工具通过迭代推理，强化逻辑连贯性与准确性。最终，自一致性工具依据不同参数筛选出最终答案，增强推理的稳定性和可信度。这一框架通过工具间的协同作用，在数学推理任务中取得了显著进步。实验在NumGLUE任务4测试集上进行，包含220道填空题。结果表明，我们的方法在任务4中达到了89.09%的准确率，相较于GPT3+FewShot基线，Few Shot+ERNIE-4.0+self consistency提升了49.09%，与微调基线相比，提升了52.29%。

> Mathematical reasoning is an important research direction in the field of artificial intelligence. This article proposes a novel multi tool application framework for mathematical reasoning, aiming to achieve more comprehensive and accurate mathematical reasoning by utilizing the collaborative effect of large language models (LLMs) and multiple external tools. Firstly, use a Math Tool to perform basic mathematical calculations during the inference process through interaction with LLM. Secondly, Code Tool can generate code fragments that comply with syntax rules and execute them, providing support for complex mathematical problems. Then, through the iterative reasoning of the CoT Tool, the logical coherence and accuracy of mathematical reasoning are enhanced. Ultimately, by using self consistency tools to select the final answer based on different parameters, the consistency and reliability of reasoning are improved. Through the synergistic effect of these tools, the framework has achieved significant performance improvement in mathematical reasoning tasks. We conducted experiments on the NumGLUE Task 4 test set, which includes 220 mathematical reasoning fill in the blank questions. The experimental results showed that, based on Math Tool, Code Tool, and CoT Tool, in Task 4 task,our method achieved an accuracy of 89.09,compared with the GPT3+FewShot baseline, Few Shot+ERNIE-4.0+self consistency improved by 49.09%, and compared with fine-tuning the Fine tuning baseline, Few Shot+ERNIE-4.0+self consistency improved by 52.29%

[Arxiv](https://arxiv.org/abs/2408.12148)