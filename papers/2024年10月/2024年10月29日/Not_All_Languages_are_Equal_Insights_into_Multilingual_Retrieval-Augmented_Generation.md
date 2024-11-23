# 并非所有语言都平等：有关多语言检索增强生成的洞察

发布时间：2024年10月29日

`LLM应用` `语言模型` `多语言处理`

> Not All Languages are Equal: Insights into Multilingual Retrieval-Augmented Generation

# 摘要

> RALMs（检索增强型语言模型）借助整合外部文本资源来拓展自身的知识范畴。然而，全球知识的多语言特性使得RALMs必须应对多种语言，可这方面的研究关注度有限。在本次工作中，我们提出了	extit{Futurepedia}，这是一个精心打造的基准，涵盖了八种具有代表性语言的平行文本。我们运用此基准对六种多语言RALMs进行了评估，以探究多语言RALMs所面临的挑战。实验结果揭示了语言不平等的情况：1）在单语知识提取方面，高资源语言表现出色；2）印欧语系语言促使RALMs能够直接从文档中给出答案，缓解了跨语言表达答案的难题；3）英语因RALMs的选择偏差而更具优势，在多语言知识选择中占据主导。基于这些发现，我们为改进多语言检索增强生成给出了建议。对于单语知识提取，要格外留意将低资源语言翻译为高资源语言时产生的级联错误。在跨语言知识转移中，鼓励RALMs在不同语言的文档中提供答案，能够提升转移效果。对于多语言知识选择，纳入更多非英语文档并重新调整英语文档的位置，有助于减轻RALMs的选择偏差。通过全面的实验，我们突出了多语言RALMs固有的复杂性，并为未来的研究提供了宝贵的见解。

> RALMs (Retrieval-Augmented Language Models) broaden their knowledge scope by incorporating external textual resources. However, the multilingual nature of global knowledge necessitates RALMs to handle diverse languages, a topic that has received limited research focus. In this work, we propose \textit{Futurepedia}, a carefully crafted benchmark containing parallel texts across eight representative languages. We evaluate six multilingual RALMs using our benchmark to explore the challenges of multilingual RALMs. Experimental results reveal linguistic inequalities: 1) high-resource languages stand out in Monolingual Knowledge Extraction; 2) Indo-European languages lead RALMs to provide answers directly from documents, alleviating the challenge of expressing answers across languages; 3) English benefits from RALMs' selection bias and speaks louder in multilingual knowledge selection. Based on these findings, we offer advice for improving multilingual Retrieval Augmented Generation. For monolingual knowledge extraction, careful attention must be paid to cascading errors from translating low-resource languages into high-resource ones. In cross-lingual knowledge transfer, encouraging RALMs to provide answers within documents in different languages can improve transfer performance. For multilingual knowledge selection, incorporating more non-English documents and repositioning English documents can help mitigate RALMs' selection bias. Through comprehensive experiments, we underscore the complexities inherent in multilingual RALMs and offer valuable insights for future research.

[Arxiv](https://arxiv.org/abs/2410.21970)