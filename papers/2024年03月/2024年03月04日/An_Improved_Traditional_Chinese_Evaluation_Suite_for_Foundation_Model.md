# 为了更好地评测基础模型在处理汉字任务时的性能，我们推出了一个优化的传统中文评估套件。这个改进版套件旨在深入考察和精确衡量各类基础模型在处理汉字文本及理解传统中国文化情境中的表现。

发布时间：2024年03月04日

`LLM应用`

> An Improved Traditional Chinese Evaluation Suite for Foundation Model

# 摘要

> 我们推出了面向繁体中文的大规模多任务理解的全面数据集 TMMLU+，涵盖从基础到专业级别的66个主题的多选题问答内容，相比前代 TMMLU，TMMLU+ 在规模上扩容了六倍，并优化了主题分配的均衡性。我们在此数据集中纳入了闭源模型与参数量从1.8B至72B的24款开源中文大型语言模型的性能基准。研究揭示，繁体中文模型目前在性能上仍不及简体中文模型，并且现有的大型语言模型在总体得分上仍未超越人类水平。现我们已将此数据集及配套基准测试源代码公开发布。

> We present TMMLU+, a comprehensive dataset designed for the Traditional Chinese massive multitask language understanding dataset. TMMLU+ is a multiple-choice question-answering dataset with 66 subjects from elementary to professional level. Compared to its predecessor, TMMLU, TMMLU+ is six times larger and boasts a more balanced subject distribution. We included benchmark results in TMMLU+ from closed-source models and 24 open-weight Chinese large language models of parameters ranging from 1.8B to 72B. Our findings reveal that Traditional Chinese models still trail behind their Simplified Chinese counterparts. Additionally, current large language models have yet to outperform human performance in average scores. We publicly release our dataset and the corresponding benchmark source code.

[Arxiv](https://arxiv.org/abs/2403.01858)