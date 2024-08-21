# 化废为宝：利用 Token 回收技术加速大型语言模型的推理过程
发布时间：2024年08月16日


> Turning Trash into Treasure: Accelerating Inference of Large Language Models with Token Recycling
>
> 随着大型语言模型（LLM）参数的激增，推理延迟已成为其广泛应用的瓶颈。为此，我们引入了推测解码技术，通过猜测与验证的并行处理，无损地加速推理过程。该技术或依赖于小型模型等额外结构进行初步令牌猜测，需预先训练；或采用基于检索的无训练方法，从现有语料库中构建库，但面临存储量大、检索耗时及适应性有限的问题。我们观察到解码过程中生成的候选令牌常在后续序列中重现，因此提出了创新的“令牌回收”方法。该方法将候选令牌存储于邻接矩阵，并运用类似广度优先搜索的算法构建草稿树，再通过树注意力机制进行验证，随后用新令牌更新矩阵。仅需不到2MB的额外存储，便能在各类LLM上实现近两倍的加速，性能远超现有无训练方法30%，甚至优于某些训练方法25%。此技术可无缝应用于任何LLM及任务，无需额外适应。
>
> https://arxiv.org/abs/2408.08696

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08696/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08696/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08696/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08696/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08696/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.08696](https://arxiv.org/abs/2408.08696)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)