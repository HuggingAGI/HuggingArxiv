# [探究“生成”与“检索”的抉择——人工构建的上下文对医学开放领域问答效果的影响](https://arxiv.org/abs/2403.01924)

> To Generate or to Retrieve? On the Effectiveness of Artificial Contexts for Medical Open-Domain Question Answering

发布时间：2024年03月04日

> 面对医疗领域的开放型问题回答，深度依赖专业知识是个不争的事实。近期研究致力于让知识脱离模型参数束缚，克服架构扩大带来的挑战，并使得在普通低配硬件上也能进行训练。当前，“检索后阅读”模式已成主流，模型依据PubMed、教科书及UMLS等外部资料库中的相关知识点进行预测。随着特定领域大语言模型的兴起，一种尚待深入探索的新路径——通过提示构建虚拟情境——也逐渐显现。于是，“生成还是检索”，这一抉择如同哈姆雷特的经典困境在现代语境下的再现。本文介绍了一款名为MedGENIE的创新框架，它是首个针对医学多选题答题应用的“生成-后阅读”结构。我们立足于不超过24GB VRAM的实际考虑，在MedQA-USMLE、MedMCQA及MMLU三大数据集上开展了大规模实验。结果显示，MedGENIE在各测试平台的开卷环境中均刷新了最先进水平，并且仅用原先1750亿参数基准的至多706分之一，便能使小型阅读器轻松胜过零样本闭卷模型，其关键在于生成的文本片段相较于检索内容在提高准确率上表现出更高的效能。

> Medical open-domain question answering demands substantial access to specialized knowledge. Recent efforts have sought to decouple knowledge from model parameters, counteracting architectural scaling and allowing for training on common low-resource hardware. The retrieve-then-read paradigm has become ubiquitous, with model predictions grounded on relevant knowledge pieces from external repositories such as PubMed, textbooks, and UMLS. An alternative path, still under-explored but made possible by the advent of domain-specific large language models, entails constructing artificial contexts through prompting. As a result, "to generate or to retrieve" is the modern equivalent of Hamlet's dilemma. This paper presents MedGENIE, the first generate-then-read framework for multiple-choice question answering in medicine. We conduct extensive experiments on MedQA-USMLE, MedMCQA, and MMLU, incorporating a practical perspective by assuming a maximum of 24GB VRAM. MedGENIE sets a new state-of-the-art (SOTA) in the open-book setting of each testbed, even allowing a small-scale reader to outcompete zero-shot closed-book 175B baselines while using up to 706$\times$ fewer parameters. Overall, our findings reveal that generated passages are more effective than retrieved counterparts in attaining higher accuracy.

`Agent`