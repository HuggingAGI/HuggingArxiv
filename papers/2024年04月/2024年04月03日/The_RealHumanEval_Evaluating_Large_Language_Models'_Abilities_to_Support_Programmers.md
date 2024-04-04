# RealHumanEval：探究大型语言模型在辅助编程方面的实际效能

发布时间：2024年04月03日

`LLM应用` `软件开发`

> The RealHumanEval: Evaluating Large Language Models' Abilities to Support Programmers

# 摘要

> 在对大型语言模型（LLM）进行代码能力的评估中，我们主要参考了如HumanEval（Chen等人，2021年）这样的静态基准测试，它们评估LLM生成能通过单元测试的完整代码的能力。随着LLM逐渐成为编程助手，我们探究了这些基准测试中的提升是否真正提高了程序员在使用LLM编码时的生产力，包括他们在编码上所花费的时间。我们不仅关注静态基准测试，还研究了偏好度量指标的实用性，如代码接受率或复制率，这些可能作为衡量LLM帮助程度的代理指标。我们推出了RealHumanEval，一个在线平台，用以衡量LLM在自动补全或聊天支持方面协助程序员的能力。通过RealHumanEval，我们组织了一项用户研究（参与者213人），用户与六种性能各异的基础模型LLM进行了互动。尽管静态基准测试没有将人类参与考虑在内，我们的研究发现，基准测试性能的提升确实带来了程序员生产力的增长；但基准测试与人为性能之间的差异并非成正比，这一点在LLM的两种支持形式中都有所体现。与此相反，程序员的个人喜好与他们的实际编码表现并不挂钩，这突显了我们需要更多以人为核心的有效评估指标。此外，我们还将RealHumanEval开源，以便对新模型进行更注重人类体验的评估，并分享研究数据，以助力提升代码模型的质量。

> Evaluation of large language models (LLMs) for code has primarily relied on static benchmarks, including HumanEval (Chen et al., 2021), which measure the ability of LLMs to generate complete code that passes unit tests. As LLMs are increasingly used as programmer assistants, we study whether gains on existing benchmarks translate to gains in programmer productivity when coding with LLMs, including time spent coding. In addition to static benchmarks, we investigate the utility of preference metrics that might be used as proxies to measure LLM helpfulness, such as code acceptance or copy rates. To do so, we introduce RealHumanEval, a web interface to measure the ability of LLMs to assist programmers, through either autocomplete or chat support. We conducted a user study (N=213) using RealHumanEval in which users interacted with six LLMs of varying base model performance. Despite static benchmarks not incorporating humans-in-the-loop, we find that improvements in benchmark performance lead to increased programmer productivity; however gaps in benchmark versus human performance are not proportional -- a trend that holds across both forms of LLM support. In contrast, we find that programmer preferences do not correlate with their actual performance, motivating the need for better, human-centric proxy signals. We also open-source RealHumanEval to enable human-centric evaluation of new models and the study data to facilitate efforts to improve code models.

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x1.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x2.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x3.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x4.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x5.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x6.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x7.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x8.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x9.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x10.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x11.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/autocomplete.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x12.jpg)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x13.jpg)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x14.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x15.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x16.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x17.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x18.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x19.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x20.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x21.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x22.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x23.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x24.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x25.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x26.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x27.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x28.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x29.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x30.png)

![RealHumanEval：探究大型语言模型在辅助编程方面的实际效能](../../../paper_images/2404.02806/x31.png)

[Arxiv](https://arxiv.org/abs/2404.02806)