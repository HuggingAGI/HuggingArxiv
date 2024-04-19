# 利用形式化验证工具，大型语言模型（LLMs）能够为您的旅行提供严谨的规划。

发布时间：2024年04月18日

`LLM应用` `旅游规划` `组合优化`

> Large Language Models Can Plan Your Travels Rigorously with Formal Verification Tools

# 摘要

> 最新的大型语言模型（LLMs）以其广博的世界知识、工具使用和推理能力，催生了众多LLM规划算法。但是，LLMs在解决复杂的组合优化问题方面尚未表现出精准能力。Xie等人在2024年的研究中提出了一个美国国内旅行规划的基准测试——TravelPlanner，发现LLMs在制定满足用户需求的旅行计划上，最佳成功率仅为0.6%。本研究提出了一个框架，使LLMs能够将旅行规划问题转化为可满足性模态理论（SMT）问题，并与SMT求解器互动，自动解决组合搜索问题。SMT求解器确保输入约束的满足性，而LLMs则提供基于语言的交互。当输入约束无法满足时，我们的LLM框架将自动使用SMT求解器进行推理，与用户互动，提出修改旅行需求的建议。我们利用TravelPlanner对框架进行了评估，取得了97%的成功率。此外，我们还创建了一个包含国际旅行基准的独立数据集，并通过这两个数据集评估了在初始用户查询无法满足时，我们的交互式规划框架的有效性。根据不同人的偏好，我们的数据集的平均成功率为78.6%，而TravelPlanner的成功率为85.0%。

> The recent advancements of Large Language Models (LLMs), with their abundant world knowledge and capabilities of tool-using and reasoning, fostered many LLM planning algorithms. However, LLMs have not shown to be able to accurately solve complex combinatorial optimization problems. In Xie et al. (2024), the authors proposed TravelPlanner, a U.S. domestic travel planning benchmark, and showed that LLMs themselves cannot make travel plans that satisfy user requirements with a best success rate of 0.6%. In this work, we propose a framework that enables LLMs to formally formulate and solve the travel planning problem as a satisfiability modulo theory (SMT) problem and use SMT solvers interactively and automatically solve the combinatorial search problem. The SMT solvers guarantee the satisfiable of input constraints and the LLMs can enable a language-based interaction with our framework. When the input constraints cannot be satisfiable, our LLM-based framework will interactively offer suggestions to users to modify their travel requirements via automatic reasoning using the SMT solvers. We evaluate our framework with TravelPlanner and achieve a success rate of 97%. We also create a separate dataset that contain international travel benchmarks and use both dataset to evaluate the effectiveness of our interactive planning framework when the initial user queries cannot be satisfied. Our framework could generate valid plans with an average success rate of 78.6% for our dataset and 85.0% for TravelPlanner according to diverse humans preferences.

[Arxiv](https://arxiv.org/abs/2404.11891)