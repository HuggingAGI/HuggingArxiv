# 大型语言模型能否进行简单的算术推理？本文旨在探究这些模型是否能够识别并处理蕴含的数学关系。

发布时间：2024年04月30日

`LLM理论` `人工智能`

> Can Large Language Models put 2 and 2 together? Probing for Entailed Arithmetical Relationships

# 摘要

> 在大型语言模型（LLM）的研究热潮中，我们关注的焦点有两个：LLM掌握了哪些知识，以及它们是否具备推理能力，或者更确切地说，能否进行近似推理。尽管这些研究方向大多独立进展，我们却对它们的交汇点充满好奇：即对隐含知识的推理能力进行探究。鉴于我们对这一领域的表现持保留态度，我们采用了一种简单的比较方法，对比不同主题元素的相关基数（如鸟的腿数与三轮车的轮子数）。我们的实证研究揭示了一个现象：尽管LLM在知识积累和推理能力上随着GPT模型的迭代而稳步提升，但它们的推理能力仅限于统计推断。要应对许多常识推理任务中的组合爆炸问题，尤其是涉及算术概念时，纯粹的统计学习方法显得力不从心。我们进一步指出，规模并非总是优势，单纯追求统计学上的提升是有缺陷的，因为这实际上加剧了正确答案产出与真正推理能力之间的混淆。

> Two major areas of interest in the era of Large Language Models regard questions of what do LLMs know, and if and how they may be able to reason (or rather, approximately reason). Since to date these lines of work progressed largely in parallel (with notable exceptions), we are interested in investigating the intersection: probing for reasoning about the implicitly-held knowledge. Suspecting the performance to be lacking in this area, we use a very simple set-up of comparisons between cardinalities associated with elements of various subjects (e.g. the number of legs a bird has versus the number of wheels on a tricycle). We empirically demonstrate that although LLMs make steady progress in knowledge acquisition and (pseudo)reasoning with each new GPT release, their capabilities are limited to statistical inference only. It is difficult to argue that pure statistical learning can cope with the combinatorial explosion inherent in many commonsense reasoning tasks, especially once arithmetical notions are involved. Further, we argue that bigger is not always better and chasing purely statistical improvements is flawed at the core, since it only exacerbates the dangerous conflation of the production of correct answers with genuine reasoning ability.

[Arxiv](https://arxiv.org/abs/2404.19432)