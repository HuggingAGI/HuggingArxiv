# 深入研究聊天机器人的安全漏洞
`模型安全`
> 最新研究揭示，大型语言模型（LLMs）面临着后门攻击的安全风险。这种后门攻击下，模型在正常情形下运作正常，但一旦遇到特定的触发信号，便会展现出恶意行为。目前的研究多集中于针对指令调整过的LLMs，却忽略了一个实际场景：LLMs在多轮对话数据上经过微调，变身为聊天机器人。鉴于聊天机器人在现实世界的应用广泛，其安全性问题亟需关注。遗憾的是，我们发现，多轮交互的灵活性反而让触发器设计更加多变，增加了聊天机器人面对后门攻击的脆弱性。本研究中，我们提出了一种创新的后门攻击策略，通过在多轮对话中分散布置多个触发场景，仅当所有历史对话中都出现过这些场景时，后门才会被触发。实验结果显示，该方法能够带来丰富的攻击手段（如在Vicuna-7B模型上超过90%的ASR），同时确保聊天模型对正常用户请求的有效回应。值得注意的是，这种后门难以通过下游的重新对齐来消除，这进一步凸显了对聊天模型安全性问题持续研究和关注的必要性。注意：本文可能包含不当内容。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02406/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02406/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02406/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02406/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.02406/x5.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/1522581182125522](https://wx.zsxq.com/dweb2/index/topic_detail/1522581182125522)

[https://arxiv.org/abs/2404.02406](https://arxiv.org/abs/2404.02406)