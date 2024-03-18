# [Semi-Instruct 方法旨在弥合自然指令与自我指令之间的鸿沟，以提升代码大型语言模型的表现。它通过结合两种教学模式的优势，探索在代码理解和生成任务中更高效地引导大型语言模型的新途径。]

发布时间：2024年03月01日

`LLM应用`

> Semi-Instruct: Bridging Natural-Instruct and Self-Instruct for Code Large Language Models

> 在Code LLMs中进行程序合成任务时，指令调优至关重要。目前主要有两种收集调优数据的方式：基于自然指令的人类编写方式与基于自我指令的自动产生方式。自然指令虽包含多样、正确的代码实例，却欠缺指令与代码对应关系，且可能出现嵌套单行代码等不规范格式。而自我指令能自动生成配对数据，却又受限于生成重复内容导致多样性偏低，同时不能保证生成代码的准确性。为此，我们提出一种名为\textbf{半指令（Semi-Instruct）}的新方案，该方案借鉴自我指令的方式，先将源自自然指令的多样而不规范的代码转化为合适的指令-代码对。为了验证生成代码的有效性，我们创新地设计了一种构建测试用例的方法——通过生成输入样例并执行自然指令中的正确代码来得到预期输出。最后，筛选出多样且正确的指令-代码对用于指令调优。实验证明，半指令方法明显优于自然指令和自我指令，并且其性能随数据规模的增长而持续提高。

> Instruction tuning plays a pivotal role in Code Large Language Models (Code LLMs) for the task of program synthesis. Presently, two dominant paradigms for collecting tuning data are natural-instruct (human-written) and self-instruct (automatically generated). Natural-instruct includes diverse and correct codes but lacks instruction-code pairs, and exists improper code formats like nested single-line codes. In contrast, self-instruct automatically generates proper paired data. However, it suffers from low diversity due to generating duplicates and cannot ensure the correctness of codes. To bridge the both paradigms, we propose \textbf{Semi-Instruct}. It first converts diverse but improper codes from natural-instruct into proper instruction-code pairs through a method similar to self-instruct. To verify the correctness of generated codes, we design a novel way to construct test cases by generating cases' inputs and executing correct codes from natural-instruct to get outputs. Finally, diverse and correct instruction-code pairs are retained for instruction tuning. Experiments show that semi-instruct is significantly better than natural-instruct and self-instruct. Furthermore, the performance steadily improves as data scale increases.

[Arxiv](https://arxiv.org/abs/2403.00338)