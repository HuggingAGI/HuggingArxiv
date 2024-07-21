# 大型语言模型推理研究综述
发布时间：2024年07月16日


> Reasoning with Large Language Models, a Survey
>
> 将语言模型扩展至数十亿参数，开启了上下文学习的新纪元，使得模型能够对未经专门训练的任务进行指令调整和少样本学习，从而在翻译、摘要和问答等语言任务上取得显著突破。不仅如此，近期思维链提示学习的进步更展示了LLMs在“系统2”推理能力上的强大潜力，引发了关于LLMs能否进行推理的讨论。这一探索始于LLMs是否能解决小学数学应用题的疑问。本文深入探讨了基于提示的推理与LLMs领域的迅猛发展，提出了一套分类法，涵盖了多步骤推理的生成、评估与控制方式。我们详细剖析了核心方法与待解难题，并勾勒出近期的研究蓝图。最后，我们探讨了推理与基于提示学习之间的联系，以及推理、序列决策过程与强化学习之间的相互关系。我们发现，通过巧妙运用提示，推理过程的自改进、自我反思及部分元认知能力得以实现。然而，真正的自我改进与自我推理，即从LLMs辅助的推理转向LLMs自主的推理，仍是未来探索的方向。
>
> https://arxiv.org/abs/2407.11511

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/Taxonomy7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/scratchpad2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/cot.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/zero.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/selfask.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/codex.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/debug.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/pal.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/refiner.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/star.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/saycan.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/inner.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/least.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/tot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/bot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/beam.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/rl.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/progressive.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/selfref.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/selfrefine2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/react.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/reflexion3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/reflexion.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/minecraft.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.11511/mp.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.11511](https://arxiv.org/abs/2407.11511)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1