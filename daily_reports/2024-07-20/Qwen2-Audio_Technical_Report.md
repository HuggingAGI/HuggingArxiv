# Qwen2-Audio 技术报告
发布时间：2024年07月15日

`动手训练`
> Qwen2-Audio Technical Report
>
> 我们推出了Qwen-Audio的最新成果——Qwen2-Audio，这是一个能够处理多种音频输入并进行分析或直接响应语音指令的大型音频-语言模型。通过使用自然语言提示简化预训练流程并扩充数据量，我们增强了Qwen2-Audio的指令执行能力，并设计了两种音频交互模式：语音聊天和音频分析。在语音聊天模式下，用户可与Qwen2-Audio自由语音交流，无需文本介入；而在音频分析模式中，用户可结合音频与文本指令进行深入分析。值得一提的是，这两种模式间的切换无需系统提示，Qwen2-Audio能智能识别并响应音频内容。例如，面对同时包含多种声音、多人对话及语音指令的复杂音频，Qwen2-Audio能精准理解指令并给出相应解读。此外，通过DPO的优化，模型在保持事实准确性和行为一致性方面表现更佳。根据AIR-Bench的评测，Qwen2-Audio在音频指令遵循能力测试中超越了Gemini-1.5-pro等先前最佳模型。我们开源Qwen2-Audio，旨在推动多模态语言技术的发展。
>
> https://arxiv.org/abs/2407.10759

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/pretrain_hours.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.10759/x9.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.10759](https://arxiv.org/abs/2407.10759)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1