# 利用大型语言模型为本地项目提供增强检索的代码补全功能
发布时间：2024年08月09日

`代码编写`
> Retrieval-augmented code completion for local projects using large language models
>
> 随着 LLM 在软件开发领域的普及，隐私和计算需求成为商业解决方案中的难题。为此，我们探索了适用于本地执行和增强的 1.6 亿参数 LLM。通过在开源 Python 代码上训练 GPT-2 和 RETRO 模型，我们验证了基于向量嵌入检索的优势。进一步地，我们采用 In-context 检索增强生成技术，根据令牌的 Jaccard 相似性检索代码片段，提升了模型性能。实验表明，尽管方法简单，但在处理更大模型时，这种方法比 RETRO 架构更为有效。我们强调，在代码完成任务中，适当的令牌化是释放 LLM 潜力的关键。
>
> https://arxiv.org/abs/2408.05026

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.05026](https://arxiv.org/abs/2408.05026)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)