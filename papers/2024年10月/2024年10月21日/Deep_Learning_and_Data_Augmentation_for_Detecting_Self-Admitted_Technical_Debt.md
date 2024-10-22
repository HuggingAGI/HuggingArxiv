# 利用深度学习与数据增强技术，精准检测自我承认的技术债务

发布时间：2024年10月21日

`其他` `软件开发` `数据分析`

> Deep Learning and Data Augmentation for Detecting Self-Admitted Technical Debt

# 摘要

> 自我承认的技术债务（SATD）是开发者通过文本解释现有实现非最优的情况。过去研究主要集中在识别或分类SATD，但效果不佳，尤其是测试和需求债务，因数据极度不平衡。我们结合BiLSTM和BERT架构，并采用数据增强策略，提出两步法识别和分类SATD。我们的贡献包括提供平衡数据集，并显著提升SATD识别和分类效果。

> Self-Admitted Technical Debt (SATD) refers to circumstances where developers use textual artifacts to explain why the existing implementation is not optimal. Past research in detecting SATD has focused on either identifying SATD (classifying SATD items as SATD or not) or categorizing SATD (labeling instances as SATD that pertain to requirement, design, code, test debt, etc.). However, the performance of these approaches remains suboptimal, particularly for specific types of SATD, such as test and requirement debt, primarily due to extremely imbalanced datasets. To address these challenges, we build on earlier research by utilizing BiLSTM architecture for the binary identification of SATD and BERT architecture for categorizing different types of SATD. Despite their effectiveness, both architectures struggle with imbalanced data. Therefore, we employ a large language model data augmentation strategy to mitigate this issue. Furthermore, we introduce a two-step approach to identify and categorize SATD across various datasets derived from different artifacts. Our contributions include providing a balanced dataset for future SATD researchers and demonstrating that our approach significantly improves SATD identification and categorization performance compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2410.15804)