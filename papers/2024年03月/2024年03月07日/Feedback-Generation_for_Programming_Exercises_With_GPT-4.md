# GPT-4 在编程练习中助力生成针对性反馈

发布时间：2024年03月07日

`LLM应用`

> Feedback-Generation for Programming Exercises With GPT-4

> 随着LLMs及相关应用的广泛应用，已有多项研究探索它们在高等教育中辅助教师与支持学生学习的可能性。诸如Codex、GPT-3.5以及最新版GPT 4等模型，在大型编程课堂上展现出了巨大的潜能，能够及时且规模化地为学生提供反馈和建议。本论文专注于探究当输入同时包含编程任务说明和学生实际提交代码时，GPT-4 Turbo对于此类提示生成的反馈质量。我们挑选了两份初级编程课程的作业，并让GPT-4针对55份随机抽取的真实学生编程作业进行反馈生成。通过正确性、个性化程度、错误定位等多个维度对生成反馈进行了细致分析。相比前人研究及对GPT-3.5的分析，GPT-4 Turbo展现出明显的进步，如生成的反馈更具结构性和一致性，甚至能精准揪出学生程序输出中的大小写格式错误。有时，反馈还包含了学生的程序运行结果。不过，也存在反馈矛盾的情况，比如认为提交内容正确却仍需修复某个错误。这项研究进一步丰富了我们对LLMs潜力、局限性的认知，以及如何将它们更好地融入电子测评系统、教学实践以及指导使用基于GPT-4应用的学生之中。

> Ever since Large Language Models (LLMs) and related applications have become broadly available, several studies investigated their potential for assisting educators and supporting students in higher education. LLMs such as Codex, GPT-3.5, and GPT 4 have shown promising results in the context of large programming courses, where students can benefit from feedback and hints if provided timely and at scale. This paper explores the quality of GPT-4 Turbo's generated output for prompts containing both the programming task specification and a student's submission as input. Two assignments from an introductory programming course were selected, and GPT-4 was asked to generate feedback for 55 randomly chosen, authentic student programming submissions. The output was qualitatively analyzed regarding correctness, personalization, fault localization, and other features identified in the material. Compared to prior work and analyses of GPT-3.5, GPT-4 Turbo shows notable improvements. For example, the output is more structured and consistent. GPT-4 Turbo can also accurately identify invalid casing in student programs' output. In some cases, the feedback also includes the output of the student program. At the same time, inconsistent feedback was noted such as stating that the submission is correct but an error needs to be fixed. The present work increases our understanding of LLMs' potential, limitations, and how to integrate them into e-assessment systems, pedagogical scenarios, and instructing students who are using applications based on GPT-4.

[Arxiv](https://arxiv.org/abs/2403.04449)