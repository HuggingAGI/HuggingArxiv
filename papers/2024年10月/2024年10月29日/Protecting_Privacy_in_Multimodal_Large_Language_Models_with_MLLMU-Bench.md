# 借助 MLLMU-Bench 保护多模态大型语言模型中的隐私

发布时间：2024年10月29日

`LLM应用` `多模态` `机器遗忘`

> Protecting Privacy in Multimodal Large Language Models with MLLMU-Bench

# 摘要

> 像基于大规模网络语料库训练的大型语言模型（LLM）和多模态大型语言模型（MLLMs）这样的生成式模型，能够记住并泄露个人的机密和隐私数据，从而引发法律和伦理方面的担忧。此前虽有众多工作通过机器遗忘在LLM中处理此问题，但在MLLMs方面，这仍基本未被探索。为应对这一挑战，我们推出了多模态大型语言模型遗忘基准（MLLMU-Bench），这一全新的基准旨在加深对多模态机器遗忘的理解。MLLMU-Bench包含500个虚构人物资料和153个公众名人资料，每个资料都有超过14个定制的问答对，并从多模态（图像+文本）和单模态（文本）的视角进行评估。该基准分为四组，用于从效果、通用性和模型实用性等方面评估遗忘算法。最后，我们给出了使用现有生成式模型遗忘算法的基线结果。令人意外的是，我们的实验显示，单模态遗忘算法在生成和填空任务中表现出众，而多模态遗忘方法在具有多模态输入的分类任务中更胜一筹。

> Generative models such as Large Language Models (LLM) and Multimodal Large Language models (MLLMs) trained on massive web corpora can memorize and disclose individuals' confidential and private data, raising legal and ethical concerns. While many previous works have addressed this issue in LLM via machine unlearning, it remains largely unexplored for MLLMs. To tackle this challenge, we introduce Multimodal Large Language Model Unlearning Benchmark (MLLMU-Bench), a novel benchmark aimed at advancing the understanding of multimodal machine unlearning. MLLMU-Bench consists of 500 fictitious profiles and 153 profiles for public celebrities, each profile feature over 14 customized question-answer pairs, evaluated from both multimodal (image+text) and unimodal (text) perspectives. The benchmark is divided into four sets to assess unlearning algorithms in terms of efficacy, generalizability, and model utility. Finally, we provide baseline results using existing generative model unlearning algorithms. Surprisingly, our experiments show that unimodal unlearning algorithms excel in generation and cloze tasks, while multimodal unlearning approaches perform better in classification tasks with multimodal inputs.

[Arxiv](https://arxiv.org/abs/2410.22108)