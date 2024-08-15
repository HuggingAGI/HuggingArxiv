# 大型语言模型在源代码质量评估中的应用：一项对比研究

发布时间：2024年08月07日

`LLM应用` `软件开发` `质量控制`

> Evaluating Source Code Quality with Large Languagem Models: a comparative study

# 摘要

> 代码质量涵盖了复杂性、可读性、可测试性等多项指标。静态代码分析工具虽能评估这些属性，但某些如可读性等特质仍需人工审查。我们推测，凭借其强大的自然语言处理能力，大型语言模型（LLM）或许能评估包括当前难以自动化的代码质量属性。本文通过对比LLM与SonarQube软件在两个Java开源项目的分析结果，展示了LLM在代码质量评估方面的潜力。研究发现，GPT 3.5 Turbo模型能有效评估代码质量，并与SonarQube的指标存在相关性，但GPT 4o模型在某些评估上与前者及SonarQube存在差异。尽管LLM在代码质量评估上展现出潜力，但仍需进一步研究以解决其成本、输出一致性等问题，并探索传统工具未涉及的质量特征。

> Code quality is an attribute composed of various metrics, such as complexity, readability, testability, interoperability, reusability, and the use of good or bad practices, among others. Static code analysis tools aim to measure a set of attributes to assess code quality. However, some quality attributes can only be measured by humans in code review activities, readability being an example. Given their natural language text processing capability, we hypothesize that a Large Language Model (LLM) could evaluate the quality of code, including attributes currently not automatable. This paper aims to describe and analyze the results obtained using LLMs as a static analysis tool, evaluating the overall quality of code. We compared the LLM with the results obtained with the SonarQube software and its Maintainability metric for two Open Source Software (OSS) Java projects, one with Maintainability Rating A and the other B. A total of 1,641 classes were analyzed, comparing the results in two versions of models: GPT 3.5 Turbo and GPT 4o. We demonstrated that the GPT 3.5 Turbo LLM has the ability to evaluate code quality, showing a correlation with Sonar's metrics. However, there are specific aspects that differ in what the LLM measures compared to SonarQube. The GPT 4o version did not present the same results, diverging from the previous model and Sonar by assigning a high classification to codes that were assessed as lower quality. This study demonstrates the potential of LLMs in evaluating code quality. However, further research is necessary to investigate limitations such as LLM's cost, variability of outputs and explore quality characteristics not measured by traditional static analysis tools.

[Arxiv](https://arxiv.org/abs/2408.07082)