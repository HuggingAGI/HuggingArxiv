# VISUALCODER：以细粒度多模态思维链推理引导大型语言模型进行代码执行

发布时间：2024年10月30日

`LLM应用` `软件工程` `代码推理`

> VISUALCODER: Guiding Large Language Models in Code Execution with Fine-grained Multimodal Chain-of-Thought Reasoning

# 摘要

> 在软件工程领域，预测程序行为以及对代码执行进行推理一直是重大难题，尤其是对于专为代码分析打造的大型语言模型（LLMs）而言。尽管这些模型在理解静态语法时表现出众，但在动态推理任务中却常常力不从心。我们推出了 Visual Coder，这一简单却高效的方法通过融合多模态的思维链（CoT）推理与视觉控制流图（CFG），强化了代码推理能力。将代码片段与相应的 CFG 相匹配，Visual Coder 能更深入地洞察执行流程，从而更精准地预测代码行为。我们的实验表明，在代码推理任务中，用视觉 CFG 来增强 LLMs 的效果明显优于基于文本的 CFG 描述。我们借助参考机制化解了多模态 CoT 集成中的难题，保证了代码与其执行路径的一致性，进而在程序行为预测、错误检测以及输出生成等方面提升了性能。

> Predicting program behavior and reasoning about code execution remain significant challenges in software engineering, particularly for large language models (LLMs) designed for code analysis. While these models excel at understanding static syntax, they often struggle with dynamic reasoning tasks. We introduce Visual Coder, a simple yet effective approach that enhances code reasoning by integrating multimodal Chain-of-Thought (CoT) reasoning with a visual Control Flow Graph (CFG). By aligning code snippets with their corresponding CFGs, Visual Coder provides deeper insights into execution flow, enabling more accurate predictions of code behavior. Our experiments demonstrate that augmenting LLMs with visual CFGs significantly outperforms text-based CFG descriptions in code reasoning tasks. We address challenges in multimodal CoT integration through a reference mechanism, ensuring consistency between code and its execution path, thereby improving performance in program behavior prediction, error detection, and output generation.

[Arxiv](https://arxiv.org/abs/2410.23402)