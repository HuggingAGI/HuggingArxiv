# 无代码协作机器人编程新探索：借助大型代码模型实现对话式代码生成实验

发布时间：2024年09月17日

`LLM应用` `制造业` `机器人`

> Towards No-Code Programming of Cobots: Experiments with Code Synthesis by Large Code Models for Conversational Programming

# 摘要

> 尽管家庭机器人研究火热，但目前多数机器人仍活跃于车间，人机互动也多在此发生。传统“协作机器人”（cobots）需专家编程，灵活性受限。为此，我们引入大型语言模型（LLMs），特别是其上下文学习能力，用于对话代码生成。首先，我们定义了RATS，即“重复装配任务”，为模拟工业装配场景奠定基础。在此任务中，程序员用自然语言指导cobot完成装配。我们创建了包含目标结构与示例指令、代码的数据集，系统评估LLMs的代码合成能力。结果显示，LLMs能生成准确的一阶代码，但在高阶代码（如函数、循环）生成上仍有不足。

> While there has been a lot of research recently on robots in household environments, at the present time, most robots in existence can be found on shop floors, and most interactions between humans and robots happen there. ``Collaborative robots'' (cobots) designed to work alongside humans on assembly lines traditionally require expert programming, limiting ability to make changes, or manual guidance, limiting expressivity of the resulting programs. To address these limitations, we explore using Large Language Models (LLMs), and in particular, their abilities of doing in-context learning, for conversational code generation. As a first step, we define RATS, the ``Repetitive Assembly Task'', a 2D building task designed to lay the foundation for simulating industry assembly scenarios. In this task, a `programmer' instructs a cobot, using natural language, on how a certain assembly is to be built; that is, the programmer induces a program, through natural language. We create a dataset that pairs target structures with various example instructions (human-authored, template-based, and model-generated) and example code. With this, we systematically evaluate the capabilities of state-of-the-art LLMs for synthesising this kind of code, given in-context examples. Evaluating in a simulated environment, we find that LLMs are capable of generating accurate `first order code' (instruction sequences), but have problems producing `higher-order code' (abstractions such as functions, or use of loops).

[Arxiv](https://arxiv.org/abs/2409.11041)