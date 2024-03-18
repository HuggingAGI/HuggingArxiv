# [为助力现实世界中的事实核查，我们引入了多模态大型语言模型。这类模型能够整合多种信息源，以提升对复杂情境中事实信息的精准判断能力。]

发布时间：2024年03月06日

`LLM应用`

> Multimodal Large Language Models to Support Real-World Fact-Checking

> MLLMs 能够助力人类应对海量信息，尽管它们已被应用于事实核查场景，但其效能与局限尚待深度挖掘。本研究首次尝试弥补这一认知空白，提出了一个体系化的评估框架，专注于考察当前多模态模型如何有效支持现实生活中的事实核查。该方法摒弃了额外证据，完全依赖于模型自身的知识库及推理技能。我们精心设计了一系列提示，以揭示模型的预测内容、解释说明及其自信程度，从而探究模型在准确度、抗干扰性以及失效原因等方面的问题。实验结果显示，GPT-4V 在识破并解析含有恶意或误导性质的多模态声明时展现出优越性能，能够阐明其中不合理之处及其背后的动机。然而，现有的开源多模态模型普遍存在较强的偏向性，对输入提示极其敏感。此项研究对于打击虚假多模态信息传播及构建安全可靠的多模态模型具有重要的启示意义。

> Multimodal large language models (MLLMs) carry the potential to support humans in processing vast amounts of information. While MLLMs are already being used as a fact-checking tool, their abilities and limitations in this regard are understudied. Here is aim to bridge this gap. In particular, we propose a framework for systematically assessing the capacity of current multimodal models to facilitate real-world fact-checking. Our methodology is evidence-free, leveraging only these models' intrinsic knowledge and reasoning capabilities. By designing prompts that extract models' predictions, explanations, and confidence levels, we delve into research questions concerning model accuracy, robustness, and reasons for failure. We empirically find that (1) GPT-4V exhibits superior performance in identifying malicious and misleading multimodal claims, with the ability to explain the unreasonable aspects and underlying motives, and (2) existing open-source models exhibit strong biases and are highly sensitive to the prompt. Our study offers insights into combating false multimodal information and building secure, trustworthy multimodal models. To the best of our knowledge, we are the first to evaluate MLLMs for real-world fact-checking.

[Arxiv](https://arxiv.org/abs/2403.03627)