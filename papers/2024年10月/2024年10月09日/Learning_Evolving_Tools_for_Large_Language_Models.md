# 探索大型语言模型的进化学习工具

发布时间：2024年10月09日

`LLM应用` `人工智能` `软件开发`

> Learning Evolving Tools for Large Language Models

# 摘要

> 工具学习让大型语言模型（LLM）能与外部工具和API互动，大大拓宽了应用领域。但外部环境的动态变化可能导致这些工具和API过时，影响LLM的正确调用。现有研究多聚焦于静态环境，忽视了这一问题，限制了LLM在实际应用中的适应性。为此，我们提出了ToolEVO框架，旨在提升LLM对工具变异性的适应与反射能力。通过蒙特卡洛树搜索，ToolEVO助力LLM在动态环境中主动探索与交互，实现基于环境反馈的工具使用自我反思与更新。同时，我们推出了ToolQA-D基准，专门评估工具变异性的影响。实验结果显示，我们的方法既有效又稳定，凸显了适应工具变异性对工具学习的重要性。

> Tool learning enables large language models (LLMs) to interact with external tools and APIs, greatly expanding the application scope of LLMs. However, due to the dynamic nature of external environments, these tools and APIs may become outdated over time, preventing LLMs from correctly invoking tools. Existing research primarily focuses on static environments and overlooks this issue, limiting the adaptability of LLMs in real-world applications. In this paper, we propose ToolEVO, a novel framework designed to enhance the adaptive and reflective capabilities of LLMs against tool variability. By leveraging Monte Carlo Tree Search, ToolEVO facilitates active exploration and interaction of LLMs within dynamic environments, allowing for autonomous self-reflection and self-updating of tool usage based on environmental feedback. Additionally, we introduce ToolQA-D, a benchmark specifically designed to evaluate the impact of tool variability. Extensive experiments demonstrate the effectiveness and stability of our approach, highlighting the importance of adaptability to tool variability for effective tool learning.

[Arxiv](https://arxiv.org/abs/2410.06617)