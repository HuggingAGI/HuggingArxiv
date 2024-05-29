# Conv-CoA：借助对话链式行动优化大型语言模型中的开放领域问答性能
发布时间：2024年05月28日

`RAG`
> Conv-CoA: Improving Open-domain Question Answering in Large Language Models via Conversational Chain-of-Action
>
> 我们开发了一种名为对话行动链（Conv-CoA）的新框架，专为开放域对话问答（OCQA）设计。该框架针对三大挑战进行了优化：(i) 避免与实时或领域事实不符的幻觉现象，(ii) 提升对话场景中的推理能力，(iii) 改善对话信息检索的性能。我们的核心创新在于一种动态的推理-检索机制，它能够识别问题意图，并将其分解成一系列推理步骤，通过精心设计的提示、预设行动、更新上下文知识集（CKS）以及基于Hopfield的新型检索器来逐步解答。在方法论上，我们引入了高效的Hopfield检索器，以提高对话信息检索的效率和准确性。同时，我们还设计了一个对话多参考忠诚度分数（Conv-MRFS），用于验证并解决对话中知识与答案之间的冲突。通过与23种顶尖方法在五个研究方向和两个公共基准上的比较，我们的Conv-CoA在准确性和效率方面均显示出优越性。
>
> https://arxiv.org/abs/2405.17822

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17822/framework.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.17822](https://arxiv.org/abs/2405.17822)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886