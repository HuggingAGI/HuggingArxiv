# EEE-Bench：一个综合性的多模态电气与电子工程基准

发布时间：2024年11月03日

`LLM应用` `电气和电子工程` `多模态模型`

> EEE-Bench: A Comprehensive Multimodal Electrical And Electronics Engineering Benchmark

# 摘要

> 近期针对大型语言模型（LLMs）和大型多模态模型（LMMs）的研究，在科学、数学等众多领域展现出良好的能力。但它们在更具挑战且贴近现实的工程场景中的表现，尚未得到系统探究。为填补这一空缺，我们推出了 EEE-Bench，这一多模态基准以电气和电子工程（EEE）为测试平台，用于评估 LMMs 解决实际工程任务的水平。该基准包含 2860 个精心筛选的问题，涵盖模拟电路、控制系统等 10 个核心子领域。相较其他领域的基准，工程问题本质上 1）视觉呈现更复杂多变 2）解决方案更具不确定性。要成功解决这些问题，往往需要更严格地整合视觉与文本信息，因为模型既要理解诸如抽象电路和系统图之类的复杂图像，又要遵循专业指令，这使其成为 LMM 评估的上佳之选。除了 EEE-Bench，我们还对 17 种广泛使用的开源和闭源的 LLMs 及 LMMs 进行了大量的定量评估和细致分析。结果显示，当前的基础模型在 EEE 方面存在明显短板，平均性能介于 19.48％至 46.78％之间。最后，我们揭示并探讨了 LMMs 的一个关键缺陷，我们称之为“懒惰”：即在推理技术图像问题时，倾向于依赖文本走捷径，而忽视视觉背景。总之，我们认为 EEE-Bench 不但揭示了 LMMs 的一些显著局限，还为推动其在实际工程任务中的应用研究提供了宝贵资源，有助于提升其应对复杂现实场景的能力。

> Recent studies on large language models (LLMs) and large multimodal models (LMMs) have demonstrated promising skills in various domains including science and mathematics. However, their capability in more challenging and real-world related scenarios like engineering has not been systematically studied. To bridge this gap, we propose EEE-Bench, a multimodal benchmark aimed at assessing LMMs' capabilities in solving practical engineering tasks, using electrical and electronics engineering (EEE) as the testbed. Our benchmark consists of 2860 carefully curated problems spanning 10 essential subdomains such as analog circuits, control systems, etc. Compared to benchmarks in other domains, engineering problems are intrinsically 1) more visually complex and versatile and 2) less deterministic in solutions. Successful solutions to these problems often demand more-than-usual rigorous integration of visual and textual information as models need to understand intricate images like abstract circuits and system diagrams while taking professional instructions, making them excellent candidates for LMM evaluations. Alongside EEE-Bench, we provide extensive quantitative evaluations and fine-grained analysis of 17 widely-used open and closed-sourced LLMs and LMMs. Our results demonstrate notable deficiencies of current foundation models in EEE, with an average performance ranging from 19.48% to 46.78%. Finally, we reveal and explore a critical shortcoming in LMMs which we term laziness: the tendency to take shortcuts by relying on the text while overlooking the visual context when reasoning for technical image problems. In summary, we believe EEE-Bench not only reveals some noteworthy limitations of LMMs but also provides a valuable resource for advancing research on their application in practical engineering tasks, driving future improvements in their capability to handle complex, real-world scenarios.

[Arxiv](https://arxiv.org/abs/2411.01492)