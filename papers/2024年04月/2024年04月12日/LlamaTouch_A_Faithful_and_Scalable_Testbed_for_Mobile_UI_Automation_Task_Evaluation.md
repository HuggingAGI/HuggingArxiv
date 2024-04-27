# LlamaTouch：一个忠实且可扩展的移动用户界面自动化任务评估测试平台。

发布时间：2024年04月12日

`Agent` `移动UI自动化` `软件测试`

> LlamaTouch: A Faithful and Scalable Testbed for Mobile UI Automation Task Evaluation

# 摘要

> 随着大型语言/多模态模型的兴起，移动代理在移动 UI 自动化任务中的发展迎来了新机遇。但现行的评估手段，无论是依赖人工确认还是基于现有数据集比较代理行为与预设标准，都存在扩展性差和准确性不足的问题。本文介绍的 LlamaTouch，是一个创新的测试平台，旨在实现设备上的代理执行和更为可靠、可扩展的代理评估。LlamaTouch 通过观察到任务执行仅涉及 UI 状态的转换，采用了一种创新的评估策略，只关注代理是否成功遍历了所有关键的应用/系统状态。该平台整合了三项核心技术：设备上的实时任务执行、细致的 UI 组件标注以及多级状态匹配算法，后者结合了精确匹配和模糊匹配技术，以适应不断变化的 UI 布局和内容。目前，LlamaTouch 已经集成了四款移动代理，覆盖了495个 UI 自动化任务，不仅包括广泛使用的数据集中的任务，还有我们为多样化移动应用场景特别构建的任务。评估结果显示，LlamaTouch 在真实环境中的评估准确性高，且在扩展性方面优于人工验证。此外，LlamaTouch 还简化了任务标注流程，并支持新移动代理的轻松集成。相关代码和数据集已在 https://github.com/LlamaTouch/LlamaTouch 上公开发布。

> The emergent large language/multimodal models facilitate the evolution of mobile agents, especially in the task of mobile UI automation. However, existing evaluation approaches, which rely on human validation or established datasets to compare agent-predicted actions with predefined ones, are unscalable and unfaithful. To overcome these limitations, this paper presents LlamaTouch, a testbed for on-device agent execution and faithful, scalable agent evaluation. By observing that the task execution process only transfers UI states, LlamaTouch employs a novel evaluation approach that only assesses whether an agent traverses all manually annotated, essential application/system states. LlamaTouch comprises three key techniques: (1) On-device task execution that enables mobile agents to interact with real mobile environments for task completion. (2) Fine-grained UI component annotation that merges pixel-level screenshots and textual screen hierarchies to explicitly identify and precisely annotate essential UI components with a rich set of designed annotation primitives. (3) A multi-level state matching algorithm that utilizes exact and fuzzy matching to accurately detect critical information in each screen with unpredictable UI layout/content dynamics. LlamaTouch currently incorporates four mobile agents and 495 UI automation tasks, encompassing both tasks in the widely-used datasets and our self-constructed ones for more diverse mobile applications. Evaluation results demonstrate the LlamaTouch's high faithfulness of evaluation in real environments and its better scalability than human validation. LlamaTouch also enables easy task annotation and integration of new mobile agents. Code and dataset are publicly available at https://github.com/LlamaTouch/LlamaTouch.

[Arxiv](https://arxiv.org/abs/2404.16054)