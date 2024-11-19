# 以知识图嵌入作为额外的模态来处理语言模型中的幻觉问题。

发布时间：2024年11月18日

`LLM应用` `知识图谱` `语言模型`

> Addressing Hallucinations in Language Models with Knowledge Graph Embeddings as an Additional Modality

# 摘要

> 在本文中，我们给出了一种借助将知识图谱（KGs）当作额外模态来降低大型语言模型（LLMs）中幻觉现象的办法。我们的方法是把输入文本转化成一组KG嵌入，再利用一个适配器把这些嵌入整合进语言模型空间，且无需依赖外部检索流程。
  为达成此目的，我们创建了WikiEntities，这是一个涵盖超300万篇维基百科文本的数据集，其中带有来自Wikidata的实体标注及其在PyTorch-BigGraph中的对应嵌入。该数据集是训练实体链接模型以及使用专门适配器让上述方法适配各类LLMs的珍贵资源。
  我们的方法无需对语言模型本身进行微调，只需训练适配器即可。这能保证模型在其他任务上的表现不受影响。我们用此数据集为Mistral 7B、LLaMA 2-7B（聊天）和LLaMA 3-8B（指导）模型训练了适配器，并证实我们的方法在HaluEval、True-False基准和FEVER数据集上提升了性能。结果显示，把KGs作为新模态引入能够切实减少幻觉，提高语言模型的事实准确性，且无需外部检索。

> In this paper we present an approach to reduce hallucinations in Large Language Models (LLMs) by incorporating Knowledge Graphs (KGs) as an additional modality. Our method involves transforming input text into a set of KG embeddings and using an adapter to integrate these embeddings into the language model space, without relying on external retrieval processes.
  To facilitate this, we created WikiEntities, a dataset containing over 3 million Wikipedia texts annotated with entities from Wikidata and their corresponding embeddings from PyTorch-BigGraph. This dataset serves as a valuable resource for training Entity Linking models and adapting the described method to various LLMs using specialized adapters.
  Our method does not require fine-tuning of the language models themselves; instead, we only train the adapter. This ensures that the model's performance on other tasks is not affected. We trained an adapter for the Mistral 7B, LLaMA 2-7B (chat), and LLaMA 3-8B (instruct) models using this dataset and demonstrated that our approach improves performance on the HaluEval, True-False benchmarks and FEVER dataset. The results indicate that incorporating KGs as a new modality can effectively reduce hallucinations and improve the factual accuracy of language models, all without the need for external retrieval.

[Arxiv](https://arxiv.org/abs/2411.11531)