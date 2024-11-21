# 编辑后模型性能下降的原因及解决办法

发布时间：2024年10月31日

`LLM应用` `知识编辑`

> Reasons and Solutions for the Decline in Model Performance after Editing

# 摘要

> 知识编辑技术因能低成本更新大规模语言模型中的错误或过时知识而备受关注。然而，近期研究发现，编辑后的模型常常出现不同程度的性能下滑。这一现象的背后原因及潜在解决方案尚未明确。为探究编辑模型性能下降的缘由并优化编辑手段，此项工作从数据和模型两方面探寻了潜在因素。具体来说，1）从数据层面，为明晰数据对编辑模型性能的影响，本文率先构建了一个多问题数据集（MQD），用于评估不同类型的编辑数据对模型性能的作用。实验表明，编辑模型的性能主要受编辑目标的多样性和序列长度影响。2）从模型角度，本文探究了影响编辑模型性能的要素。结果显示，编辑模型层的 L1 范数与编辑准确性存在紧密关联，并明确这是造成编辑性能瓶颈的重要因素。最后，为提升编辑模型的性能，本文进一步提出了一种序列转储（D4S）方法，通过降低编辑层的 L1 范数，成功突破了此前的编辑瓶颈，允许用户进行多次有效编辑，且将模型损伤降到最低。我们的代码可在 https://github.com/nlpkeg/D4S 上获取。

> Knowledge editing technology has received widespread attention for low-cost updates of incorrect or outdated knowledge in large-scale language models. However, recent research has found that edited models often exhibit varying degrees of performance degradation. The reasons behind this phenomenon and potential solutions have not yet been provided. In order to investigate the reasons for the performance decline of the edited model and optimize the editing method, this work explores the underlying reasons from both data and model perspectives. Specifically, 1) from a data perspective, to clarify the impact of data on the performance of editing models, this paper first constructs a Multi-Question Dataset (MQD) to evaluate the impact of different types of editing data on model performance. The performance of the editing model is mainly affected by the diversity of editing targets and sequence length, as determined through experiments. 2) From a model perspective, this article explores the factors that affect the performance of editing models. The results indicate a strong correlation between the L1-norm of the editing model layer and the editing accuracy, and clarify that this is an important factor leading to the bottleneck of editing performance. Finally, in order to improve the performance of the editing model, this paper further proposes a Dump for Sequence (D4S) method, which successfully overcomes the previous editing bottleneck by reducing the L1-norm of the editing layer, allowing users to perform multiple effective edits and minimizing model damage. Our code is available at https://github.com/nlpkeg/D4S.

[Arxiv](https://arxiv.org/abs/2410.23843)