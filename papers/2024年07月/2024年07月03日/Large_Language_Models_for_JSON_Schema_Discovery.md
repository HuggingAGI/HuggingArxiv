# 利用大型语言模型进行 JSON 模式探索

发布时间：2024年07月03日

`LLM应用` `数据管理`

> Large Language Models for JSON Schema Discovery

# 摘要

> JSON 等半结构化数据格式因其灵活性在应用中广受欢迎，但缺乏关系数据中的固定模式。为此，我们研发了一种新方法，利用大型语言模型和人工编写的 JSON Schema 文档，自动为发现的模式添加语义信息，生成自然语言描述和有意义的定义名称，并区分有用与无用的属性。该方法在文本生成评估中表现优异，与人类判断高度一致。

> Semi-structured data formats such as JSON have proved to be useful data models for applications that require flexibility in the format of data stored. However, JSON data often come without the schemas that are typically available with relational data. This has resulted in a number of tools for discovering schemas from a collection of data. Although such tools can be useful, existing approaches focus on the syntax of documents and ignore semantic information.
  In this work, we explore the automatic addition of meaningful semantic information to discovered schemas similar to information that is added by human schema authors. We leverage large language models and a corpus of manually authored JSON Schema documents to generate natural language descriptions of schema elements, meaningful names for reusable definitions, and identify which discovered properties are most useful and which can be considered "noise". Our approach performs well on existing metrics for text generation that have been previously shown to correlate well with human judgement.

[Arxiv](https://arxiv.org/abs/2407.03286)