# 强化假新闻检测：借助 SVM 与精细的文本向量化技术。叫板 BERT？

发布时间：2024年11月19日

`LLM应用`

> Strengthening Fake News Detection: Leveraging SVM and Sophisticated Text Vectorization Techniques. Defying BERT?

# 摘要

> 错误信息，尤其是通过在线平台的快速传播，凸显出对可靠检测系统的急切需求。本研究探索运用机器学习和自然语言处理技术，特别是支持向量机（SVM）和 BERT，来检测假新闻。我们为 SVM 运用了三种不同的文本向量化方法：词频 - 逆文档频率（TF-IDF）、Word2Vec 和词袋模型（BoW），评估它们在辨别真假新闻时的有效性。另外，我们将这些方法与变形器大型语言模型 BERT 做了对比。我们的综合手段涵盖了详尽的预处理步骤、严格的模型实施和全面的评估，以确定最有效的技术。结果显示，尽管 BERT 准确率高达 99.98%，F1 分数为 0.9998，但采用线性核和 BoW 向量化的 SVM 模型同样表现优异，准确率达 99.81%，F1 分数为 0.9980。这些发现表明，尽管 BERT 性能卓越，但采用 BoW 和 TF-IDF 向量化方法的 SVM 模型也极为接近，在具备较低计算需求优势的同时，提供了极具竞争力的性能。

> The rapid spread of misinformation, particularly through online platforms, underscores the urgent need for reliable detection systems. This study explores the utilization of machine learning and natural language processing, specifically Support Vector Machines (SVM) and BERT, to detect news that are fake. We employ three distinct text vectorization methods for SVM: Term Frequency Inverse Document Frequency (TF-IDF), Word2Vec, and Bag of Words (BoW) evaluating their effectiveness in distinguishing between genuine and fake news. Additionally, we compare these methods against the transformer large language model, BERT. Our comprehensive approach includes detailed preprocessing steps, rigorous model implementation, and thorough evaluation to determine the most effective techniques. The results demonstrate that while BERT achieves superior accuracy with 99.98% and an F1-score of 0.9998, the SVM model with a linear kernel and BoW vectorization also performs exceptionally well, achieving 99.81% accuracy and an F1-score of 0.9980. These findings highlight that, despite BERT's superior performance, SVM models with BoW and TF-IDF vectorization methods come remarkably close, offering highly competitive performance with the advantage of lower computational requirements.

[Arxiv](https://arxiv.org/abs/2411.12703)