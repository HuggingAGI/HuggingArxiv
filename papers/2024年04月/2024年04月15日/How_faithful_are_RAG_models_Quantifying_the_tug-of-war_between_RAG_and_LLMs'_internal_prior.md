# RAG模型的准确性有多高？探究RAG与大型语言模型内在先验之间的相互制衡。

发布时间：2024年04月15日

`RAG` `信息检索` `问答系统`

> How faithful are RAG models? Quantifying the tug-of-war between RAG and LLMs' internal prior

# 摘要

> 检索增强生成技术（RAG）旨在修复大型语言模型（LLMs）的误解并更新其知识库。但问题是，当LLM本身给出错误答案时，正确的检索内容总能纠正这一错误吗？反过来，如果检索到的信息本身有误，LLM能够识别并忽略，还是会继续传播这一错误呢？为了探究这些问题，我们对LLM内部的先验知识与检索所得信息之间的冲突进行了系统性分析。通过在有无参考文档的数据集上对GPT-4及其他LLMs的问答能力进行测试，我们发现提供准确的检索信息能够解决大部分模型错误，准确率达到94%。但是，当参考文档被错误信息干扰时，如果LLM的先验知识较弱，它更容易重复这些错误的信息；而当先验知识较强时，LLM则更能坚持正确答案。此外，我们还发现，信息与LLM的先验知识偏差越大，模型越不可能采纳这些信息。这一发现揭示了模型的固有知识和参考文档所提供信息之间的微妙平衡。

> Retrieval augmented generation (RAG) is often used to fix hallucinations and provide up-to-date knowledge for large language models (LLMs). However, in cases when the LLM alone incorrectly answers a question, does providing the correct retrieved content always fix the error? Conversely, in cases where the retrieved content is incorrect, does the LLM know to ignore the wrong information, or does it recapitulate the error? To answer these questions, we systematically analyze the tug-of-war between a LLM's internal knowledge (i.e. its prior) and the retrieved information in settings when they disagree. We test GPT-4 and other LLMs on question-answering abilities across datasets with and without reference documents. As expected, providing the correct retrieved information fixes most model mistakes (94% accuracy). However, when the reference document is perturbed with increasing levels of wrong values, the LLM is more likely to recite the incorrect, modified information when its internal prior is weaker but is more resistant when its prior is stronger. Similarly, we also find that the more the modified information deviates from the model's prior, the less likely the model is to prefer it. These results highlight an underlying tension between a model's prior knowledge and the information presented in reference documents.

![RAG模型的准确性有多高？探究RAG与大型语言模型内在先验之间的相互制衡。](../../../paper_images/2404.10198/schematic4.png)

![RAG模型的准确性有多高？探究RAG与大型语言模型内在先验之间的相互制衡。](../../../paper_images/2404.10198/fig1-2.png)

![RAG模型的准确性有多高？探究RAG与大型语言模型内在先验之间的相互制衡。](../../../paper_images/2404.10198/examples4.png)

![RAG模型的准确性有多高？探究RAG与大型语言模型内在先验之间的相互制衡。](../../../paper_images/2404.10198/adherence-prompts6.png)

![RAG模型的准确性有多高？探究RAG与大型语言模型内在先验之间的相互制衡。](../../../paper_images/2404.10198/fig1combined2.png)

[Arxiv](https://arxiv.org/abs/2404.10198)