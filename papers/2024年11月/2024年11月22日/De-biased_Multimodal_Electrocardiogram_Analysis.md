# 无偏的多模态心电图分析

发布时间：2024年11月22日

`LLM应用` `医学成像`

> De-biased Multimodal Electrocardiogram Analysis

# 摘要

> 多模态大型语言模型（MLLMs）在医疗领域，尤其是医学成像方面的应用愈发广泛。然而，针对临床中至关重要的心电图（ECG）信号开发 MLLMs 却是医学成像之外的重大难题。此前的研究尝试借助外部分类器，以无训练的方式将心电图转化为若干文本标签来应对此问题。但这种方式大幅压缩了心电图的信息，也未充分发挥 LLM 的推理能力。在本研究中，我们通过投影层把心电图的嵌入直接输入到 LLM 里，保留了更多心电图的信息，更好地利用了 LLM 的推理能力。我们的方法还能有效处理临床中常见的需对比不同时间采集的两份心电图的情况。近来研究发现，MLLMs 可能仅依赖文本输入给出答案，而忽视其他模态的输入。我们从因果角度在心电图 MLLMs 的情境中分析了这一现象，发现混杂因素——疾病严重程度，在问题和答案间引入了虚假关联，致使模型依赖此虚假关联而忽略心电图输入。这类模型不理解心电图输入，在训练集和测试集使用相同问题的不同表述的对抗性测试中表现欠佳。我们依据后门调整理论设计了一种去偏的预训练方法以消除混杂因素的影响。我们的模型在对抗性测试中的心电图问答（ECG-QA）任务中表现出色，并展现出零样本能力。一项有趣的随机心电图测试进一步证实我们的模型能有效理解和利用输入的心电图信号。

> Multimodal large language models (MLLMs) are increasingly being applied in the medical field, particularly in medical imaging. However, developing MLLMs for ECG signals, which are crucial in clinical settings, has been a significant challenge beyond medical imaging. Previous studies have attempted to address this by converting ECGs into several text tags using an external classifier in a training-free manner. However, this approach significantly compresses the information in ECGs and underutilizes the reasoning capabilities of LLMs. In this work, we directly feed the embeddings of ECGs into the LLM through a projection layer, retaining more information about ECGs and better leveraging the reasoning abilities of LLMs. Our method can also effectively handle a common situation in clinical practice where it is necessary to compare two ECGs taken at different times. Recent studies found that MLLMs may rely solely on text input to provide answers, ignoring inputs from other modalities. We analyzed this phenomenon from a causal perspective in the context of ECG MLLMs and discovered that the confounder, severity of illness, introduces a spurious correlation between the question and answer, leading the model to rely on this spurious correlation and ignore the ECG input. Such models do not comprehend the ECG input and perform poorly in adversarial tests where different expressions of the same question are used in the training and testing sets. We designed a de-biased pre-training method to eliminate the confounder's effect according to the theory of backdoor adjustment. Our model performed well on the ECG-QA task under adversarial testing and demonstrated zero-shot capabilities. An interesting random ECG test further validated that our model effectively understands and utilizes the input ECG signal.

[Arxiv](https://arxiv.org/abs/2411.14795)