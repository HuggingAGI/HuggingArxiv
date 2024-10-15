# 仇恨言论分类的诊断：人类与机器的分歧点及原因何在？

发布时间：2024年10月14日

`LLM应用` `社交媒体` `仇恨言论检测`

> Diagnosing Hate Speech Classification: Where Do Humans and Machines Disagree, and Why?

# 摘要

> 本研究通过余弦相似度比率、嵌入回归和手动重新标注，深入分析了仇恨言论分类。首先，我们在包含135,556条社交媒体评论的数据集上计算余弦相似度，展示了其作为仇恨言论内容描述的基本应用。接着，我们从人类标注的不一致性入手，使用嵌入回归发现女性标注者对种族诽谤更为敏感。进一步，我们训练了一个基于NV-Embed-v2的仇恨言论分类器，测试准确率达94%。在对比机器与人类标注时，尽管人类标注被视为标准，机器在长篇事实标注上表现更优，但在短句脏话标注上则稍逊一筹。我们推测，这可能是模型对齐的结果：虽然防止了明显仇恨言论的产生，但也削弱了检测此类内容的能力。

> This study uses the cosine similarity ratio, embedding regression, and manual re-annotation to diagnose hate speech classification. We begin by computing cosine similarity ratio on a dataset "Measuring Hate Speech" that contains 135,556 annotated comments on social media. This way, we show a basic use of cosine similarity as a description of hate speech content. We then diagnose hate speech classification starting from understanding the inconsistency of human annotation from the dataset. Using embedding regression as a basic diagnostic, we found that female annotators are more sensitive to racial slurs that target the black population. We perform with a more complicated diagnostic by training a hate speech classifier using a SoTA pre-trained large language model, NV-Embed-v2, to convert texts to embeddings and run a logistic regression. This classifier achieves a testing accuracy of 94%. In diagnosing where machines disagree with human annotators, we found that machines make fewer mistakes than humans despite the fact that human annotations are treated as ground truth in the training set. Machines perform better in correctly labeling long statements of facts, but perform worse in labeling short instances of swear words. We hypothesize that this is due to model alignment - while curating models at their creation prevents the models from producing obvious hate speech, it also reduces the model's ability to detect such content.

[Arxiv](https://arxiv.org/abs/2410.10153)