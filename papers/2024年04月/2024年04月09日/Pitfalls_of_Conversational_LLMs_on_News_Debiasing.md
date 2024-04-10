# 对话型大型语言模型在新闻去偏见方面的潜在问题

发布时间：2024年04月09日

`RAG` `新闻编辑` `去偏见处理`

> Pitfalls of Conversational LLMs on News Debiasing

# 摘要

> 本文聚焦于新闻编辑的去偏见处理，并探讨了对话式大型语言模型在此领域的效能。我们根据新闻编辑的专业视角，量身打造了一套评估标准，从三个热门对话模型中提取文本样本，并基于这一标准进行评估。研究还考察了这些模型在审核去偏见输出质量方面的功能。研究结果显示，各类大型语言模型在去偏见方面均有不足，特别是ChatGPT等模型有时会产生偏离原意的不必要修改，甚至可能引发误导。此外，相较于专业领域的专家，这些模型在评判去偏见成果的质量上表现尚欠火候。

> This paper addresses debiasing in news editing and evaluates the effectiveness of conversational Large Language Models in this task. We designed an evaluation checklist tailored to news editors' perspectives, obtained generated texts from three popular conversational models using a subset of a publicly available dataset in media bias, and evaluated the texts according to the designed checklist. Furthermore, we examined the models as evaluator for checking the quality of debiased model outputs. Our findings indicate that none of the LLMs are perfect in debiasing. Notably, some models, including ChatGPT, introduced unnecessary changes that may impact the author's style and create misinformation. Lastly, we show that the models do not perform as proficiently as domain experts in evaluating the quality of debiased outputs.

[Arxiv](https://arxiv.org/abs/2404.06488)