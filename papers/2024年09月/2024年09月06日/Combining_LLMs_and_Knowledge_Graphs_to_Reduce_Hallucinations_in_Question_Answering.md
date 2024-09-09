# 将 LLM 与知识图谱结合，旨在减少问答中的幻觉现象。

发布时间：2024年09月06日

`LLM应用` `生物医学` `问答系统`

> Combining LLMs and Knowledge Graphs to Reduce Hallucinations in Question Answering

# 摘要

> 自然语言处理的进步让数字信息系统（如数据库）变得更加亲民。但在生物医学等对准确性要求极高的领域，挑战依旧。幻觉问题尤为棘手，模型可能生成与数据不符的信息，带来误导风险。本文通过结合大型语言模型（LLM）和知识图谱（KG），提出了一种提升问答系统准确性的新方法，以生物医学KG为例。基于LangChain框架，我们的方法引入查询检查器，确保LLM生成的查询既合语法又合逻辑，从而减少错误。我们用50个生物医学问题的新数据集测试了多个LLM，发现GPT-4 Turbo在准确性上领先，而llama3:70b等开源模型在精心设计提示后也表现不俗。为方便用户，我们开发了友好的Web界面，用户可输入自然语言查询，查看并验证生成的Cypher查询。这种混合方法有效解决了数据缺口和幻觉问题，为问答系统提供了可靠且直观的解决方案。源代码已公开，详见：https://git.zib.de/lpusch/cyphergenkg-gui。

> Advancements in natural language processing have revolutionized the way we can interact with digital information systems, such as databases, making them more accessible. However, challenges persist, especially when accuracy is critical, as in the biomedical domain. A key issue is the hallucination problem, where models generate information unsupported by the underlying data, potentially leading to dangerous misinformation. This paper presents a novel approach designed to bridge this gap by combining Large Language Models (LLM) and Knowledge Graphs (KG) to improve the accuracy and reliability of question-answering systems, on the example of a biomedical KG. Built on the LangChain framework, our method incorporates a query checker that ensures the syntactical and semantic validity of LLM-generated queries, which are then used to extract information from a Knowledge Graph, substantially reducing errors like hallucinations. We evaluated the overall performance using a new benchmark dataset of 50 biomedical questions, testing several LLMs, including GPT-4 Turbo and llama3:70b. Our results indicate that while GPT-4 Turbo outperforms other models in generating accurate queries, open-source models like llama3:70b show promise with appropriate prompt engineering. To make this approach accessible, a user-friendly web-based interface has been developed, allowing users to input natural language queries, view generated and corrected Cypher queries, and verify the resulting paths for accuracy. Overall, this hybrid approach effectively addresses common issues such as data gaps and hallucinations, offering a reliable and intuitive solution for question answering systems. The source code for generating the results of this paper and for the user-interface can be found in our Git repository: https://git.zib.de/lpusch/cyphergenkg-gui

[Arxiv](https://arxiv.org/abs/2409.04181)