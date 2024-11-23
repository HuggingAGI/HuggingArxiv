# 对 LLM 防护栏处理多语言毒性的情况进行基准测试

发布时间：2024年10月29日

`LLM应用` `语言模型` `防护栏`

> Benchmarking LLM Guardrails in Handling Multilingual Toxicity

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，防护栏在检测和抵御有害内容方面变得至关重要。然而，随着LLMs在多语言场景中的愈发普及，它们处理多语言有害输入的有效性尚不明确。在本项工作中，我们引入了一套全面的多语言测试套件，涵盖七个数据集和十余种语言，用于对先进防护栏的性能进行基准测试。我们还探究了防护栏对近期越狱技术的抵御能力，并评估了上下文安全策略和语言资源可用性对防护栏性能的影响。我们的发现表明，现有的防护栏在处理多语言有害性方面依旧效果不佳，且对越狱提示缺乏稳健性。此项工作旨在明确防护栏的局限性，在多语言场景中构建更可靠、更值得信赖的LLMs。

> With the ubiquity of Large Language Models (LLMs), guardrails have become crucial to detect and defend against toxic content. However, with the increasing pervasiveness of LLMs in multilingual scenarios, their effectiveness in handling multilingual toxic inputs remains unclear. In this work, we introduce a comprehensive multilingual test suite, spanning seven datasets and over ten languages, to benchmark the performance of state-of-the-art guardrails. We also investigates the resilience of guardrails against recent jailbreaking techniques, and assess the impact of in-context safety policies and language resource availability on guardrails' performance. Our findings show that existing guardrails are still ineffective at handling multilingual toxicity and lack robustness against jailbreaking prompts. This work aims to identify the limitations of guardrails and to build a more reliable and trustworthy LLMs in multilingual scenarios.

[Arxiv](https://arxiv.org/abs/2410.22153)