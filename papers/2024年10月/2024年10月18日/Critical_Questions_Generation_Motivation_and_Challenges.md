# 关键问题生成：探索背后的动机与面临的挑战

发布时间：2024年10月18日

`LLM应用` `信息安全` `人工智能`

> Critical Questions Generation: Motivation and Challenges

# 摘要

> 大型语言模型（LLM）在反驳生成等对抗错误信息的策略上表现出色，但仍受限于过时知识和幻觉内容生成。为此，我们提出“批判性问题生成”任务，通过处理论证文本生成关键问题（CQ），揭示论证的盲点。我们利用 LLM 质疑论证，无需外部知识。为进行大规模实验，我们探索了两种创建数据集的方法：一是基于 Walton 论证理论的 CQ 模板，二是直接使用 LLM 生成 CQ。研究表明，LLM 虽能生成 CQ，但仍有显著提升空间。

> The development of Large Language Models (LLMs) has brought impressive performances on mitigation strategies against misinformation, such as counterargument generation. However, LLMs are still seriously hindered by outdated knowledge and by their tendency to generate hallucinated content. In order to circumvent these issues, we propose a new task, namely, Critical Questions Generation, consisting of processing an argumentative text to generate the critical questions (CQs) raised by it. In argumentation theory CQs are tools designed to lay bare the blind spots of an argument by pointing at the information it could be missing. Thus, instead of trying to deploy LLMs to produce knowledgeable and relevant counterarguments, we use them to question arguments, without requiring any external knowledge. Research on CQs Generation using LLMs requires a reference dataset for large scale experimentation. Thus, in this work we investigate two complementary methods to create such a resource: (i) instantiating CQs templates as defined by Walton's argumentation theory and (ii), using LLMs as CQs generators. By doing so, we contribute with a procedure to establish what is a valid CQ and conclude that, while LLMs are reasonable CQ generators, they still have a wide margin for improvement in this task.

[Arxiv](https://arxiv.org/abs/2410.14335)