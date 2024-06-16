# GraphCoder：借助代码上下文图检索与语言模型，提升仓库级代码补全能力
发布时间：2024年06月11日

`代码编写`
> GraphCoder: Enhancing Repository-Level Code Completion via Code Context Graph-based Retrieval and Language Model
>
> 仓库级别的代码补全依赖于有效结合通用与特定仓库知识。尽管代码LLMs在通用补全任务中表现卓越，但在涉及特定仓库知识时却常显不足。为此，我们开发了GraphCoder，一种结合LLMs通用代码知识与仓库特定知识的检索增强框架。通过代码上下文图（CCG），GraphCoder以更结构化的方式精准捕捉代码补全的上下文，并采用由粗到细的检索策略，从仓库中精确定位相关代码片段。实验表明，GraphCoder不仅提高了精确匹配率，代码与标识符匹配分别提升了+6.06和+6.23，且在时间和空间效率上也有显著优势。
>
> https://arxiv.org/abs/2406.07003

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07003/x10.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.07003](https://arxiv.org/abs/2406.07003)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2