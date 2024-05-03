# 利用大型语言模型从动作中学习对象状态。

发布时间：2024年05月02日

`LLM应用` `视频分析` `人工智能`

> Learning Object States from Actions via Large Language Models

# 摘要

> 在视频分析中，准确识别对象状态的时间位置对于深入理解人类行为极为关键。然而，由于对象状态的复杂多变，相关训练数据的匮乏一直是研究的瓶颈。传统的详尽标注方法耗时且效率低下，因此，我们探索了一种新颖的方法：从教学视频的旁白中学习。尽管如此，与动作描述相比，对象状态在旁白中的描述较为简略，导致信息捕捉不足。本研究提出了一种创新框架，利用大型语言模型（LLMs）从旁白中的动作描述推断出对象状态信息。我们发现，LLMs能够利用其内置的世界知识，理解动作与随后对象状态之间的联系，并从动作序列中预测对象状态。此外，该框架的灵活性允许它为任意类别生成看似合理的伪对象状态标签。为了验证我们的方法，我们创建了一个新的数据集——多对象状态转换（MOST），它包含了60个对象状态类别的密集时间标注。在该数据集上，我们训练的模型使用生成的伪标签，与现有的强大零样本视觉-语言模型相比，在平均精度（mAP）上实现了超过29%的显著提升，从而证明了我们通过LLMs从动作中提取对象状态信息方法的有效性。

> Temporally localizing the presence of object states in videos is crucial in understanding human activities beyond actions and objects. This task has suffered from a lack of training data due to object states' inherent ambiguity and variety. To avoid exhaustive annotation, learning from transcribed narrations in instructional videos would be intriguing. However, object states are less described in narrations compared to actions, making them less effective. In this work, we propose to extract the object state information from action information included in narrations, using large language models (LLMs). Our observation is that LLMs include world knowledge on the relationship between actions and their resulting object states, and can infer the presence of object states from past action sequences. The proposed LLM-based framework offers flexibility to generate plausible pseudo-object state labels against arbitrary categories. We evaluate our method with our newly collected Multiple Object States Transition (MOST) dataset including dense temporal annotation of 60 object state categories. Our model trained by the generated pseudo-labels demonstrates significant improvement of over 29% in mAP against strong zero-shot vision-language models, showing the effectiveness of explicitly extracting object state information from actions through LLMs.

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x1.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x2.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x3.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x4.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x5.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x6.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x7.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x8.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x9.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x10.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x11.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x12.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x13.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x14.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x15.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x16.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x17.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x18.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x19.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x20.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x21.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x22.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x23.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x24.png)

![利用大型语言模型从动作中学习对象状态。](../../../paper_images/2405.01090/x25.png)

[Arxiv](https://arxiv.org/abs/2405.01090)