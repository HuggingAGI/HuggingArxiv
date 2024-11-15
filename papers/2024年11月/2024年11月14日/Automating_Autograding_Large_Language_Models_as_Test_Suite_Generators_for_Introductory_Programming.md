# 自动化自动评分：大型语言模型充当入门编程的测试套件生成工具

发布时间：2024年11月14日

`LLM应用`

> Automating Autograding: Large Language Models as Test Suite Generators for Introductory Programming

# 摘要

> 自动评分的编程作业能给学生即时反馈，还能大幅缩短教师手动评分的时间。但在自动评分器里为编程问题打造全面的测试用例集，既费时间又复杂。定义测试用例集所需的精力，可能让一些教师不再新增问题，或者导致测试覆盖不全，可能给学生的解决方案带来误导性反馈。这种局限可能会让学生难以充分享受到学习编程时及时反馈带来的好处。

在这项工作中，我们评估了把大型语言模型（LLM）作为更大工作流程的一部分，为 CS1 级别的编程问题自动生成测试套件的效果。我们把每个问题的陈述和参考解决方案提供给 GPT-4，让其生成能被自动评分器使用的测试套件。我们用 26 个问题的样本以及超过 25000 个这些问题的学生提交的尝试解决方案来评估我们提出的方法。我们对比了每个问题中 LLM 生成的测试套件和教师创建的测试套件的性能。研究发现，LLM 生成的测试套件能正确识别大多数有效解决方案，而且多数问题上至少和教师的测试套件一样全面。此外，LLM 生成的测试套件还暴露出一些问题陈述中的模糊之处，凸显了其在改进自动评分和教学设计方面的潜力。

> Automatically graded programming assignments provide instant feedback to students and significantly reduce manual grading time for instructors. However, creating comprehensive suites of test cases for programming problems within automatic graders can be time-consuming and complex. The effort needed to define test suites may deter some instructors from creating additional problems or lead to inadequate test coverage, potentially resulting in misleading feedback on student solutions. Such limitations may reduce student access to the well-documented benefits of timely feedback when learning programming.
  In this work, we evaluate the effectiveness of using Large Language Models (LLMs), as part of a larger workflow, to automatically generate test suites for CS1-level programming problems. Each problem's statement and reference solution are provided to GPT-4 to produce a test suite that can be used by an autograder. We evaluate our proposed approach using a sample of 26 problems, and more than 25,000 attempted solutions to those problems, submitted by students in an introductory programming course. We compare the performance of the LLM-generated test suites against the instructor-created test suites for each problem. Our findings reveal that LLM-generated test suites can correctly identify most valid solutions, and for most problems are at least as comprehensive as the instructor test suites. Additionally, the LLM-generated test suites exposed ambiguities in some problem statements, underscoring their potential to improve both autograding and instructional design.

[Arxiv](https://arxiv.org/abs/2411.09261)