# 利用多模态大型语言模型实现视觉驱动的移动GUI自动化测试
发布时间：2024年07月03日

`代码编写`
> Vision-driven Automated Mobile GUI Testing via Multimodal Large Language Model
>
> 随着软件渲染技术的提升，移动应用的GUI页面如今承载了丰富的视觉信息，这些视觉语义对应用逻辑至关重要，同时也为软件测试带来了新挑战。尽管自动化GUI测试有所进步，但由于缺乏有效的测试预言，其效果仍局限于识别明显的崩溃错误。然而，许多非崩溃错误，如意外行为或界面错位，往往难以被现有技术捕捉。这些错误虽可能通过视觉线索提供潜在的测试预言，但检测它们需要深入理解GUI页面间的操作逻辑，这对传统技术构成挑战。鉴于多模态大型语言模型（MLLM）在视觉与语言理解上的卓越能力，本文提出了一种基于视觉的自动化GUI测试方法——VisionDroid，旨在利用MLLM检测非崩溃功能错误。该方法首先提取GUI文本信息并结合截图形成视觉提示，使MLLM能理解GUI上下文。随后，功能感知探索器引导MLLM进行深入且面向功能的GUI页面探索，而逻辑感知错误检测器则将探索历史按逻辑分段，并引导MLLM进行错误检测。我们在三个数据集上验证了VisionDroid，并对比了10个基线方法，证实了其优异性能。消融研究进一步凸显了各模块的贡献。此外，VisionDroid在Google Play上发现了29个新错误，其中19个已获确认并得到修复。
>
> https://arxiv.org/abs/2407.03037

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/bug-example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/Pilot-study.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/overview.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/example-screenshot.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/example-history.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/explore-prompt.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/test-seq-example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/Detect-prompt.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.03037/RQ2-2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.03037](https://arxiv.org/abs/2407.03037)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1