# 像人类一样探索数字世界：GUI 代理的通用视觉基础

发布时间：2024年10月07日

`Agent` `软件开发` `人机交互`

> Navigating the Digital World as Humans Do: Universal Visual Grounding for GUI Agents

# 摘要

> 多模态大型语言模型 (MLLMs) 正在革新图形用户界面 (GUI) 代理，使其从受控模拟迈向复杂的现实应用。然而，这些代理的效能依赖于其基础能力的稳健性。当前的 GUI 代理主要依赖基于文本的表示，如 HTML 或可访问性树，这些表示虽有用，但常带来噪声、不完整性和计算负担。本文提出，GUI 代理应具备类似人类的视觉感知能力，直接进行像素级操作。关键在于视觉基础模型，能将 GUI 元素的多样表达准确映射到不同平台上的坐标。我们发现，结合网络合成数据和 LLaVA 架构的轻微调整，能有效训练此类模型。我们收集了迄今最大的 GUI 视觉基础数据集，包含 10M 元素和 1.3M 截图，用于训练 UGround，一个强大的通用视觉基础模型。实验结果显示，UGround 在六个基准测试中显著优于现有模型，且仅依赖视觉感知的代理性能超越了使用额外文本输入的最先进代理。这些发现为 GUI 代理在数字世界中像人类一样导航的可行性和前景提供了有力支持。

> Multimodal large language models (MLLMs) are transforming the capabilities of graphical user interface (GUI) agents, facilitating their transition from controlled simulations to complex, real-world applications across various platforms. However, the effectiveness of these agents hinges on the robustness of their grounding capability. Current GUI agents predominantly utilize text-based representations such as HTML or accessibility trees, which, despite their utility, often introduce noise, incompleteness, and increased computational overhead. In this paper, we advocate a human-like embodiment for GUI agents that perceive the environment entirely visually and directly take pixel-level operations on the GUI. The key is visual grounding models that can accurately map diverse referring expressions of GUI elements to their coordinates on the GUI across different platforms. We show that a simple recipe, which includes web-based synthetic data and slight adaptation of the LLaVA architecture, is surprisingly effective for training such visual grounding models. We collect the largest dataset for GUI visual grounding so far, containing 10M GUI elements and their referring expressions over 1.3M screenshots, and use it to train UGround, a strong universal visual grounding model for GUI agents. Empirical results on six benchmarks spanning three categories (grounding, offline agent, and online agent) show that 1) UGround substantially outperforms existing visual grounding models for GUI agents, by up to 20% absolute, and 2) agents with UGround outperform state-of-the-art agents, despite the fact that existing agents use additional text-based input while ours only uses visual perception. These results provide strong support for the feasibility and promises of GUI agents that navigate the digital world as humans do.

[Arxiv](https://arxiv.org/abs/2410.05243)