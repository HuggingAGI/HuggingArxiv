# 探究大型视觉-语言模型对属性的理解能力

发布时间：2024年08月25日

`LLM应用` `计算机视觉` `人工智能`

> Evaluating Attribute Comprehension in Large Vision-Language Models

# 摘要

> 大型视觉-语言模型在众多下游任务中已取得显著进展，但在细粒度视觉理解，如对象属性识别上仍显不足。尽管评估工作增多，对属性理解和视觉语言微调的深入研究却显匮乏。本文从属性识别与层次理解两方面，评估了视觉问答、图像-文本匹配等三种交互方式，并探讨了微调中影响属性理解的关键因素。实验揭示：模型虽擅长属性识别，层次理解却有限；ITM在捕捉细节上优于ITC，更适于属性任务；微调中使用的标题属性信息至关重要。期望本研究能为未来大型视觉-语言模型在细粒度视觉理解上的进步提供指引。

> Currently, large vision-language models have gained promising progress on many downstream tasks. However, they still suffer many challenges in fine-grained visual understanding tasks, such as object attribute comprehension. Besides, there have been growing efforts on the evaluations of large vision-language models, but lack of in-depth study of attribute comprehension and the visual language fine-tuning process. In this paper, we propose to evaluate the attribute comprehension ability of large vision-language models from two perspectives: attribute recognition and attribute hierarchy understanding. We evaluate three vision-language interactions, including visual question answering, image-text matching, and image-text cosine similarity. Furthermore, we explore the factors affecting attribute comprehension during fine-tuning. Through a series of quantitative and qualitative experiments, we introduce three main findings: (1) Large vision-language models possess good attribute recognition ability, but their hierarchical understanding ability is relatively limited. (2) Compared to ITC, ITM exhibits superior capability in capturing finer details, making it more suitable for attribute understanding tasks. (3) The attribute information in the captions used for fine-tuning plays a crucial role in attribute understanding. We hope this work can help guide future progress in fine-grained visual understanding of large vision-language models.

[Arxiv](https://arxiv.org/abs/2408.13898)