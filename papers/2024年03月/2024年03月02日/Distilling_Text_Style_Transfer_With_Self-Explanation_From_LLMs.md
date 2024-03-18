# [本研究致力于从大型语言模型（LLM）中提炼出带有自我解释功能的文本风格转换技术，旨在探索如何有效利用LLM进行文本风格迁移，并通过自我解释机制提升其可解释性和应用效果。]

发布时间：2024年03月02日

`LLM应用`

> Distilling Text Style Transfer With Self-Explanation From LLMs

> TST技术致力于在保持文本实质内容的同时改变其风格，然而此类任务往往面临平行数据集不足的问题。为此，我们创新性地提出了CoTeX框架，该框架巧妙利用LLMs和CoT引导策略，以应对TST挑战。CoTeX成功地将LLMs强大的复杂改写和逻辑推理能力浓缩至轻量级模型中，使得这种模型能够灵活适应非平行及平行数据场景。实验证明，在四个不同TST数据集上，尤其是在低资源环境下，CoTeX表现优于传统监督微调和知识蒸馏等方法。我们深入研究并全面比较了CoTeX与当前主流的无监督、监督、ICL技术以及针对指令优化的LLMs。更值得一提的是，CoTeX还具备独特优势，即能为风格转换的过程提供清晰易懂的解释说明。

> Text Style Transfer (TST) seeks to alter the style of text while retaining its core content. Given the constraints of limited parallel datasets for TST, we propose CoTeX, a framework that leverages large language models (LLMs) alongside chain-of-thought (CoT) prompting to facilitate TST. CoTeX distills the complex rewriting and reasoning capabilities of LLMs into more streamlined models capable of working with both non-parallel and parallel data. Through experimentation across four TST datasets, CoTeX is shown to surpass traditional supervised fine-tuning and knowledge distillation methods, particularly in low-resource settings. We conduct a comprehensive evaluation, comparing CoTeX against current unsupervised, supervised, in-context learning (ICL) techniques, and instruction-tuned LLMs. Furthermore, CoTeX distinguishes itself by offering transparent explanations for its style transfer process.

[Arxiv](https://arxiv.org/abs/2403.01106)