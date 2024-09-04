# 在性能与效率之间寻找平衡：一种通过图像与文本交互来优化多模态大型语言模型的剪枝技术

发布时间：2024年09月02日

`LLM应用` `人工智能` `计算机视觉`

> Balancing Performance and Efficiency: A Multimodal Large Language Model Pruning Method based Image Text Interaction

# 摘要

> 多模态大型语言模型 (MM-LLMs) 近期在多模态任务中表现卓越，但其高昂的计算成本限制了其广泛应用。我们发现，在 MM-LLMs 中，处理文本与视觉标记的步骤是计算瓶颈。为此，我们深入研究了视觉标记，并发现视觉与 CLS 标记的相似度呈长尾分布，即仅少数视觉标记高度相似。基于此，我们设计了一种动态剪枝算法：首先，针对不同样本，找到视觉 CLS 标记相似度曲线的拐点，以此为依据修剪视觉标记，从而加速模型；接着，在 LLM 层对视觉文本标记进行二次剪枝，通过筛选与文本相关性低的标记，实现效率与性能的平衡。实验表明，使用平均 22% 的原标记数量时，我们的方法能保持与原始模型相媲美的性能。相关源代码将在接受后公开。

> Recently, multimodal large language models (MM-LLMs) have achieved great success in many multimodal tasks, but their high computational costs limit their further promotion and application. In the MM-LLMs framework, the main computational consumption step is the processing of concatenated text and visual tokens at the LLM layer. The length of the input token for LLM directly affects the overall training and inference efficiency. In response to this issue, we further studied the visual tokens of MM-LLMs. We found that the similarity between visual and CLS tokens in the visual encoder follows a long-tail distribution. In other words, only a few visual tokens are highly similar to CLS tokens. Therefore, we designed a dynamic pruning algorithm to address this issue. Firstly, for different input samples, we search for the inflection point of their visual CLS token similarity curve and use it as the corresponding segmentation point to trim the visual markers. This process mainly reduces the output of the visual encoder to accelerate the model. Then, in the LLM layer, the concatenated visual text tokens are pruned for the second time. During this process, due to the interaction between visual and textual features, visual and textual tokens with low text correlation are further filtered, achieving a balance between efficiency and performance. The results on multiple datasets show that our proposed method can achieve performance that competes with the original performance when using an average of 22% of the original token quantity. Our source code will be made publicly available following acceptance.

[Arxiv](https://arxiv.org/abs/2409.01162)