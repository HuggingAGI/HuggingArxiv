# 探究检索增强型大型语言模型中的归因偏差

发布时间：2024年10月16日

`RAG` `人工智能` `信息检索`

> Evaluation of Attribution Bias in Retrieval-Augmented Large Language Models

# 摘要

> 将答案归因于源文档是提升 RAG 模型输出可验证性的方法。以往研究多聚焦于提升和评估 LLM 在 RAG 中的归因质量，但可能因此引入偏见。我们探讨了 LLM 在 RAG 中的归因敏感性和作者信息偏见。通过告知 LLM 源文档作者并指示其归因答案，我们分析了 LLM 输出对作者的敏感性及对人类或 AI 生成文档的偏见。实验表明，添加作者信息可使 LLM 归因质量变化 3% 至 18%。此外，LLM 可能偏爱人类作者，这与先前研究中 LLM 生成内容更受青睐的结论形成对比。研究显示，源文档元数据影响 LLM 的信任度和归因方式，并揭示了归因偏见和敏感性是 LLM 脆弱性的新视角。

> Attributing answers to source documents is an approach used to enhance the verifiability of a model's output in retrieval augmented generation (RAG). Prior work has mainly focused on improving and evaluating the attribution quality of large language models (LLMs) in RAG, but this may come at the expense of inducing biases in the attribution of answers. We define and examine two aspects in the evaluation of LLMs in RAG pipelines, namely attribution sensitivity and bias with respect to authorship information. We explicitly inform an LLM about the authors of source documents, instruct it to attribute its answers, and analyze (i) how sensitive the LLM's output is to the author of source documents, and (ii) whether the LLM exhibits a bias towards human-written or AI-generated source documents. We design an experimental setup in which we use counterfactual evaluation to study three LLMs in terms of their attribution sensitivity and bias in RAG pipelines. Our results show that adding authorship information to source documents can significantly change the attribution quality of LLMs by 3% to 18%. Moreover, we show that LLMs can have an attribution bias towards explicit human authorship, which can serve as a competing hypothesis for findings of prior work that shows that LLM-generated content may be preferred over human-written contents. Our findings indicate that metadata of source documents can influence LLMs' trust, and how they attribute their answers. Furthermore, our research highlights attribution bias and sensitivity as a novel aspect of brittleness in LLMs.

[Arxiv](https://arxiv.org/abs/2410.12380)