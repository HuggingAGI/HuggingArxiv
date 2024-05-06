# 利用大型语言模型实现控制逻辑测试用例的自动生成

发布时间：2024年05月03日

`LLM应用` `工业自动化` `软件测试`

> Automated Control Logic Test Case Generation using Large Language Models

# 摘要

> 工业自动化领域中对PLC和DCS控制逻辑的测试工作既繁琐又充满挑战，主要原因在于设计出恰当的测试案例本身颇为复杂且难以构造。过去，研究者们已经提出多种自动化生成PLC软件测试案例的方法，这些方法运用了符号执行和基于搜索的技术。它们通常需要依赖正式的规范说明，并进行程序的机械分析，虽然能够发现某些编程错误，但有时会因为状态空间的爆炸性增长而无法处理那些不太正式的规范说明。我们提出了一种创新的方法，通过询问大型语言模型（LLM）来自动生成PLC的测试案例，这些案例针对提示中提供的代码进行合成。在Oscat自动化库的十个开源功能块上的实验显示，这种方法不仅快速、用户友好，而且能够为中等以下复杂度的程序产生高语句覆盖率的测试案例。尽管如此，我们也发现，由LLM生成的测试案例在很多情况下包含了错误的断言，这需要进行人工修正。

> Testing PLC and DCS control logic in industrial automation is laborious and challenging since appropriate test cases are often complex and difficult to formulate. Researchers have previously proposed several automated test case generation approaches for PLC software applying symbolic execution and search-based techniques. Often requiring formal specifications and performing a mechanical analysis of programs, these approaches may uncover specific programming errors but sometimes suffer from state space explosion and cannot process rather informal specifications. We proposed a novel approach for the automatic generation of PLC test cases that queries a Large Language Model (LLM) to synthesize test cases for code provided in a prompt. Experiments with ten open-source function blocks from the OSCAT automation library showed that the approach is fast, easy to use, and can yield test cases with high statement coverage for low-to-medium complex programs. However, we also found that LLM-generated test cases suffer from erroneous assertions in many cases, which still require manual adaption.

[Arxiv](https://arxiv.org/abs/2405.01874)