# AutoPenBench：为渗透测试中的生成代理提供基准测试

发布时间：2024年10月04日

`Agent` `网络安全` `自动化测试`

> AutoPenBench: Benchmarking Generative Agents for Penetration Testing

# 摘要

> 生成式AI代理，基于大型语言模型（LLM），正成为自动化网络安全任务的新星。渗透测试因其任务复杂性和攻击策略多样性而颇具挑战。尽管自动化渗透测试的研究兴趣渐浓，但评估和开发的标准框架仍显不足。本文推出AutoPenBench，一个开源基准，用于评估自动化渗透测试中的生成代理。该框架包含33个任务，模拟不同难度的脆弱系统。通过通用和特定里程碑，我们标准化评估并揭示代理的局限。测试显示，完全自主代理的成功率仅为21%，而半自主代理则提升至64%。AutoPenBench还揭示了不同LLM对代理任务完成能力的影响。我们期待通过https://github.com/lucagioacchini/auto-pen-bench，与社区共同扩展这一基准，填补标准框架的空白。

> Generative AI agents, software systems powered by Large Language Models (LLMs), are emerging as a promising approach to automate cybersecurity tasks. Among the others, penetration testing is a challenging field due to the task complexity and the diverse strategies to simulate cyber-attacks. Despite growing interest and initial studies in automating penetration testing with generative agents, there remains a significant gap in the form of a comprehensive and standard framework for their evaluation and development. This paper introduces AutoPenBench, an open benchmark for evaluating generative agents in automated penetration testing. We present a comprehensive framework that includes 33 tasks, each representing a vulnerable system that the agent has to attack. Tasks are of increasing difficulty levels, including in-vitro and real-world scenarios. We assess the agent performance with generic and specific milestones that allow us to compare results in a standardised manner and understand the limits of the agent under test. We show the benefits of AutoPenBench by testing two agent architectures: a fully autonomous and a semi-autonomous supporting human interaction. We compare their performance and limitations. For example, the fully autonomous agent performs unsatisfactorily achieving a 21% Success Rate (SR) across the benchmark, solving 27% of the simple tasks and only one real-world task. In contrast, the assisted agent demonstrates substantial improvements, with 64% of SR. AutoPenBench allows us also to observe how different LLMs like GPT-4o or OpenAI o1 impact the ability of the agents to complete the tasks. We believe that our benchmark fills the gap with a standard and flexible framework to compare penetration testing agents on a common ground. We hope to extend AutoPenBench along with the research community by making it available under https://github.com/lucagioacchini/auto-pen-bench.

[Arxiv](https://arxiv.org/abs/2410.03225)