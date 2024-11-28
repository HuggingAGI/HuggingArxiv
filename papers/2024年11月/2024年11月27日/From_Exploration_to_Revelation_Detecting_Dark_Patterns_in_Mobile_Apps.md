# 从探索走向揭示：检测移动应用中的暗黑模式

发布时间：2024年11月27日

`LLM应用` `移动应用` `用户行为`

> From Exploration to Revelation: Detecting Dark Patterns in Mobile Apps

# 摘要

> 移动应用在日常生活中不可或缺，然而它们常采用黑暗模式，像用视觉手段突出某些选项，或用语言策略诱导用户消费，以此操控用户行为。当下的研究主要依靠手动方式检测黑暗模式，这既费时又难以跟上不断更新和涌现的应用。虽然有些研究致力于自动检测，却局限于静态模式，仍需手动探索应用。为填补这些空缺，我们推出了 AppRay 这一创新系统，它将面向任务的应用探索与自动黑暗模式检测完美融合，降低了人工投入。我们的方法包含两步：其一，借助大型语言模型的常识知识进行有针对性的应用探索，同时辅以传统随机探索，以获取更广泛的 UI 状态。其二，开发了由基于对比学习的多标签分类器和基于规则的优化器驱动的静态与动态黑暗模式检测器来执行检测。我们贡献了两个数据集，即 AppRay-Dark 和 AppRay-Light，涵盖了 876 个 UI 和 871 个良性 UI 中的 18 种类型的 2185 个独特欺骗模式（包括 149 个动态实例）。这些数据集涵盖了静态和动态黑暗模式，同时保留了 UI 关系。实验结果表明，AppRay 能够高效探索应用并识别各类黑暗模式，表现出色。

> Mobile apps are essential in daily life, yet they often employ dark patterns, such as visual tricks to highlight certain options or linguistic tactics to nag users into making purchases, to manipulate user behavior. Current research mainly uses manual methods to detect dark patterns, a process that is time-consuming and struggles to keep pace with continually updating and emerging apps. While some studies targeted at automated detection, they are constrained to static patterns and still necessitate manual app exploration. To bridge these gaps, we present AppRay, an innovative system that seamlessly blends task-oriented app exploration with automated dark pattern detection, reducing manual efforts. Our approach consists of two steps: First, we harness the commonsense knowledge of large language models for targeted app exploration, supplemented by traditional random exploration to capture a broader range of UI states. Second, we developed a static and dynamic dark pattern detector powered by a contrastive learning-based multi-label classifier and a rule-based refiner to perform detection. We contributed two datasets, AppRay-Dark and AppRay-Light, with 2,185 unique deceptive patterns (including 149 dynamic instances) across 18 types from 876 UIs and 871 benign UIs. These datasets cover both static and dynamic dark patterns while preserving UI relationships. Experimental results confirm that AppRay can efficiently explore the app and identify a wide range of dark patterns with great performance.

[Arxiv](https://arxiv.org/abs/2411.18084)