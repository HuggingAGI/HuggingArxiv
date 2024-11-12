# vTune：通过后门实现大型语言模型的可验证微调

发布时间：2024年11月10日

`LLM应用` `语言模型` `模型验证`

> vTune: Verifiable Fine-Tuning for LLMs Through Backdooring

# 摘要

> 随着大型语言模型（LLM）的微调变得越来越普遍，用户通常依赖第三方服务，而对其微调过程的可见性有限。这种缺乏透明度引发了一个问题：\emph{消费者如何验证微调服务是否正确执行}？例如，服务提供商可能声称为每个用户微调模型，但只是将相同的基础模型发送回所有用户。为了解决这个问题，我们提出了 vTune，一种简单的方法，它使用添加到训练数据中的少量	extit{后门}数据点来提供统计测试，以验证提供商是否在特定用户的数据集上微调了自定义模型。与现有工作不同，vTune 能够扩展到对最先进的 LLM 微调的验证，并且可以与开源和闭源模型一起使用。我们在几个模型系列和大小以及多个指令调优数据集上测试了我们的方法，发现统计测试满足 p 值约为$\sim 10^{-40}$，对下游任务性能没有负面影响。此外，我们探索了几种试图颠覆 vTune 的攻击，并证明了该方法对这些攻击的鲁棒性。

> As fine-tuning large language models (LLMs) becomes increasingly prevalent, users often rely on third-party services with limited visibility into their fine-tuning processes. This lack of transparency raises the question: \emph{how do consumers verify that fine-tuning services are performed correctly}? For instance, a service provider could claim to fine-tune a model for each user, yet simply send all users back the same base model. To address this issue, we propose vTune, a simple method that uses a small number of \textit{backdoor} data points added to the training data to provide a statistical test for verifying that a provider fine-tuned a custom model on a particular user's dataset. Unlike existing works, vTune is able to scale to verification of fine-tuning on state-of-the-art LLMs, and can be used both with open-source and closed-source models. We test our approach across several model families and sizes as well as across multiple instruction-tuning datasets, and find that the statistical test is satisfied with p-values on the order of $\sim 10^{-40}$, with no negative impact on downstream task performance. Further, we explore several attacks that attempt to subvert vTune and demonstrate the method's robustness to these attacks.

[Arxiv](https://arxiv.org/abs/2411.06611)