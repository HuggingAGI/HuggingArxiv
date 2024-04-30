![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# AdvPrompter：一种为大型语言模型（LLMs）量身定制的快速自适应对抗性提示工具
发布时间：2024年04月21日

`模型安全`
> 近期，大型语言模型（LLMs）虽然取得了显著成就，却也容易遭受特定越狱攻击，从而产生不当或有害的内容。传统的手动红队战术，通过添加后缀等方式寻找对抗性提示，不仅效率低下，还耗费大量时间。而自动化的对抗性提示生成方法，往往产生无意义的攻击，容易被基于困惑度的过滤器识破，且可能需要目标LLM的梯度信息，或因优化过程繁琐而难以扩展。本文提出了一种创新方法，利用另一个名为AdvPrompter的LLM快速生成易于人类理解的对抗性提示，速度是现有优化方法的800倍。我们采用了一种新颖的算法训练AdvPrompter，无需获取目标LLM的梯度信息。该过程包括两个交替步骤：首先，优化AdvPrompter的预测以产生高质量的目标对抗性后缀；其次，使用这些后缀对AdvPrompter进行低秩微调。经过训练的AdvPrompter能够生成不改变指令含义的隐蔽后缀，诱使目标LLM作出有害回应。在多个流行的开源目标LLM上的实验表明，我们的方法在AdvBench数据集上达到了最佳效果，并且这些成果同样适用于封闭源的黑盒LLM API。此外，我们还证明了通过在AdvPrompter生成的合成数据集上进行微调，可以在保持高性能的同时，增强LLM对越狱攻击的抵抗力，即保持高MMLU得分。



- 论文原文 [https://arxiv.org/abs/2404.16873](https://arxiv.org/abs/2404.16873)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode3.png)