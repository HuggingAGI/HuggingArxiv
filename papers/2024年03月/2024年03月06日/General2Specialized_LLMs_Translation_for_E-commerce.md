# [面向电商领域的 General2Specialized LLMs 翻译技术](https://arxiv.org/abs/2403.03689)

发布时间：2024年03月06日

`LLM应用`

> General2Specialized LLMs Translation for E-commerce

> 现今的NMT模型擅长处理一般领域的翻译任务，但在面对电商、法律等含有特殊表达规律的领域时显得力不从心。以电商为例，相关文本中充斥着大量的行业特有词汇和复杂的语法结构，导致现有NMT方法性能受限。为此，我们特别搜集了两类针对性资源：一组对齐的中英双语术语对及一个专门标注的电商领域平行语料库。在此基础上，我们创新性地提出了名为G2ST的两步精细调整范式，并融入了自我对比语义增强技术，旨在将普通NMT模型高效迁移至专注于电商领域的专业模型，该范式适用于基于LLMs的NMT模型。经过在实际电商商品标题上的深入评估，我们的G2ST方法展现出了卓越的翻译质量和稳健性，超越了包括LLaMA、Qwen、GPT-3.5乃至GPT-4在内的顶级NMT模型。

> Existing Neural Machine Translation (NMT) models mainly handle translation in the general domain, while overlooking domains with special writing formulas, such as e-commerce and legal documents. Taking e-commerce as an example, the texts usually include amounts of domain-related words and have more grammar problems, which leads to inferior performances of current NMT methods. To address these problems, we collect two domain-related resources, including a set of term pairs (aligned Chinese-English bilingual terms) and a parallel corpus annotated for the e-commerce domain. Furthermore, we propose a two-step fine-tuning paradigm (named G2ST) with self-contrastive semantic enhancement to transfer one general NMT model to the specialized NMT model for e-commerce. The paradigm can be used for the NMT models based on Large language models (LLMs). Extensive evaluations on real e-commerce titles demonstrate the superior translation quality and robustness of our G2ST approach, as compared with state-of-the-art NMT models such as LLaMA, Qwen, GPT-3.5, and even GPT-4.

[Arxiv](https://arxiv.org/abs/2403.03689)