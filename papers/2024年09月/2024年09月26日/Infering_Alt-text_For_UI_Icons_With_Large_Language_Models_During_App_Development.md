# 在应用开发中，借助大型语言模型为 UI 图标生成替代文本

发布时间：2024年09月26日

`LLM应用` `移动应用` `可访问性`

> Infering Alt-text For UI Icons With Large Language Models During App Development

# 摘要

> 确保移动应用的可访问性对视觉障碍用户尤为重要，但现有方法在生成图标替代文本时面临挑战。我们提出了一种新方法，利用大型语言模型（LLMs）在部分UI数据的基础上，自动生成描述性替代文本。通过整合图标的多维度信息，我们在小规模数据集上微调LLM，成功开发了IconDesc。实证评估和用户研究显示，IconDesc在生成相关替代文本方面表现优异，成为提升UI可访问性的有力工具。

> Ensuring accessibility in mobile applications remains a significant challenge, particularly for visually impaired users who rely on screen readers. User interface icons are essential for navigation and interaction and often lack meaningful alt-text, creating barriers to effective use. Traditional deep learning approaches for generating alt-text require extensive datasets and struggle with the diversity and imbalance of icon types. More recent Vision Language Models (VLMs) require complete UI screens, which can be impractical during the iterative phases of app development. To address these issues, we introduce a novel method using Large Language Models (LLMs) to autonomously generate informative alt-text for mobile UI icons with partial UI data. By incorporating icon context, that include class, resource ID, bounds, OCR-detected text, and contextual information from parent and sibling nodes, we fine-tune an off-the-shelf LLM on a small dataset of approximately 1.4k icons, yielding IconDesc. In an empirical evaluation and a user study IconDesc demonstrates significant improvements in generating relevant alt-text. This ability makes IconDesc an invaluable tool for developers, aiding in the rapid iteration and enhancement of UI accessibility.

[Arxiv](https://arxiv.org/abs/2409.18060)