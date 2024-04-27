# LlamaTouch：一个忠实且可扩展的移动用户界面自动化任务评估测试平台。

发布时间：2024年04月12日

`Agent` `移动应用测试` `自动化测试`

> LlamaTouch: A Faithful and Scalable Testbed for Mobile UI Automation Task Evaluation

# 摘要

> 随着大型语言/多模态模型的出现，移动代理的进化，尤其是在移动用户界面(UI)自动化任务中，得到了显著推动。然而，目前依赖人工验证或现有数据集的评估方法存在扩展性差和准确性不足的问题。为了解决这一难题，本文介绍了 LlamaTouch，这是一个在设备上执行代理操作并进行准确、可扩展评估的测试平台。LlamaTouch 创新地仅关注任务执行过程中的 UI 状态转移，通过评估代理是否成功遍历了所有关键的、手动标注的应用/系统状态。该平台采用了三项核心技术：(1) 设备上的实时任务执行，让移动代理能够与真实移动环境互动完成任务；(2) 精细的 UI 组件标注，结合像素级截图和文本化屏幕层级，精确识别并标注关键 UI 组件；(3) 多级状态匹配算法，结合精确匹配和模糊匹配技术，准确捕捉每个屏幕中的关键信息，即使在 UI 布局和内容动态变化的情况下。LlamaTouch 已集成四种移动代理和 495 项 UI 自动化任务，不仅涵盖了广泛使用的公共数据集，还包括我们为多样化移动应用自建的任务。评估结果显示，LlamaTouch 在真实环境中的评估准确性高，且相较于人工验证，具有更好的可扩展性。此外，LlamaTouch 还简化了任务标注流程，并支持新移动代理的轻松集成。相关代码和数据集已在 https://github.com/LlamaTouch/LlamaTouch 上公开发布。

> The emergent large language/multimodal models facilitate the evolution of mobile agents, especially in the task of mobile UI automation. However, existing evaluation approaches, which rely on human validation or established datasets to compare agent-predicted actions with predefined ones, are unscalable and unfaithful. To overcome these limitations, this paper presents LlamaTouch, a testbed for on-device agent execution and faithful, scalable agent evaluation. By observing that the task execution process only transfers UI states, LlamaTouch employs a novel evaluation approach that only assesses whether an agent traverses all manually annotated, essential application/system states. LlamaTouch comprises three key techniques: (1) On-device task execution that enables mobile agents to interact with real mobile environments for task completion. (2) Fine-grained UI component annotation that merges pixel-level screenshots and textual screen hierarchies to explicitly identify and precisely annotate essential UI components with a rich set of designed annotation primitives. (3) A multi-level state matching algorithm that utilizes exact and fuzzy matching to accurately detect critical information in each screen with unpredictable UI layout/content dynamics. LlamaTouch currently incorporates four mobile agents and 495 UI automation tasks, encompassing both tasks in the widely-used datasets and our self-constructed ones for more diverse mobile applications. Evaluation results demonstrate the LlamaTouch's high faithfulness of evaluation in real environments and its better scalability than human validation. LlamaTouch also enables easy task annotation and integration of new mobile agents. Code and dataset are publicly available at https://github.com/LlamaTouch/LlamaTouch.

[Arxiv](https://arxiv.org/abs/2404.16054)