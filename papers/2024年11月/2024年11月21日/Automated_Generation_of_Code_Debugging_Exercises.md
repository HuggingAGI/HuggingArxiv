# 代码调试练习的自动生成

发布时间：2024年11月21日

`LLM应用`

> Automated Generation of Code Debugging Exercises

# 摘要

> 调试是学习编程必不可少的技能，然而在入门课程里，其教学与侧重点往往大不相同。在代码生成大型语言模型（LLMs）的时代，学生推理代码和识别错误的能力愈发重要。但学生常常依靠试错法来解决错误，却未完全明白潜在问题。培养识别和假设错误成因的能力极为关键，可通过传统方式有效教学却颇为耗时。本文引入了 BugSpotter 这一创新工具，它借助 LLM 依据问题描述生成错误代码，并通过测试套件验证合成的错误。学生通过设计失败的测试用例与 BugSpotter 互动，其中错误代码的输出与问题规范所定义的预期结果不同。这不但给学生提供了提升调试技能的契机，还能让他们练习阅读和理解问题规范。我们在大教室环境中部署了 BugSpotter，并将其生成的调试练习和教师针对相同问题手工制作的练习做了对比。我们发现 BugSpotter 生成的 LLM 练习难度各异，且与问题规范高度匹配。重要的是，就学生表现而言，LLM 生成的练习与教师手动创建的练习不相上下，这表明 BugSpotter 可能是学习调试的有效且高效的辅助工具。

> Debugging is an essential skill when learning to program, yet its instruction and emphasis often vary widely across introductory courses. In the era of code-generating large language models (LLMs), the ability for students to reason about code and identify errors is increasingly important. However, students frequently resort to trial-and-error methods to resolve bugs without fully understanding the underlying issues. Developing the ability to identify and hypothesize the cause of bugs is crucial but can be time-consuming to teach effectively through traditional means. This paper introduces BugSpotter, an innovative tool that leverages an LLM to generate buggy code from a problem description and verify the synthesized bugs via a test suite. Students interact with BugSpotter by designing failing test cases, where the buggy code's output differs from the expected result as defined by the problem specification. This not only provides opportunities for students to enhance their debugging skills, but also to practice reading and understanding problem specifications. We deployed BugSpotter in a large classroom setting and compared the debugging exercises it generated to exercises hand-crafted by an instructor for the same problems. We found that the LLM-generated exercises produced by BugSpotter varied in difficulty and were well-matched to the problem specifications. Importantly, the LLM-generated exercises were comparable to those manually created by instructors with respect to student performance, suggesting that BugSpotter could be an effective and efficient aid for learning debugging.

[Arxiv](https://arxiv.org/abs/2411.14303)