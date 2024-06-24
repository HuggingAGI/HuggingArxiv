# 揭秘 CoT-Augmented Distillation 的神秘面纱
发布时间：2024年06月20日

`提示工程`
> Investigating Mysteries of CoT-Augmented Distillation
>
> 通过引入“思维链”（CoT）理性——一系列传达推理过程的令牌——已证实能显著提升大型语言模型（LLM）在问答任务上的表现。近期研究进一步发现，这些理性在模型蒸馏中也大有裨益：在微调小型模型时，若加入来自大型“教师”模型的CoT序列及目标标签，往往能带来显著性能提升。本研究旨在探究这一额外训练信号为何及如何助力模型蒸馏，并揭示了一些出人意料的发现。具体而言：（1）将CoT序列置于标签之后而非之前，能持续提升下游任务表现，这意味着在测试阶段，学生模型无需实际推理即可受益。（2）即便CoT序列并非连贯推理，仅简单附加亦能带来性能提升，且对令牌顺序变化具有较强适应性。更有甚者，（3）仅需少数关键令牌，便能达到与完整理性蒸馏相当的改进效果。
>
> https://arxiv.org/abs/2406.14511

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/unk_plot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/masking.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/x4.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/x5.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.14511/x6.jpg)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.14511](https://arxiv.org/abs/2406.14511)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2