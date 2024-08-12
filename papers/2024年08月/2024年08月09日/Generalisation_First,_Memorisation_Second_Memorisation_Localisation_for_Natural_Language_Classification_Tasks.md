# 自然语言分类任务中，是否应先泛化再记忆？本研究探讨记忆定位策略。

发布时间：2024年08月09日

`LLM理论` `人工智能`

> Generalisation First, Memorisation Second? Memorisation Localisation for Natural Language Classification Tasks

# 摘要

> 记忆是神经模型学习真实数据的一部分，它们会捕捉并存储非典型的输入-输出组合。尽管这一现象广为人知，但记忆的具体机制和位置仍是个谜。在多层神经网络中，记忆究竟藏身何处？相关研究对此看法不一：有观点认为，图像分类中较低层负责学习通用特征，而深层则专注于记忆。然而，NLP领域的研究表明，语言模型并非如此，主要关注事实记忆。我们拓宽了研究视野，涵盖了12项自然语言分类任务，并采用了4种定位技术。结果显示，记忆是一个渐进而非局部的过程，且具有任务依赖性，同时对“先泛化后记忆”的假设提出了更细致的解读。

> Memorisation is a natural part of learning from real-world data: neural models pick up on atypical input-output combinations and store those training examples in their parameter space. That this happens is well-known, but how and where are questions that remain largely unanswered. Given a multi-layered neural model, where does memorisation occur in the millions of parameters? Related work reports conflicting findings: a dominant hypothesis based on image classification is that lower layers learn generalisable features and that deeper layers specialise and memorise. Work from NLP suggests this does not apply to language models, but has been mainly focused on memorisation of facts. We expand the scope of the localisation question to 12 natural language classification tasks and apply 4 memorisation localisation techniques. Our results indicate that memorisation is a gradual process rather than a localised one, establish that memorisation is task-dependent, and give nuance to the generalisation first, memorisation second hypothesis.

[Arxiv](https://arxiv.org/abs/2408.04965)