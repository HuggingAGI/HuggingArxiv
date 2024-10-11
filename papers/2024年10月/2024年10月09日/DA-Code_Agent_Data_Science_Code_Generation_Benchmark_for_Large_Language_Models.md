# DA-Code：专为大型语言模型设计的代理数据科学代码生成基准

发布时间：2024年10月09日

`LLM应用` `数据科学` `人工智能`

> DA-Code: Agent Data Science Code Generation Benchmark for Large Language Models

# 摘要

> 我们推出了 DA-Code，一个专为评估 LLM 在基于代理的数据科学任务中的代码生成能力而设计的基准。DA-Code 包含三大核心元素：首先，其任务极具挑战性，远超传统代码生成任务，要求高级编码技能；其次，所有示例均基于真实多样化的数据，覆盖复杂的数据整理与分析任务；第三，模型需运用复杂的数据科学编程语言，进行精细数据处理并得出答案。我们在一个与现实数据分析场景相符且可扩展的可控环境中设置了基准，并精心设计了评估套件，确保评估的准确性与鲁棒性。实验显示，尽管 DA-Agent 基线优于其他框架，但当前最佳 LLM 的准确率仅为 30.5%，提升空间巨大。基准已发布于 [https://da-code-bench.github.io](https://da-code-bench.github.io)。

> We introduce DA-Code, a code generation benchmark specifically designed to assess LLMs on agent-based data science tasks. This benchmark features three core elements: First, the tasks within DA-Code are inherently challenging, setting them apart from traditional code generation tasks and demanding advanced coding skills in grounding and planning. Second, examples in DA-Code are all based on real and diverse data, covering a wide range of complex data wrangling and analytics tasks. Third, to solve the tasks, the models must utilize complex data science programming languages, to perform intricate data processing and derive the answers. We set up the benchmark in a controllable and executable environment that aligns with real-world data analysis scenarios and is scalable. The annotators meticulously design the evaluation suite to ensure the accuracy and robustness of the evaluation. We develop the DA-Agent baseline. Experiments show that although the baseline performs better than other existing frameworks, using the current best LLMs achieves only 30.5% accuracy, leaving ample room for improvement. We release our benchmark at [https://da-code-bench.github.io](https://da-code-bench.github.io).

[Arxiv](https://arxiv.org/abs/2410.07331)