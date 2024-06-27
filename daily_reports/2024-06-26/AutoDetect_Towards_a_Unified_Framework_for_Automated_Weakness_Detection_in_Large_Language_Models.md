# AutoDetect：构建大型语言模型弱点自动化检测的统一框架
发布时间：2024年06月24日


> AutoDetect: Towards a Unified Framework for Automated Weakness Detection in Large Language Models
>
> 尽管大型语言模型（LLMs）日益强大，但仍存在微妙的弱点，如在指令遵循或编码任务中的错误。这些意外错误在实际应用中可能带来严重后果，因此系统地探究LLMs的局限性至关重要。传统的基准测试方法难以精准定位模型缺陷，而手动检查则成本高昂且不可扩展。为此，我们提出了一个名为AutoDetect的统一框架，旨在自动检测LLMs在多任务中的弱点。该框架借鉴教育评估的理念，集成了三个由LLM驱动的智能体：考官、提问者和评估者，通过它们的协同工作，实现对模型弱点的全面深入识别。AutoDetect在揭示模型缺陷方面成效显著，识别成功率在ChatGPT和Claude等主流模型中超过30%。更重要的是，这些识别出的弱点能有效指导模型优化，其效果远超无针对性的数据增强方法，如Self-Instruct。我们的方法已显著提升了包括Llama系列和Mistral-7b在内的流行LLMs的性能，在多个基准测试中提升了超过10%。相关代码和数据已公开发布于https://github.com/thu-coai/AutoDetect。
>
> https://arxiv.org/abs/2406.16714

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/score_change_all_avg_gpt4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/comp35_improve.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.16714/x12.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.16714](https://arxiv.org/abs/2406.16714)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2