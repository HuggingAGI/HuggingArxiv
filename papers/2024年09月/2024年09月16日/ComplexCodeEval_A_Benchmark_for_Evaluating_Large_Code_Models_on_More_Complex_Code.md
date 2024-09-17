# ComplexCodeEval：评估大型代码模型处理复杂代码能力的基准

发布时间：2024年09月16日

`LLM应用` `软件开发` `代码生成`

> ComplexCodeEval: A Benchmark for Evaluating Large Code Models on More Complex Code

# 摘要

> 近年来，LLM 在代码任务中的应用备受瞩目，但现有评估基准多局限于代码生成等单一场景，未能全面反映开发者的实际挑战。为此，我们推出了 ComplexCodeEval，一个涵盖代码生成、API 推荐等多项任务的评估基准。该基准包含 3,897 个 Java 和 7,184 个 Python 样本，均来自高星 GitHub 仓库，并附有函数签名、文档字符串等详细信息，力求模拟真实开发环境。我们的实验显示，上下文信息能显著提升模型性能，但数据泄露问题可能导致评估偏差，这凸显了更精准评估的重要性。

> In recent years, the application of large language models (LLMs) to code-related tasks has gained significant attention. However, existing evaluation benchmarks often focus on limited scenarios, such as code generation or completion, which do not reflect the diverse challenges developers face in real-world contexts. To address this, we introduce ComplexCodeEval, a benchmark designed to assess LCMs in various development tasks, including code generation, completion, API recommendation, and test case generation. It includes 3,897 Java samples and 7,184 Python samples from high-star GitHub repositories, each annotated with function signatures, docstrings, and API references to simulate real development environments. Our experiments across ten LCMs reveal that context improves performance and that data leakage can lead to overestimation, highlighting the need for more accurate evaluations.

[Arxiv](https://arxiv.org/abs/2409.10280)