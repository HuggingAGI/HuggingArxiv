# ISC4DGF：借助 LLM 驱动的初始种子语料库生成，提升有向灰盒模糊测试的效能

发布时间：2024年09月22日

`LLM应用` `软件安全` `模糊测试`

> ISC4DGF: Enhancing Directed Grey-box Fuzzing with LLM-Driven Initial Seed Corpus Generation

# 摘要

> 模糊测试在识别软件漏洞中至关重要，AFL和Angora等覆盖引导的灰盒模糊器在广泛检测中表现优异。然而，随着对目标检测需求的增加，定向灰盒模糊测试（DGF）变得尤为重要，专注于特定漏洞。初始种子语料库，作为模糊器的起点，对于确定探索路径至关重要。设计良好的种子语料库能更有效地引导模糊器，提高检测效率和成功率。尽管其重要性，许多研究仍集中在改进指导机制，而对优化初始种子语料库的关注较少。本文介绍了ISC4DGF，一种利用大型语言模型（LLMs）为DGF生成优化种子语料库的新方法。通过深度软件理解和精细用户输入，ISC4DGF创建了精确的种子语料库，高效触发特定漏洞。在AFL上实现并对比AFLGo、FairFuzz和Entropic等先进模糊器，ISC4DGF实现了显著的加速和目标到达减少。此外，ISC4DGF在减少代码覆盖的情况下，更有效地检测目标漏洞，提升了整体效率。

> Fuzz testing is crucial for identifying software vulnerabilities, with coverage-guided grey-box fuzzers like AFL and Angora excelling in broad detection. However, as the need for targeted detection grows, directed grey-box fuzzing (DGF) has become essential, focusing on specific vulnerabilities. The initial seed corpus, which consists of carefully selected input samples that the fuzzer uses as a starting point, is fundamental in determining the paths that the fuzzer explores. A well-designed seed corpus can guide the fuzzer more effectively towards critical areas of the code, improving the efficiency and success of the fuzzing process. Even with its importance, many works concentrate on refining guidance mechanisms while paying less attention to optimizing the initial seed corpus. In this paper, we introduce ISC4DGF, a novel approach to generating optimized initial seed corpus for DGF using Large Language Models (LLMs). By leveraging LLMs' deep software understanding and refined user inputs, ISC4DGF creates precise seed corpus that efficiently trigger specific vulnerabilities. Implemented on AFL and tested against state-of-the-art fuzzers like AFLGo, FairFuzz, and Entropic using the Magma benchmark, ISC4DGF achieved a 35.63x speedup and 616.10x fewer target reaches. Moreover, ISC4DGF focused on more effectively detecting target vulnerabilities, enhancing efficiency while operating with reduced code coverage.

[Arxiv](https://arxiv.org/abs/2409.14329)