# 运用知识编辑技术净化大型语言模型，旨在消除潜在有害内容，提升模型输出的安全性和准确性。

发布时间：2024年03月21日

`LLM应用` `人工智能安全`

> Detoxifying Large Language Models via Knowledge Editing

# 摘要

> 本文致力于研究如何运用知识编辑技术来净化大型语言模型（LLMs）。我们搭建了一个名为SafeEdit的基准测试平台，它囊括了九类安全隐患，并配备了各种有力的攻击提示和一套全面的系统评估标准。实验结果显示，相比传统方法，知识编辑技术有望高效地对LLMs进行去毒处理，同时尽量减少对其通用性能的影响。此外，我们创新提出了一项简洁实用的新基线方法——“手术中神经监控下的去毒化”（DINM），仅需一步实例操作，就能在短时间内明显降低LLMs的毒性。我们还深入剖析了各类去毒化方法的内在机制，揭示出以往如SFT、DPO等方法主要是在压制有毒参数的激活，而DINM则是更进一步，在某种程度上实质降低了有毒参数的毒性并实现持久性的调整。我们期待这些洞见能照亮未来研发LLMs去毒化技术及探索其底层知识机制的道路，相关代码和基准已发布于https://github.com/zjunlp/EasyEdit供参考。

> This paper investigates using knowledge editing techniques to detoxify Large Language Models (LLMs). We construct a benchmark, SafeEdit, which covers nine unsafe categories with various powerful attack prompts and equips comprehensive metrics for systematic evaluation. We conduct experiments to compare knowledge editing approaches with previous baselines, indicating that knowledge editing has the potential to efficiently detoxify LLMs with limited impact on general performance. Then, we propose a simple yet effective baseline, dubbed Detoxifying with Intraoperative Neural Monitoring (DINM), to diminish the toxicity of LLMs within a few tuning steps via only one instance. We further provide an in-depth analysis of the internal mechanism for various detoxify approaches, demonstrating that previous methods like SFT and DPO may merely suppress the activations of toxic parameters, while DINM mitigates the toxicity of the toxic parameters to a certain extent, making permanent adjustments. We hope that these insights could shed light on future work of developing detoxifying approaches and the underlying knowledge mechanisms of LLMs. Code and benchmark are available at https://github.com/zjunlp/EasyEdit.

[Arxiv](https://arxiv.org/abs/2403.14472)