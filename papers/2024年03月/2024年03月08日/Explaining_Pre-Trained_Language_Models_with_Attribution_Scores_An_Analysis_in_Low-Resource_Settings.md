# [针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](https://arxiv.org/abs/2403.05338)

发布时间：2024年03月08日

`LLM理论`

> Explaining Pre-Trained Language Models with Attribution Scores: An Analysis in Low-Resource Settings

> 归因分数揭示了输入各部分对模型决策的重要性，有助于理解模型行为。随着易于在低资源场景下调整的优势，基于提示的模型正日益流行。然而，这类模型产生的归因分数质量却尚未经过深入探究。本研究针对此问题，对比分析了基于提示模型、微调模型及大型语言模型所得到的归因分数，评价其合理性和忠实度，并创新性地引入训练数据规模作为分析维度。结果显示，在资源有限的情况下，采用提示范式的模型（不论是基于编码器还是解码器）相较于微调模型能提供更为合理的解释；此外，Shapley Value Sampling 方法在生成兼具合理性和忠实性的解释时，表现稳健，明显优于注意力机制和Integrated Gradients方法。

> Attribution scores indicate the importance of different input parts and can, thus, explain model behaviour. Currently, prompt-based models are gaining popularity, i.a., due to their easier adaptability in low-resource settings. However, the quality of attribution scores extracted from prompt-based models has not been investigated yet. In this work, we address this topic by analyzing attribution scores extracted from prompt-based models w.r.t. plausibility and faithfulness and comparing them with attribution scores extracted from fine-tuned models and large language models. In contrast to previous work, we introduce training size as another dimension into the analysis. We find that using the prompting paradigm (with either encoder-based or decoder-based models) yields more plausible explanations than fine-tuning the models in low-resource settings and Shapley Value Sampling consistently outperforms attention and Integrated Gradients in terms of leading to more plausible and faithful explanations.

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/x1.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/x2.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/x3.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/x4.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/x5.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/task_p_tse.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/task_p_esnli.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/plau_tse.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/plau_esnli.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/faith_tse.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/faith_esnli.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/model_plau_tse.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/model_plau_esnli.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/model_faith_tse.png)

![针对低资源场景，本研究通过归因分数深入剖析预训练语言模型的工作原理。](../../../paper_images/2403.05338/model_faith_esnli.png)

[Arxiv](https://arxiv.org/abs/2403.05338)