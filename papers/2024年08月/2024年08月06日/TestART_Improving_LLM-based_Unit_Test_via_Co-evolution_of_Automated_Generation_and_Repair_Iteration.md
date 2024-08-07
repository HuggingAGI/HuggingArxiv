# TestART：借助自动化生成与修复的迭代共进化，提升基于 LLM 的单元测试质量。

发布时间：2024年08月06日

`LLM应用` `软件开发` `自动化测试`

> TestART: Improving LLM-based Unit Test via Co-evolution of Automated Generation and Repair Iteration

# 摘要

> 单元测试虽关键，但耗时费力。现有自动化方法多基于SBST和语言模型。近期，LLM展现了卓越的推理与生成能力，但面临生成高质量测试用例的挑战：无效测试、缺乏反馈、重复问题。为此，我们提出TestART，一种结合LLM优势并克服其局限的新方法。TestART通过自动化生成与修复迭代，利用模板修复技术及提示注入，提升测试用例质量。此外，从通过测试中提取覆盖信息，增强测试充分性。实验显示，TestART生成的测试用例通过率高达78.55%，行覆盖率达90.96%，显著优于其他方法。

> Unit test is crucial for detecting bugs in individual program units but consumes time and effort. The existing automated unit test generation methods are mainly based on search-based software testing (SBST) and language models to liberate developers. Recently, large language models (LLMs) have demonstrated remarkable reasoning and generation capabilities. However, several problems limit their ability to generate high-quality test cases: (1) LLMs may generate invalid test cases under insufficient context, resulting in compilation errors; (2) Lack of test and coverage feedback information may cause runtime errors and low coverage rates. (3) The repetitive suppression problem causes LLMs to get stuck into the repetition loop of self-repair or re-generation attempts. In this paper, we propose TestART, a novel unit test generation method that leverages the strengths of LLMs while overcoming the limitations mentioned. TestART improves LLM-based unit test via co-evolution of automated generation and repair iteration. TestART leverages the template-based repair technique to fix bugs in LLM-generated test cases, using prompt injection to guide the next-step automated generation and avoid repetition suppression. Furthermore, TestART extracts coverage information from the passed test cases and utilizes it as testing feedback to enhance the sufficiency of the final test case. This synergy between generation and repair elevates the quality, effectiveness, and readability of the produced test cases significantly beyond previous methods. In comparative experiments, the pass rate of TestART-generated test cases is 78.55%, which is approximately 18% higher than both the ChatGPT-4.0 model and the same ChatGPT-3.5-based method ChatUniTest. It also achieves an impressive line coverage rate of 90.96% on the focal methods that passed the test, exceeding EvoSuite by 3.4%.

[Arxiv](https://arxiv.org/abs/2408.03095)