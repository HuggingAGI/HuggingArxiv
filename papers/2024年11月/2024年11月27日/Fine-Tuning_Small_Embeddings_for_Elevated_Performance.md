# 通过微调小嵌入来提升性能

发布时间：2024年11月27日

`LLM应用` `尼泊尔语`

> Fine-Tuning Small Embeddings for Elevated Performance

# 摘要

> 情境嵌入在各类自然语言处理任务中都斩获了顶尖成果。但这些嵌入受限于模型，因为此类模型需要海量数据和强大的计算能力。对于尼泊尔语这类低资源语言而言，这是个难题，毕竟互联网上可获取的数据量往往难以满足模型所需。此项工作采用了一个带有六个在尼泊尔语上预训练的注意力头的不完整 BERT 模型，并在先前未见过的数据上进行了微调。将内在和外在评估所得结果与原始模型基线以及在尼泊尔语上预训练的完整 BERT 模型（作为基准）得出的结果进行了对比。结果显示，尽管基准平均表现更优，但与原始基线相比，对小嵌入进行微调显著提升了结果。

> Contextual Embeddings have yielded state-of-the-art results in various natural language processing tasks. However, these embeddings are constrained by models requiring large amounts of data and huge computing power. This is an issue for low-resource languages like Nepali as the amount of data available over the internet is not always sufficient for the models. This work has taken an incomplete BERT model with six attention heads pretrained on Nepali language and finetuned it on previously unseen data. The obtained results from intrinsic and extrinsic evaluations have been compared to the results drawn from the original model baseline and a complete BERT model pretrained on Nepali language as the oracle. The results demonstrate that even though the oracle is better on average, finetuning the small embeddings drastically improves results compared to the original baseline.

[Arxiv](https://arxiv.org/abs/2411.18099)