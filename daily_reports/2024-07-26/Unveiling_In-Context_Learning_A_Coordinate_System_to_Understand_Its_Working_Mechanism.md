# 揭秘 In-Context Learning：构建坐标系统，深入探究其运作原理
发布时间：2024年07月24日

`提示工程`
> Unveiling In-Context Learning: A Coordinate System to Understand Its Working Mechanism
>
> 大型语言模型 (LLM) 的 in-context learning (ICL) 能力引人注目，但其工作原理尚不清晰。研究界对 ICL 存在两种对立看法：一方认为 LLM 能自动识别任务，标签和示例数量无关紧要；另一方则强调演示中相似示例的关键作用，主张标签准确和示例丰富。我们构建了一个二维坐标框架，整合这两种观点，通过两个关键变量解析 ICL 行为：任务识别能力和演示中的相似示例。我们引入峰值逆序排名指标评估 LLM 的任务识别力，并探究其对相似性定义的响应。实验覆盖多个分类任务，深入揭示 ICL 在各象限的运作机制。此外，我们的坐标系统同样适用于生成任务，有效解读 ICL 在生成领域的应用。
>
> https://arxiv.org/abs/2407.17011

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x18.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x19.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x20.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x21.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x22.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.17011/x23.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.17011](https://arxiv.org/abs/2407.17011)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1