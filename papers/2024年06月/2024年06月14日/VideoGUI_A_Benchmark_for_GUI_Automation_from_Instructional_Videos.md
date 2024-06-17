# VideoGUI：教学视频中的GUI自动化性能评估基准

发布时间：2024年06月14日

`Agent

这篇论文介绍了一个名为VideoGUI的多模态基准，用于评估GUI助手在处理视觉密集型任务中的表现。它特别关注于使用专业软件进行复杂任务，如视频编辑，并通过分层评估机制来分析助手在不同层次上的表现，从高级规划到原子动作执行。这种对GUI助手的评估和改进，以及其在复杂任务中的应用，符合Agent类别的定义，即设计和评估能够执行复杂任务的智能代理。` `视频编辑` `软件自动化`

> VideoGUI: A Benchmark for GUI Automation from Instructional Videos

# 摘要

> 图形用户界面（GUI）自动化通过辅助计算机任务，极大地提升了人类的工作效率。然而，现有的任务定义多局限于简单的指令性任务，如“插入新幻灯片”。本研究推出的VideoGUI，是一个创新的多模态基准，专门用于评估GUI助手在视觉密集型任务中的表现。该基准聚焦于使用专业软件（如Adobe Photoshop或Stable Diffusion WebUI）进行的复杂任务，如视频编辑，数据来源于高质量的网络教学视频。VideoGUI通过分层评估机制，揭示了GUI助手在不同层次上的潜在失败点：从高级规划（无需语言描述，从视觉条件重建程序子任务）到中级规划（基于视觉状态和目标生成动作序列），再到原子动作执行（如精确点击指定元素）。我们为每个层次设计了详细的评估指标，以清晰地反映性能，例如在原子动作执行中的点击、拖动、打字和滚动等。评估结果显示，即使是顶尖的多模态模型GPT4o，在视觉密集型GUI任务，尤其是在高级规划方面，表现亦不尽人意。

> Graphical User Interface (GUI) automation holds significant promise for enhancing human productivity by assisting with computer tasks. Existing task formulations primarily focus on simple tasks that can be specified by a single, language-only instruction, such as "Insert a new slide." In this work, we introduce VideoGUI, a novel multi-modal benchmark designed to evaluate GUI assistants on visual-centric GUI tasks. Sourced from high-quality web instructional videos, our benchmark focuses on tasks involving professional and novel software (e.g., Adobe Photoshop or Stable Diffusion WebUI) and complex activities (e.g., video editing). VideoGUI evaluates GUI assistants through a hierarchical process, allowing for identification of the specific levels at which they may fail: (i) high-level planning: reconstruct procedural subtasks from visual conditions without language descriptions; (ii) middle-level planning: generate sequences of precise action narrations based on visual state (i.e., screenshot) and goals; (iii) atomic action execution: perform specific actions such as accurately clicking designated elements. For each level, we design evaluation metrics across individual dimensions to provide clear signals, such as individual performance in clicking, dragging, typing, and scrolling for atomic action execution. Our evaluation on VideoGUI reveals that even the SoTA large multimodal model GPT4o performs poorly on visual-centric GUI tasks, especially for high-level planning.

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x1.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x2.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x3.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x4.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x5.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x7.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x8.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x9.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x10.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x11.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x12.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/label_gui.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x13.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x14.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x15.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x16.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x17.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x18.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/videogui.jpg)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/x19.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt17_final.jpg)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt17_v.jpg)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt17_full.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt17_full_mid.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt18_final.jpg)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt18_v.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt18_full.png)

![VideoGUI：教学视频中的GUI自动化性能评估基准](../../../paper_images/2406.10227/ppt18_full_mid.png)

[Arxiv](https://arxiv.org/abs/2406.10227)