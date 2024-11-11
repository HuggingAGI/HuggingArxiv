# 利用精确和完整的代码上下文来指导大型语言模型在自动误报缓解中。

发布时间：2024年11月05日

`LLM应用` `软件开发` `应用程序安全`

> Utilizing Precise and Complete Code Context to Guide LLM in Automatic False Positive Mitigation

# 摘要

> 静态应用程序安全测试（SAST）工具对于早期错误检测和代码质量至关重要，但经常产生误报，从而减缓开发进度。因此，自动减轻误报对于推进 SAST 工具至关重要。过去的努力使用了静态/动态分析或机器学习。大型语言模型的出现，擅长理解自然语言和代码，为提高 SAST 工具的准确性和可用性提供了有希望的方法。然而，现有的基于 LLM 的方法在两个关键领域需要改进：首先，与警告相关的提取代码片段经常混杂着不相关的控制和数据流，降低了精度；其次，关键的代码上下文经常缺失，导致不完整的表示，可能误导 LLM 并导致不准确的评估。为了确保使用精确和完整的代码上下文，从而避免误导并使 LLM 得出准确的结论，我们提出了 LLM4FPM。其核心组件之一是 eCPG-Slicer，它构建了一个扩展的代码属性图，并提取了行级别的精确代码上下文。此外，LLM4FPM 结合了 FARF 算法，该算法构建了一个文件引用图，然后在线性时间内有效地检测到与警告相关的所有文件，使 eCPG-Slicer 能够在这些文件中收集完整的代码上下文。我们在 Juliet 数据集上评估 LLM4FPM，它全面优于基线，在各种 CWE 中实现了超过 99％的 F1 分数。LLM4FPM 利用了一个免费的开源模型，避免了昂贵的替代方案，并将每次运行在 Juliet 上的检查成本降低了多达 2758 美元，每个警告的平均检查时间为 4.7 秒。我们的工作强调了精确和完整的代码上下文的关键影响，并突出了将程序分析与 LLM 相结合的潜力，提高了软件开发的质量和效率。

> Static Application Security Testing(SAST) tools are crucial for early bug detection and code quality but often generate false positives that slow development. Automating false positive mitigation is thus essential for advancing SAST tools. Past efforts use static/dynamic analysis or machine learning. The advent of Large Language Models, adept at understanding natural language and code, offers promising ways to improve the accuracy and usability of SAST tools. However, existing LLM-based methods need improvement in two key areas: first, extracted code snippets related to warnings are often cluttered with irrelevant control and data flows, reducing precision; second, critical code contexts are often missing, leading to incomplete representations that can mislead LLMs and cause inaccurate assessments. To ensure the use of precise and complete code context, thereby avoiding misguidance and enabling LLMs to reach accurate conclusions, we propose LLM4FPM. One of its core components is eCPG-Slicer, which builds an extended code property graph and extracts line-level, precise code context. Moreover, LLM4FPM incorporates FARF algorithm, which builds a file reference graph and then efficiently detects all files related to a warning in linear time, enabling eCPG-Slicer to gather complete code context across these files. We evaluate LLM4FPM on Juliet dataset, where it comprehensively outperforms the baseline, achieving an F1 score above 99% across various CWEs. LLM4FPM leverages a free, open-source model, avoiding costly alternatives and reducing inspection costs by up to $2758 per run on Juliet, with an average inspection time of 4.7 seconds per warning. Our work emphasizes the critical impact of precise and complete code context and highlights the potential of combining program analysis with LLMs, improving the quality and efficiency of software development.

[Arxiv](https://arxiv.org/abs/2411.03079)