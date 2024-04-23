# PARAMANU-GANITA：一款具备数学处理能力的先进语言模型

发布时间：2024年04月22日

`LLM应用`

> PARAMANU-GANITA: Language Model with Mathematical Capabilities

# 摘要

> 本文中，我们展示了 Paramanu-Ganita，这是一款拥有 2.08 亿参数的自回归解码器语言模型，专为数学领域设计。该模型基于我们精选的混合数学语料库，从零开始进行预训练，上下文尺寸为 4096。在困惑度和 GSM8k 数学基准测试中，我们对模型进行了评估。Paramanu-Ganita 虽然规模仅为 7B LLM 的三十分之一，却在 GSM8k 测试准确度上超越了多款通用型 LLM，包括 LLaMa-1 7B（28.4%）、LLaMa-2 7B（27.6%）、Falcon 7B（32.6%）和 PaLM 8B（35.3%），以及专业数学 LLM，如 Minerva 8B（23.2%）和 LLEMMA-7B（3.0%）。此外，Paramanu-Ganita 还在性能上超越了诸如 PaLM 62B（6.4%）、Falcon 40B（19.8%）、LLaMa-1 33B（3.8%）和 Vicuna 13B（11.8%）等巨型 LLM。这一显著的性能提升表明，语言模型的推理能力并非仅局限于拥有庞大参数集的 LLM。Paramanu-Ganita 仅经过 146 小时的 A100 训练，相比之下，专业数学 LLM LLEMMA 7B 则训练了 23,000 小时。这表明，从头开始预训练强大的领域特定语言模型以适应特定领域，比对 LLM 进行持续训练更具成本效益。因此，我们得出结论，要实现语言模型的高级数学推理能力，并非必须依赖庞大的 LLM 和巨大的计算资源。最终，我们想要强调的是，Paramanu-Ganita 仅在我们完整数学语料库的一部分上进行了训练，模型的全部潜力还有待进一步挖掘。

> In this paper, we present Paramanu-Ganita, a 208 million parameter novel Auto Regressive (AR) decoder based language model on mathematics. The model is pretrained from scratch at context size of 4096 on our curated mixed mathematical corpus. We evaluate our model on both perplexity metric and GSM8k mathematical benchmark. Paramanu-Ganita despite being 35 times smaller than 7B LLMs, outperformed generalist LLMs such as LLaMa-1 7B by 28.4% points, LLaMa-2 7B by 27.6% points, Falcon 7B by 32.6% points, PaLM 8B by 35.3% points, and math specialised LLMs such as Minerva 8B by 23.2% points, and LLEMMA-7B by 3.0% points in GSM8k test accuracy metric respectively. Paramanu-Ganita also outperformed giant LLMs like PaLM 62B by 6.4% points, Falcon 40B by 19.8% points, LLaMa-1 33B by 3.8% points and Vicuna 13B by 11.8% points respectively. The large significant margin improvement in performance of our math model over the existing LLMs signifies that reasoning capabilities of language model are just not restricted to LLMs with humongous number of parameters. Paramanu-Ganita took 146 hours of A100 training whereas math specialised LLM, LLEMMA 7B, was trained for 23,000 A100 hours of training equivalent. Thus, our approach of pretraining powerful domain specialised language models from scratch for domain adaptation is much more cost-effective than performing continual training of LLMs for domain adaptation. Hence, we conclude that for strong mathematical reasoning abilities of language model, we do not need giant LLMs and immense computing power to our end. In the end, we want to point out that we have only trained Paramanu-Ganita only on a part of our entire mathematical corpus and yet to explore the full potential of our model.

[Arxiv](https://arxiv.org/abs/2404.14395)