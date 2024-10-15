# LLM 生成单元测试中的测试异味

发布时间：2024年10月14日

`LLM应用` `软件测试` `人工智能`

> Test smells in LLM-Generated Unit Tests

# 摘要

> LLM 在自动化测试生成中的应用日益广泛，但除了编译率、代码覆盖率等指标外，测试代码中的设计缺陷同样关键。本研究对比了 LLM 与人类编写的测试套件，发现 LLM 生成的测试中常见异味如魔法数字和断言轮盘赌。此外，某些异味如长测试和无用测试在 LLM 生成的套件中更易共现，且受提示技术影响。项目复杂性和模型特性也显著影响异味普遍性。LLM 生成的测试异味模式与人类编写测试相似，暗示数据泄露可能。这些发现强调了优化 LLM 测试生成和提升软件测试实践的必要性。

> The use of Large Language Models (LLMs) in automated test generation is gaining popularity, with much of the research focusing on metrics like compilability rate, code coverage and bug detection. However, an equally important quality metric is the presence of test smells design flaws or anti patterns in test code that hinder maintainability and readability. In this study, we explore the diffusion of test smells in LLM generated unit test suites and compare them to those found in human written ones. We analyze a benchmark of 20,500 LLM-generated test suites produced by four models (GPT-3.5, GPT-4, Mistral 7B, and Mixtral 8x7B) across five prompt engineering techniques, alongside a dataset of 780,144 human written test suites from 34,637 projects. Leveraging TsDetect, a state of the art tool capable of detecting 21 different types of test smells, we identify and analyze the prevalence and co-occurrence of various test smells in both human written and LLM-generated test suites. Our findings reveal new insights into the strengths and limitations of LLMs in test generation. First, regarding prevalence, we observe that LLMs frequently generate tests with common test smells, such as Magic Number Test and Assertion Roulette. Second, in terms of co occurrence, certain smells, like Long Test and Useless Test, tend to co occur in LLM-generated suites, influenced by specific prompt techniques. Third, we find that project complexity and LLM specific factors, including model size and context length, significantly affect the prevalence of test smells. Finally, the patterns of test smells in LLM-generated tests often mirror those in human-written tests, suggesting potential data leakage from training datasets. These insights underscore the need to refine LLM-based test generation for cleaner code and suggest improvements in both LLM capabilities and software testing practices.

[Arxiv](https://arxiv.org/abs/2410.10628)