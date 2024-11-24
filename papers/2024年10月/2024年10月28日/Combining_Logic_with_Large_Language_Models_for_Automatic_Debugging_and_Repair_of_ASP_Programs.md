# 通过将逻辑与大型语言模型相融合，实现 ASP 程序的自动调试与修复

发布时间：2024年10月28日

`LLM应用` `程序调试`

> Combining Logic with Large Language Models for Automatic Debugging and Repair of ASP Programs

# 摘要

> 逻辑程序是解决 NP-Hard 问题的有力手段。不过，因其声明式的特性，调试逻辑程序颇具挑战。和能够逐步检查程序状态的过程式范例不同，逻辑程序需要通过对逻辑语句的推理来定位故障。在学习环境中，由于学生经验不足，这种复杂性更甚。
  我们推出了 FormHe，这一新型工具融合了基于逻辑的技术与大型语言模型，能够识别并纠正答案集编程提交中的问题。FormHe 包含两个组件：故障定位模块和程序修复模块。首先，故障定位器会找出一组需要修改的错误程序语句。接着，FormHe 运用程序变异技术和大型语言模型来修复有缺陷的 ASP 程序。这些修复可作为学生校正其程序的指引。
  针对学生提交的实际有问题的程序所做的实验显示，FormHe 能在 94%的情形中准确检测出故障，并成功修复 58%的错误提交。

> Logic programs are a powerful approach for solving NP-Hard problems. However, due to their declarative nature, debugging logic programs poses significant challenges. Unlike procedural paradigms, which allow for step-by-step inspection of program state, logic programs require reasoning about logical statements for fault localization. This complexity is amplified in learning environments due to students' inexperience.
  We introduce FormHe, a novel tool that combines logic-based techniques and Large Language Models to identify and correct issues in Answer Set Programming submissions. FormHe consists of two components: a fault localization module and a program repair module. First, the fault localizer identifies a set of faulty program statements requiring modification. Subsequently, FormHe employs program mutation techniques and Large Language Models to repair the flawed ASP program. These repairs can then serve as guidance for students to correct their programs.
  Our experiments with real buggy programs submitted by students show that FormHe accurately detects faults in 94% of cases and successfully repairs 58% of incorrect submissions.

[Arxiv](https://arxiv.org/abs/2410.20962)