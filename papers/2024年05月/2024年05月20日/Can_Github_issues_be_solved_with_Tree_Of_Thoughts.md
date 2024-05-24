# 思维树能否解开 Github 问题的谜团？

发布时间：2024年05月20日

`Agent

理由：这篇论文主要探讨了如何通过思维树（ToT）语言模型推理框架来增强大型语言模型（LLM）在复杂任务中的决策与问题解决能力，特别是在解决GitHub问题等实际场景中的应用。论文中提到的ToT框架通过结构化探索多条推理路径及自我评估解决方案，这与Agent的概念相符，即一个能够自主决策和执行任务的实体。虽然论文中提到了检索增强生成（RAG）技术，但这并不是论文的主要研究内容，而是作为对比和背景信息出现。因此，这篇论文更适合归类为Agent。` `软件开发` `人工智能`

> Can Github issues be solved with Tree Of Thoughts?

# 摘要

> 大型语言模型（LLM）在代码生成领域的研究虽已深入，但在如HumanEval等基准测试中取得的96.3%成功率，主要集中在基础函数级代码生成上，未能充分体现解决GitHub问题等实际场景所需的深度思考和作用域理解。本研究采用思维树（ToT）语言模型推理框架，旨在强化LLM在复杂任务中的决策与问题解决能力。相较于传统的输入输出（IO）提示和检索增强生成（RAG）技术，ToT通过结构化探索多条推理路径及自我评估解决方案，力求提升性能。我们在SWE-bench的一个实例中应用ToT解决GitHub问题，但发现ToT框架本身尚不足以让LLM在批判性推理上超越现有技术。本文探讨了这些局限的原因，并提出了深化思考过程和引入代理能力等改进方向，以期优化ToT的应用，并更充分地挖掘LLM在实际问题解决中的潜能。

> While there have been extensive studies in code generation by large language models (LLM), where benchmarks like HumanEval have been surpassed with an impressive 96.3% success rate, these benchmarks predominantly judge a model's performance on basic function-level code generation and lack the critical thinking and concept of scope required of real-world scenarios such as solving GitHub issues. This research introduces the application of the Tree of Thoughts (ToT) language model reasoning framework for enhancing the decision-making and problem-solving abilities of LLMs for this complex task. Compared to traditional input-output (IO) prompting and Retrieval Augmented Generation (RAG) techniques, ToT is designed to improve performance by facilitating a structured exploration of multiple reasoning trajectories and enabling self-assessment of potential solutions. We experimentally deploy ToT in tackling a Github issue contained within an instance of the SWE-bench. However, our results reveal that the ToT framework alone is not enough to give LLMs the critical reasoning capabilities to outperform existing methods. In this paper we analyze the potential causes of these shortcomings and identify key areas for improvement such as deepening the thought process and introducing agentic capabilities. The insights of this research are aimed at informing future directions for refining the application of ToT and better harnessing the potential of LLMs in real-world problem-solving scenarios.

[Arxiv](https://arxiv.org/abs/2405.13057)