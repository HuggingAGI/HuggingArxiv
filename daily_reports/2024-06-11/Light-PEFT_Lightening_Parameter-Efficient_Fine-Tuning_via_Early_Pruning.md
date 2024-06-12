# Light-PEFT：借助早期剪枝，实现参数高效微调的轻量化方案
发布时间：2024年06月06日

`动手训练`
> Light-PEFT: Lightening Parameter-Efficient Fine-Tuning via Early Pruning
>
> 在大型语言模型时代，参数高效的微调（PEFT）已成为主流技术。尽管如此，现有PEFT方法的训练效率仍有待提高。首先，对于某些微调任务，训练过程中对大规模基础模型的利用显得过于冗余。其次，随着模型规模的扩大，PEFT模块中新增的可训练参数增长显著且冗余，影响了效率。为此，我们提出了Light-PEFT框架，包含基础模型的掩码早期剪枝和PEFT的多粒度早期剪枝两种策略。该框架能在训练初期识别并剪除基础模型和PEFT模块中的冗余参数，从而实现更高效的微调。我们在GLUE、SuperGLUE、问答任务及多种模型上验证了这一方法。使用Light-PEFT，基础模型参数可减少超过40%，同时将可训练参数控制在原始PEFT方法的25%。与直接应用PEFT相比，Light-PEFT不仅加速了训练和推理过程，降低了内存消耗，还保持了PEFT的性能和即插即用特性。
>
> https://arxiv.org/abs/2406.03792

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.03792/x9.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.03792](https://arxiv.org/abs/2406.03792)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886