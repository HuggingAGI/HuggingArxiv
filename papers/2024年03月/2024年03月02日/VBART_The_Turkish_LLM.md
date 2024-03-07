# [VBART——探究土耳其的大型语言模型](https://arxiv.org/abs/2403.01308)

发布时间：2024年03月02日

`LLM应用`

> VBART: The Turkish LLM

> 我们首次推出 VBART——首个从头开始，在大规模语料上预训练的土耳其语序列到序列LLMs，它汲取了 BART 和 mBART 的精华理念，有大号和超大号两种规格。精调后的VBART在摘要生成、标题创作、文本改写、问答与问题生成等多项任务中均刷新了最高纪录。它不仅为未来的文本生成任务及数据集提供了灵活的微调可能，更为土耳其NLP研究打开了全新局面。实验显示，专为土耳其语设计的预训练LLM性能超越了多语言模型达3倍之多，显著提升了既有成果，并带来了高效的训练与推理模型。另外，我们的单语分词器效率是OpenAI多语分词器的7倍。最后，我们提出一种扩充已预训练LLM规模的方法，并探讨了Chinchilla扩展定律在序列到序列掩码语言模型中的适用性。所有精调模型、高效分词器以及经清洗的135GB网络语料库均已公开发布在huggingface.co/vngrs-ai平台上。

> We present VBART, the first Turkish sequence-to-sequence Large Language Models (LLMs) pre-trained on a large corpus from scratch. VBART are compact LLMs based on good ideas leveraged from BART and mBART models and come in two sizes, Large and XLarge. Fine-tuned VBART models surpass the prior state-of-the-art results in abstractive text summarization, title generation, text paraphrasing, question answering and question generation tasks. They allow fine-tuning for future text generation tasks and datasets, carving a new path for Turkish Natural Language Processing (NLP) research. Our work shows that having a pre-trained LLM for Turkish outperforms up to 3x multilingual models, improving existing results and providing efficient models for training and inference. Moreover, we show that our monolingual tokenizer is 7x more efficient than OpenAI's multilingual tokenizer. Last but not least, we introduce a method to enlarge an existing pre-trained LLM and question the relevancy of Chinchilla Scaling Law to sequence-to-sequence masked language models. Our fine-tuned models, tokenizer and cleaned web corpus of 135 GB are publicly available at huggingface.co/vngrs-ai.