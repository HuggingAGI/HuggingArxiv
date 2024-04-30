# 实现零样本补丁的自动化移植，以应对硬分叉的挑战。

发布时间：2024年04月27日

`LLM应用` `软件工程`

> Automating Zero-Shot Patch Porting for Hard Forks

# 摘要

> 代码分支是一种常见的复用手段，它允许开发者通过复制并修改现有代码库来创建软件的新变体，即硬分叉。尽管分支带来便利，但它也增加了软件维护的工作量，因为开发者必须在不同的硬分叉间同步补丁，以修复相似的问题或添加相同特性。由于源项目与硬分叉之间的差异，这一过程变得复杂且耗时。本研究首次尝试在零样本环境下自动化硬分叉的补丁移植。我们通过对过去十年 Vim 到 Neovim 的补丁移植情况进行了实证分析，以了解补丁移植的实际需求和现有方法的不足。基于此，我们提出了一种基于大型语言模型的新方法 PPatHF，它能够在函数级别自动移植硬分叉补丁。PPatHF 包含简化和移植两个模块，它首先精简函数输入，去除与补丁不相关的代码片段，然后利用语言模型将补丁应用到目标项目的函数上。我们在 310 个从 Vim 移植至 Neovim 的补丁上测试了 PPatHF，结果显示其性能显著超过现有基线，成功移植了 131 个（占比 42.3%）补丁，并减少了开发者 57% 的手动编辑工作量。

> Forking is a typical way of code reuse, which provides a simple way for developers to create a variant software (denoted as hard fork) by copying and modifying an existing codebase. Despite of the benefits, forking also leads to duplicate efforts in software maintenance. Developers need to port patches across the hard forks to address similar bugs or implement similar features. Due to the divergence between the source project and the hard fork, patch porting is complicated, which requires an adaption regarding different implementations of the same functionality. In this work, we take the first step to automate patch porting for hard forks under a zero-shot setting. We first conduct an empirical study of the patches ported from Vim to Neovim over the last ten years to investigate the necessities of patch porting and the potential flaws in the current practice. We then propose a large language model (LLM) based approach (namely PPatHF) to automatically port patches for hard forks on a function-wise basis. Specifically, PPatHF is composed of a reduction module and a porting module. Given the pre- and post-patch versions of a function from the reference project and the corresponding function from the target project, the reduction module first slims the input functions by removing code snippets less relevant to the patch. Then, the porting module leverages a LLM to apply the patch to the function from the target project. We evaluate PPatHF on 310 Neovim patches ported from Vim. The experimental results show that PPatHF outperforms the baselines significantly. Specifically, PPatHF can correctly port 131 (42.3%) patches and automate 57% of the manual edits required for the developer to port the patch.

[Arxiv](https://arxiv.org/abs/2404.17964)