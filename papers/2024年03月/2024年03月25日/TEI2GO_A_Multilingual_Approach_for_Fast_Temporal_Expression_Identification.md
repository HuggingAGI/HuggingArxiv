# TEI2GO 是一个针对多语种环境设计的快速时间表达识别方案。

发布时间：2024年03月25日

`Agent` `时间表达识别`

> TEI2GO: A Multilingual Approach for Fast Temporal Expression Identification

# 摘要

> 要深入理解自然语言文本，识别时间表达至关重要。虽然已有如 HeidelTime 等高效工具，但其运行效率制约了其在大规模应用场景中的普及。本文推出的 TEI2GO 模型，在保持与 HeidelTime 同等识别效果的基础上，大幅提升了运行速度，且已支持六种语言，并在其中四种语言上取得当前最优成果。为了训练 TEI2GO 模型，我们采用人工标注的参考语料库，并创新性地构建了一个庞大的弱标注新闻文本语料库——“HeidelTime 教授”。该语料库拥有涵盖六种语言的共计 138,069 篇文档和 1,050,921 个时间表达，是迄今为止最大的公开可用时间表达识别数据集。通过揭示模型构建的过程，我们期望激发研究社群持续探究、优化和拓展这套模型至更多语言和领域。目前，相关代码、标注信息及模型已公开发布，并可在 HuggingFace 平台上方便获取，便于无缝整合与应用实践。

> Temporal expression identification is crucial for understanding texts written in natural language. Although highly effective systems such as HeidelTime exist, their limited runtime performance hampers adoption in large-scale applications and production environments. In this paper, we introduce the TEI2GO models, matching HeidelTime's effectiveness but with significantly improved runtime, supporting six languages, and achieving state-of-the-art results in four of them. To train the TEI2GO models, we used a combination of manually annotated reference corpus and developed ``Professor HeidelTime'', a comprehensive weakly labeled corpus of news texts annotated with HeidelTime. This corpus comprises a total of $138,069$ documents (over six languages) with $1,050,921$ temporal expressions, the largest open-source annotated dataset for temporal expression identification to date. By describing how the models were produced, we aim to encourage the research community to further explore, refine, and extend the set of models to additional languages and domains. Code, annotations, and models are openly available for community exploration and use. The models are conveniently on HuggingFace for seamless integration and application.

[Arxiv](https://arxiv.org/abs/2403.16804)