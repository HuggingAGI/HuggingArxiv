# [本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](https://arxiv.org/abs/2403.05262)

发布时间：2024年03月08日

`LLM应用`

> Debiasing Large Visual Language Models

> 现今，在CV和NLP天地里，LVLMs已经成为了基于视觉输入生成文本说明的必备利器。然而，研究发现，即便此类模型进步显著，其生成的内容却常受到底层LLMs固有知识而非实际输入图像的主导，这一显著偏见不容忽视。即使缺乏匹配图像或面对矛盾视觉输入，LVLMs仍可能自信满满地给出答案。为了修正这类偏见，让模型重拾对视觉信息的关注，我们创新提出两种无需额外训练的简易策略。针对分类、多选问答等任务，我们倡导运用仿射变换进行“后校准”，调整输出概率分布，实现无图情况下各选项得分均衡，犹如一种有力的正则化手段，削弱LLMs先验知识的影响。至于更为复杂的开放型生成任务，则借鉴对比解码思路，推广至“去偏采样”方法。同时，我们深入探究了LVLMs在各类解码配置下的不稳定表现，并通过系统性调整优化，实现了性能的大幅提升，甚至超越既有成果，引发了对当前评估公正性的反思。大量严谨实验有力证明了上述策略在减轻模型偏见上的实效性，这些策略不仅能有效减少臆想成分，更能助力生成更具参考价值和精准度的图文解说。

> In the realms of computer vision and natural language processing, Large Vision-Language Models (LVLMs) have become indispensable tools, proficient in generating textual descriptions based on visual inputs. Despite their advancements, our investigation reveals a noteworthy bias in the generated content, where the output is primarily influenced by the underlying Large Language Models (LLMs) prior rather than the input image. Our empirical experiments underscore the persistence of this bias, as LVLMs often provide confident answers even in the absence of relevant images or given incongruent visual input. To rectify these biases and redirect the model's focus toward vision information, we introduce two simple, training-free strategies. Firstly, for tasks such as classification or multi-choice question-answering (QA), we propose a ``calibration'' step through affine transformation to adjust the output distribution. This ``Post-Hoc debias'' approach ensures uniform scores for each answer when the image is absent, serving as an effective regularization technique to alleviate the influence of LLM priors. For more intricate open-ended generation tasks, we extend this method to ``Debias sampling'', drawing inspirations from contrastive decoding methods. Furthermore, our investigation sheds light on the instability of LVLMs across various decoding configurations. Through systematic exploration of different settings, we significantly enhance performance, surpassing reported results and raising concerns about the fairness of existing evaluations. Comprehensive experiments substantiate the effectiveness of our proposed strategies in mitigating biases. These strategies not only prove beneficial in minimizing hallucinations but also contribute to the generation of more helpful and precise illustrations.

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x1.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x2.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x3.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x4.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x5.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x6.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x7.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x8.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x9.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x11.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x12.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x13.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x14.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x15.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x16.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x17.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x18.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x19.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x20.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x21.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x22.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x23.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x24.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x25.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x26.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x27.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x28.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x29.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x30.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x31.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x32.png)

![本研究致力于探讨如何有效去偏大型视觉语言模型，以提升其准确性和公正性。](../../../paper_images/2403.05262/x33.png)