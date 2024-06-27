# LangChain 中毒：利用 LangChain 解锁 LLMs 的限制
发布时间：2024年06月26日

`模型安全`
> Poisoned LangChain: Jailbreak LLMs by LangChain
>
> 随着NLP技术的进步，大型语言模型（LLMs）正日益融入我们的日常生活，同时也引发了对其安全性的广泛关注。这些模型的安全性问题日益凸显，尤其是针对它们的攻击和防御技术正在不断进化。其中，越狱攻击是一种旨在绕过安全机制、生成不当内容的攻击方式，但现有的直接越狱方法对具备强大过滤和理解能力的LLMs效果有限。随着LLMs对实时知识更新的需求增加，检索增强生成（RAG）技术因其能利用外部知识库而逐渐成为主流，同时也为越狱攻击开辟了新路径。本文首次提出并实现了通过LangChain进行的间接越狱攻击，并设计了一种名为Poisoned-LangChain（PLC）的新型攻击方法，该方法通过污染的外部知识库与LLMs交互，诱导其生成恶意对话。我们在六个大型语言模型上进行了测试，结果显示PLC在三种不同场景下的间接越狱攻击成功率分别达到了88.56%、79.04%和82.69%。
>
> https://arxiv.org/abs/2406.18122

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.18122/fig_top.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.18122/fig_contrast.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.18122](https://arxiv.org/abs/2406.18122)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2