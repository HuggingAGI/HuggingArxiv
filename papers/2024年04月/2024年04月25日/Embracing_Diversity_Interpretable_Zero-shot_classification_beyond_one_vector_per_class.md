# 拥抱多样性：探索多向量下的可解释零样本分类

发布时间：2024年04月25日

`分类：LLM应用` `计算机视觉` `人工智能`

> Embracing Diversity: Interpretable Zero-shot classification beyond one vector per class

# 摘要

> 视觉-语言模型（VLM）实现了无需重新训练即可对开放世界中的对象进行分类，这一零样本学习模式无疑是一大进步。然而，即便是最先进的模型，在面对与典型图像差异较大的对象时，也会出现性能偏差。以梨为例，它们可能被切成块或保持完整，放置在桌面或碗中，但标准的VLM分类器却将同一类别的所有实例简化为基于类别标签的单一向量。我们提出，为了捕捉类别内部的丰富多样性，零样本分类不应局限于单一向量。我们开发了一种新方法，通过推断属性来编码和体现类别内的多样性，且无需重新训练。我们的研究显示，这种方法在多个数据集上的表现均优于传统零样本分类，无论是在处理层次结构、多样化对象状态、现实世界的地理多样性，还是细粒度数据集上，其中类别内多样性不那么显著。值得注意的是，我们的方法具有天然的可解释性，为每次推断提供准确的解释，有助于模型的调试和透明度提升。此外，我们的方法能够高效地扩展到大量属性，以更准确地预测非典型实例。我们还确定了整体准确性与最差类别准确性之间的权衡原则，并通过我们方法的超参数进行调整。我们期望本研究能推动零样本分类领域的发展，超越单一类别向量，以更好地捕捉世界的多样性，并构建不牺牲性能的透明AI系统。

> Vision-language models enable open-world classification of objects without the need for any retraining. While this zero-shot paradigm marks a significant advance, even today's best models exhibit skewed performance when objects are dissimilar from their typical depiction. Real world objects such as pears appear in a variety of forms -- from diced to whole, on a table or in a bowl -- yet standard VLM classifiers map all instances of a class to a \it{single vector based on the class label}. We argue that to represent this rich diversity within a class, zero-shot classification should move beyond a single vector. We propose a method to encode and account for diversity within a class using inferred attributes, still in the zero-shot setting without retraining. We find our method consistently outperforms standard zero-shot classification over a large suite of datasets encompassing hierarchies, diverse object states, and real-world geographic diversity, as well finer-grained datasets where intra-class diversity may be less prevalent. Importantly, our method is inherently interpretable, offering faithful explanations for each inference to facilitate model debugging and enhance transparency. We also find our method scales efficiently to a large number of attributes to account for diversity -- leading to more accurate predictions for atypical instances. Finally, we characterize a principled trade-off between overall and worst class accuracy, which can be tuned via a hyperparameter of our method. We hope this work spurs further research into the promise of zero-shot classification beyond a single class vector for capturing diversity in the world, and building transparent AI systems without compromising performance.

[Arxiv](https://arxiv.org/abs/2404.16717)