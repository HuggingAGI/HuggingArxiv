# [本研究采用语义导向的对抗性手段，精准揭示了关系抽取模型存在的不足之处。](https://arxiv.org/abs/2402.19076)

发布时间：2024年02月29日

`LLM理论`

> Pointing out the Shortcomings of Relation Extraction Models with Semantically Motivated Adversarials

> 近年来，大型语言模型已在各NLP任务中登峰造极，但研究揭示它们易于依赖捷径特征，从而导致对OOD样本泛化能力不足且预测有误。以关系抽取为例，理想的模型应能无视参与关系的具体实体，稳定识别出相同的关系类型，譬如在"Leonardo da Vinci painted the Mona Lisa"与将"Leonardo da Vinci"替换成"Barack Obama"的句子中，都应识别出created关系。为此，本研究提出了一系列基于语义的对抗样例生成策略，通过替换实体名称考察当前最先进RE模型的表现力。分析结果显示，这些模型在调整后的数据集上性能大幅下滑（F1值平均降低48.5%），这揭示了它们过于倚重实体的表面形态或相关模式这一捷径，而未能充分利用句子所蕴含的全部信息。

> In recent years, large language models have achieved state-of-the-art performance across various NLP tasks. However, investigations have shown that these models tend to rely on shortcut features, leading to inaccurate predictions and causing the models to be unreliable at generalization to out-of-distribution (OOD) samples. For instance, in the context of relation extraction (RE), we would expect a model to identify the same relation independently of the entities involved in it. For example, consider the sentence "Leonardo da Vinci painted the Mona Lisa" expressing the created(Leonardo_da_Vinci, Mona_Lisa) relation. If we substiute "Leonardo da Vinci" with "Barack Obama", then the sentence still expresses the created relation. A robust model is supposed to detect the same relation in both cases. In this work, we describe several semantically-motivated strategies to generate adversarial examples by replacing entity mentions and investigate how state-of-the-art RE models perform under pressure. Our analyses show that the performance of these models significantly deteriorates on the modified datasets (avg. of -48.5% in F1), which indicates that these models rely to a great extent on shortcuts, such as surface forms (or patterns therein) of entities, without making full use of the information present in the sentences.