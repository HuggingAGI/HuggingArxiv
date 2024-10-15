# TMGBench：一款系统性游戏基准，专为评估 LLMs 的战略推理能力而设计

发布时间：2024年10月14日

`LLM应用` `人工智能`

> TMGBench: A Systematic Game Benchmark for Evaluating Strategic Reasoning Abilities of LLMs

# 摘要

> 随着大型语言模型 (LLM) 的迅猛发展，战略推理逐渐成为研究焦点。为了评估 LLM 的战略推理能力，博弈论因其简洁结构而备受青睐。然而，现有研究多局限于少数游戏，覆盖面不足。经典游戏场景易导致数据泄露，而现有基准缺乏扩展性，难以评估最先进模型。为此，我们推出了 TMGBench，一个涵盖广泛游戏类型、创新场景和灵活组织的基准。我们整合了 Robinson-Goforth 拓扑结构中的 144 种 2x2 游戏，并利用合成数据生成多样且高质量的场景，称为故事游戏。此外，我们通过将游戏视为原子单元，并采用顺序、并行和嵌套结构构建复杂形式，为 LLM 提供可持续框架。我们对主流 LLM 的全面评估包括理性推理、鲁棒性、心智理论 (ToM) 和复杂推理测试，揭示了准确性、一致性和 ToM 掌握方面的不足。OpenAI 的最新模型 o1-mini 在不同游戏中的表现也凸显了 TMGBench 的挑战性。

> The rapid advancement of large language models (LLMs) has accelerated their application in reasoning, with strategic reasoning drawing increasing attention. To evaluate LLMs' strategic reasoning capabilities, game theory, with its concise structure, has become a preferred approach. However, current research focuses on a limited selection of games, resulting in low coverage. Classic game scenarios risk data leakage, and existing benchmarks often lack extensibility, making them inadequate for evaluating state-of-the-art models. To address these challenges, we propose TMGBench, a benchmark with comprehensive game type coverage, novel scenarios, and flexible organization. Specifically, we incorporate all 144 game types summarized by the Robinson-Goforth topology of 2x2 games, constructed as classic games. We also employ synthetic data generation to create diverse, higher-quality scenarios through topic guidance and human inspection, referred to as story-based games. Lastly, we provide a sustainable framework for increasingly powerful LLMs by treating these games as atomic units and organizing them into more complex forms via sequential, parallel, and nested structures. Our comprehensive evaluation of mainstream LLMs covers tests on rational reasoning, robustness, Theory-of-Mind (ToM), and reasoning in complex forms. Results reveal flaws in accuracy, consistency, and varying mastery of ToM. Additionally, o1-mini, OpenAI's latest reasoning model, achieved accuracy rates of 66.6%, 60.0%, and 70.0% on sequential, parallel, and nested games, highlighting TMGBench's challenges.

[Arxiv](https://arxiv.org/abs/2410.10479)