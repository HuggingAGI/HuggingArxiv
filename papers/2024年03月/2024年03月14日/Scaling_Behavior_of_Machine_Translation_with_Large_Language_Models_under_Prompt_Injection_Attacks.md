# 大型语言模型在提示注入攻击下的机器翻译规模效应

发布时间：2024年03月14日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在机器翻译任务中对提示注入攻击（PIAs）的敏感性，特别是在多语言环境下的表现。研究关注的是LLMs在特定攻击条件下的行为，以及这种行为如何随模型规模的变化而变化。这属于对LLMs在实际应用中的安全性和脆弱性的研究，因此归类为LLM应用。` `机器翻译`

> Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks

# 摘要

> 大型语言模型（LLMs）因其质量与特定任务模型相当甚至更优，以及通过自然语言指令或上下文示例轻松指定任务的特性，正成为自然语言处理任务（如机器翻译）的首选平台。然而，这种通用性也使其易受终端用户的操纵，他们可能在请求中嵌入指令，诱导模型执行未经授权或不安全的操作。本研究针对机器翻译任务，探讨了不同规模的LLMs在提示注入攻击（PIAs）下的表现，并发现特定条件下，大型模型更易遭受成功攻击，这一现象被称为逆向缩放（McKenzie等人，2023）。我们首次在多语言环境中揭示了LLMs的非平凡缩放行为，并为此创建了一个新的基准数据集。

> Large Language Models (LLMs) are increasingly becoming the preferred foundation platforms for many Natural Language Processing tasks such as Machine Translation, owing to their quality often comparable to or better than task-specific models, and the simplicity of specifying the task through natural language instructions or in-context examples. Their generality, however, opens them up to subversion by end users who may embed into their requests instructions that cause the model to behave in unauthorized and possibly unsafe ways. In this work we study these Prompt Injection Attacks (PIAs) on multiple families of LLMs on a Machine Translation task, focusing on the effects of model size on the attack success rates. We introduce a new benchmark data set and we discover that on multiple language pairs and injected prompts written in English, larger models under certain conditions may become more susceptible to successful attacks, an instance of the Inverse Scaling phenomenon (McKenzie et al., 2023). To our knowledge, this is the first work to study non-trivial LLM scaling behaviour in a multi-lingual setting.

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/acc_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/pipeline.jpeg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/mt_examples.jpeg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_de_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_de.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![大型语言模型在提示注入攻击下的机器翻译规模效应](../../../paper_images/2403.09832/bleu_ru_en.jpg)

[Arxiv](https://arxiv.org/abs/2403.09832)