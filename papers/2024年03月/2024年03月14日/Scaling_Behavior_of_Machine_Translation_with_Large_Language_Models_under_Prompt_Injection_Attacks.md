# 大型语言模型在提示注入攻击下的机器翻译规模效应

发布时间：2024年03月14日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在机器翻译任务中对提示注入攻击（PIAs）的敏感性，特别是在不同规模模型下的表现。研究发现了逆向缩放现象，即在特定条件下，大型模型更容易遭受成功的攻击。这一研究关注的是LLMs在实际应用中的安全性和脆弱性，特别是在多语言环境中的表现，因此属于LLM应用分类。` `机器翻译` `网络安全`

> Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks

# 摘要

> 大型语言模型（LLMs）因其质量与特定任务模型相当甚至更优，以及通过自然语言指令或上下文示例轻松指定任务的特性，正成为机器翻译等自然语言处理任务的首选平台。然而，其通用性也使其易受终端用户的操纵，这些用户可能通过嵌入特定指令，诱导模型执行未经授权或不安全的操作。本研究针对机器翻译任务，探讨了不同规模的LLMs在提示注入攻击（PIAs）下的表现，并发现特定条件下，大型模型更易遭受成功攻击，这一现象被称为逆向缩放（McKenzie et al., 2023）。这是首次在多语言环境中深入研究LLMs非线性缩放行为的研究。

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