# NSP：神经符号自然语言导航规划器

发布时间：2024年09月10日

`LLM应用` `机器人` `自动化`

> NSP: A Neuro-Symbolic Natural Language Navigational Planner

# 摘要

> 自由形式自然语言指令的路径规划器有望推动机器人应用的自动化。这些规划器不仅简化了用户交互，还实现了对复杂半自主系统的直观控制。尽管现有符号方法在正确性和效率上有所保证，但在解析自然语言输入时却力不从心。而基于预训练大型语言模型 (LLM) 的神经方法虽能处理自然语言，却缺乏性能保障。为此，我们提出了名为 NSP 的神经符号框架，用于自然语言输入的路径规划。该框架利用 LLM 的神经推理能力，构建环境的符号表示并设计符号路径规划算法。通过在环境表示上执行算法，我们得以解决路径规划问题。此外，框架通过符号执行环境与神经生成过程间的反馈循环，自我纠正语法错误并满足执行时间约束。实验表明，我们的神经符号方法生成的有效路径比最先进的神经方法平均缩短 19-77%，且有效路径率高达 90.1%。

> Path planners that can interpret free-form natural language instructions hold promise to automate a wide range of robotics applications. These planners simplify user interactions and enable intuitive control over complex semi-autonomous systems. While existing symbolic approaches offer guarantees on the correctness and efficiency, they struggle to parse free-form natural language inputs. Conversely, neural approaches based on pre-trained Large Language Models (LLMs) can manage natural language inputs but lack performance guarantees. In this paper, we propose a neuro-symbolic framework for path planning from natural language inputs called NSP. The framework leverages the neural reasoning abilities of LLMs to i) craft symbolic representations of the environment and ii) a symbolic path planning algorithm. Next, a solution to the path planning problem is obtained by executing the algorithm on the environment representation. The framework uses a feedback loop from the symbolic execution environment to the neural generation process to self-correct syntax errors and satisfy execution time constraints. We evaluate our neuro-symbolic approach using a benchmark suite with 1500 path-planning problems. The experimental evaluation shows that our neuro-symbolic approach produces 90.1% valid paths that are on average 19-77% shorter than state-of-the-art neural approaches.

[Arxiv](https://arxiv.org/abs/2409.06859)