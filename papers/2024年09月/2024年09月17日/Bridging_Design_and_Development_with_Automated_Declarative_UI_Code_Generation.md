# 自动化声明式 UI 代码生成，架起设计与开发之间的桥梁

发布时间：2024年09月17日

`LLM应用` `移动应用开发` `软件工程`

> Bridging Design and Development with Automated Declarative UI Code Generation

# 摘要

> 声明性 UI 框架在移动应用开发中广受欢迎，因其能提升代码可读性和简化维护。然而，将 UI 设计转化为功能代码的过程依然复杂且耗时。近期，多模态大型语言模型 (MLLM) 展示了从 UI 设计直接生成应用代码的潜力，但其在准确识别 UI 组件和全面捕捉交互逻辑方面仍面临挑战。为此，我们推出了 DeclarUI，一种结合计算机视觉、MLLM 和迭代编译优化的自动化方法，旨在从设计中生成并优化声明性 UI 代码。通过精确的组件分割、页面过渡图 (PTG) 和迭代优化，DeclarUI 提升了视觉保真度、功能完整性和代码质量。在 React Native 框架的测试中，DeclarUI 表现优异，PTG 覆盖率达 96.8%，编译成功率达 98%。与最先进的 MLLM 相比，DeclarUI 的 PTG 覆盖率提升了 123%，视觉相似度得分提高了 55%，编译成功率提升了 29%。此外，DeclarUI 还成功应用于 Flutter 和 ArkUI 框架，展示了其广泛的适用性。

> Declarative UI frameworks have gained widespread adoption in mobile app development, offering benefits such as improved code readability and easier maintenance. Despite these advantages, the process of translating UI designs into functional code remains challenging and time-consuming. Recent advancements in multimodal large language models (MLLMs) have shown promise in directly generating mobile app code from user interface (UI) designs. However, the direct application of MLLMs to this task is limited by challenges in accurately recognizing UI components and comprehensively capturing interaction logic.
  To address these challenges, we propose DeclarUI, an automated approach that synergizes computer vision (CV), MLLMs, and iterative compiler-driven optimization to generate and refine declarative UI code from designs. DeclarUI enhances visual fidelity, functional completeness, and code quality through precise component segmentation, Page Transition Graphs (PTGs) for modeling complex inter-page relationships, and iterative optimization. In our evaluation, DeclarUI outperforms baselines on React Native, a widely adopted declarative UI framework, achieving a 96.8% PTG coverage rate and a 98% compilation success rate. Notably, DeclarUI demonstrates significant improvements over state-of-the-art MLLMs, with a 123% increase in PTG coverage rate, up to 55% enhancement in visual similarity scores, and a 29% boost in compilation success rate. We further demonstrate DeclarUI's generalizability through successful applications to Flutter and ArkUI frameworks.

[Arxiv](https://arxiv.org/abs/2409.11667)