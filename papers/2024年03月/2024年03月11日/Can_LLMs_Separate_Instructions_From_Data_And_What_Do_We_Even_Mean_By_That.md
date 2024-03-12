# [LLMs 是否具备区分指令与数据的能力？而这个说法背后又蕴含着怎样的深意呢？](https://arxiv.org/abs/2403.06833)

发布时间：2024年03月11日

`LLM 理论`

> Can LLMs Separate Instructions From Data? And What Do We Even Mean By That?

> 指令优化的 LLMs 已展现卓越成就，为广泛应用带来了无限可能。但这类模型缺乏诸如指令与数据分离等基础安全特性，这是计算机科学其他领域的常规规范，从而可能导致其出现功能异常，易受第三方通过巧妙手段进行操控和干扰。当前，对于“指令-数据分离”的确切界定及检测方法尚无统一标准。为此，我们在本研究中致力于解决这个问题，提出了一种形式化衡量指令数据分离程度的方法及其经验性变体，该变体可通过模型黑盒输出进行计算。同时，我们构建了一个名为 SEP（执行还是处理？）的新数据集，用于估算这一分离指标，并在多种尖端开源和闭源 LLMs 上进行了实验验证。最终，我们以量化的证据表明，按照我们的度量标准，所有被评估的 LLMs 在指令数据分离方面表现均不尽人意。相关源代码和 SEP 数据集已在 GitHub 开源，地址为 https://github.com/egozverev/Shold-It-Be-Executed-Or-Processed。

> Instruction-tuned Large Language Models (LLMs) have achieved breakthrough results, opening countless new possibilities for many practical applications. However, LLMs lack elementary safety features that are established norms in other areas of computer science, such as the separation between instructions and data, causing them to malfunction or rendering them vulnerable to manipulation and interference by third parties e.g., via indirect prompt/command injection. Even worse, so far, there is not even an established definition of what precisely such a separation would mean and how its violation could be tested. In this work, we aim to close this gap. We introduce a formal measure to quantify the phenomenon of instruction-data separation as well as an empirical variant of the measure that can be computed from a model`s black-box outputs. We also introduce a new dataset, SEP (Should it be Executed or Processed?), which allows estimating the measure, and we report results on several state-of-the-art open-source and closed LLMs. Finally, we quantitatively demonstrate that all evaluated LLMs fail to achieve a high amount of separation, according to our measure. The source code and SEP dataset are openly accessible at https://github.com/egozverev/Shold-It-Be-Executed-Or-Processed.

![LLMs 是否具备区分指令与数据的能力？而这个说法背后又蕴含着怎样的深意呢？](../../../paper_images/2403.06833/data_example.png)