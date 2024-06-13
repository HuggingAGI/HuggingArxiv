# DLLens：借助 LLM 辅助合成技术，深度检测深度学习库

发布时间：2024年06月12日

`LLM应用

这篇论文介绍了DLLens，一种创新的差分测试技术，它利用大型语言模型（LLM）来合成深度学习库中的API对应物，以检测功能缺陷。这种方法特别关注于通过静态分析提取路径约束，并生成多样化的测试输入，从而在TensorFlow和PyTorch等库中提高了测试的效率和效果。因此，这项工作属于LLM在实际应用中的使用，特别是在软件测试和质量保障领域。` `软件测试`

> DLLens: Testing Deep Learning Libraries via LLM-aided Synthesis

# 摘要

> 测试是深度学习库质量保障的关键。现有技术多依赖差分测试以减少对测试预言的依赖，但在寻找功能等效实现和生成多样化测试输入方面仍有局限。DLLens，一种创新的差分测试技术，通过观察不同库中API虽非一对一映射却能相互模拟的特性，利用大型语言模型合成API对应物，有效检测DL库的功能缺陷。DLLens不仅通过静态分析提取路径约束，指导生成多样化测试输入，还在TensorFlow和PyTorch库中展现了卓越性能，合成的API对应物数量是现有技术的两倍多，发现的约束和错误数量也显著增加。DLLens已在新近的库中发现56个错误，其中41个为新发现，39个已获开发者确认，19个已修复。

> Testing is a major approach to ensuring the quality of deep learning (DL) libraries. Existing testing techniques commonly adopt differential testing to relieve the need for test oracle construction. However, these techniques are limited in finding implementations that offer the same functionality and generating diverse test inputs for differential testing. This paper introduces DLLens, a novel differential testing technique for DL library testing. Our insight is that APIs in different DL libraries are commonly designed to accomplish various computations for the same set of published DL algorithms. Although the mapping of these APIs is not often one-to-one, we observe that their computations can be mutually simulated after proper composition and adaptation. The use of these simulation counterparts facilitates differential testing for the detection of functional DL library bugs. Leveraging the insight, we propose DLLens as a novel mechanism that utilizes a large language model (LLM) to synthesize valid counterparts of DL library APIs. To generate diverse test inputs, DLLens incorporates a static analysis method aided by LLM to extract path constraints from all execution paths in each API and its counterpart's implementations. These path constraints are then used to guide the generation of diverse test inputs. We evaluate DLLens on two popular DL libraries, TensorFlow and PyTorch. Our evaluation shows that DLLens can synthesize counterparts for more than twice as many APIs found by state-of-the-art techniques on these libraries. Moreover, DLLens can extract 26.7% more constraints and detect 2.5 times as many bugs as state-of-the-art techniques. DLLens has successfully found 56 bugs in recent TensorFlow and PyTorch libraries. Among them, 41 are previously unknown, 39 of which have been confirmed by developers after reporting, and 19 of those confirmed bugs have been fixed by developers.

[Arxiv](https://arxiv.org/abs/2406.07944)