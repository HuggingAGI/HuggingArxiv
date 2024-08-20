# 基于大型语言模型的自动化单元测试生成系统及其生成测试套件的评估
发布时间：2024年08月14日

`代码编写`
> A System for Automated Unit Test Generation Using Large Language Models and Assessment of Generated Test Suites
>
> 单元测试是软件测试的基础，对保障软件质量至关重要。然而，设计与编写单元测试既耗时又费力，亟需自动化解决方案。近年来，大型语言模型（LLM）在软件开发的多个领域展现出潜力，包括单元测试的自动生成。尽管已有研究评估了LLM在生成测试代码方面的能力，但这些研究多聚焦于简单案例，如为单一方法编写测试，且往往局限于小规模、孤立的测试单元，未能全面反映LLM在实际软件开发环境中的表现。此外，以往研究在处理实际应用规模上存在不足，生成的测试通常需手动集成至项目中进行评估，这不仅限制了测试数量，也降低了效率。为填补这些空白，我们提出了一种新方法，专注于生成复杂度更高的类级别测试代码，并实现了从生成到评估的全流程自动化。我们开发了\textsc{AgoneTest}系统，该系统能够为Java项目自动生成测试套件，并采用一套严谨的方法论来全面评估这些测试套件的质量。基于前沿数据集\textsc{Methods2Test}，我们构建了新数据集，用于对比人工编写与LLM生成的测试。我们的主要贡献包括：一个可扩展的自动化软件系统、一个新数据集，以及一套详尽的测试质量评估方法论。
>
> https://arxiv.org/abs/2408.07846

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.07846](https://arxiv.org/abs/2408.07846)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)