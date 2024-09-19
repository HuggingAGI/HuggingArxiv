# 大型语言模型的双层训练与解码，实现边思考边表达

发布时间：2024年09月18日

`LLM理论` `人工智能`

> Dual-Layer Training and Decoding of Large Language Model with Simultaneously Thinking and Speaking

# 摘要

> 大型语言模型虽能理解和生成人类表达，但缺乏深入思考和推理能力。近期研究虽提升了模型的思考能力，但大多非数据驱动或基于训练。本文受自然界认知机制启发，设计了名为 TaS 的新模型，使其先思考后表达。我们通过注释和生成思想内容，并在中间层加入思考层，训练模型以生成合理思想和更优响应。定性和定量结果均证实了 TaS 的有效性。代码详见 https://anonymous.4open.science/r/TadE。

> Large Language Model can reasonably understand and generate human expressions but may lack of thorough thinking and reasoning mechanisms. Recently there have been several studies which enhance the thinking ability of language models but most of them are not data-driven or training-based. In this paper, we are motivated by the cognitive mechanism in the natural world, and design a novel model architecture called TaS which allows it to first consider the thoughts and then express the response based upon the query. We design several pipelines to annotate or generate the thought contents from prompt-response samples, then add language heads in a middle layer which behaves as the thinking layer. We train the language model by the thoughts-augmented data and successfully let the thinking layer automatically generate reasonable thoughts and finally output more reasonable responses. Both qualitative examples and quantitative results validate the effectiveness and performance of TaS. Our code is available at https://anonymous.4open.science/r/TadE.

[Arxiv](https://arxiv.org/abs/2409.12059)