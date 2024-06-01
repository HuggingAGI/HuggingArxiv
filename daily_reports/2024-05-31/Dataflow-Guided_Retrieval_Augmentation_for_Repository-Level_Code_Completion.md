# 基于数据流的检索增强技术，助力仓库级代码补全
发布时间：2024年05月30日

`RAG`
> Dataflow-Guided Retrieval Augmentation for Repository-Level Code Completion
>
> 近年来，代码语言模型（LMs）在代码补全等智能任务中大放异彩。但预训练模型在私有代码库中生成正确补全仍是一大挑战。以往研究依赖导入关系或文本相似性检索跨文件上下文，但与补全目标的相关性不足。为此，我们提出了DraCo，一种数据流引导的检索增强方法，专为代码库级别的代码补全设计。DraCo通过扩展的数据流分析，将私有代码库转化为代码实体及其关系网络，构建出特定于代码库的上下文图。在代码补全触发时，DraCo能精准提取此图中的相关背景知识，生成优质提示以供代码LMs查询。我们还创建了Python数据集ReccEval，其补全目标更为多元。实验结果显示，DraCo在提升代码精确匹配和标识符F1分数方面均超越了现有技术，分别提高了3.43%和3.27%。
>
> https://arxiv.org/abs/2405.19782

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19782/x10.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19782](https://arxiv.org/abs/2405.19782)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886