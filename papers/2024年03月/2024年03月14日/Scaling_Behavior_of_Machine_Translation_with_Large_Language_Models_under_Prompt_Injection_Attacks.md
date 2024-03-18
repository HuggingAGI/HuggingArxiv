# 面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律

发布时间：2024年03月14日

`LLM应用` `机器翻译` `语言模型安全`

> Scaling Behavior of Machine Translation with Large Language Models under Prompt Injection Attacks

> 随着LLMs在诸如机器翻译等各类NLP任务中的广泛应用，它们凭借堪比甚至优于特定任务模型的性能以及通过自然语言指令轻松定义任务的优势，日渐成为首选基石。但这种普适性也让它们面临一个挑战——不怀好意的终端用户可能在输入请求时植入恶意指令，使模型做出未经授权甚至有安全风险的行为。在此研究中，我们聚焦于LLMs在机器翻译任务上遭遇的提示注入攻击（PIAs），并着重分析了模型尺寸对攻击成功率的影响。我们构建了一个全新的基准数据集，并揭示出一个有趣的现象：对于多组不同语言对和采用英文编写的注入提示，在特定条件下，模型尺寸更大的情况下反而可能更容易遭受成功攻击，这恰好印证了“逆向缩放”效应（McKenzie等人，2023年）。迄今为止，这是首个深入探索多语种环境下非平凡LLM缩放行为的研究工作。

> Large Language Models (LLMs) are increasingly becoming the preferred foundation platforms for many Natural Language Processing tasks such as Machine Translation, owing to their quality often comparable to or better than task-specific models, and the simplicity of specifying the task through natural language instructions or in-context examples. Their generality, however, opens them up to subversion by end users who may embed into their requests instructions that cause the model to behave in unauthorized and possibly unsafe ways. In this work we study these Prompt Injection Attacks (PIAs) on multiple families of LLMs on a Machine Translation task, focusing on the effects of model size on the attack success rates. We introduce a new benchmark data set and we discover that on multiple language pairs and injected prompts written in English, larger models under certain conditions may become more susceptible to successful attacks, an instance of the Inverse Scaling phenomenon (McKenzie et al., 2023). To our knowledge, this is the first work to study non-trivial LLM scaling behaviour in a multi-lingual setting.

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/acc_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/accuracy_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/pipeline.jpeg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/mt_examples.jpeg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ru.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_de_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_fr_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ro_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_de.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_fr.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_en_ro.jpg)

![面对提示注入攻击，探究大规模语言模型应用于机器翻译任务时的性能变化规律](../../../paper_images/2403.09832/bleu_ru_en.jpg)

[Arxiv](https://arxiv.org/abs/2403.09832)