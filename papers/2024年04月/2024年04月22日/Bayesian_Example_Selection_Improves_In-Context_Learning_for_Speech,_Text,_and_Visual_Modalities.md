# 采用贝叶斯方法精选示例，显著提升了语音、文本和视觉模式的情境学习效果。

发布时间：2024年04月22日

`LLM应用` `机器学习`

> Bayesian Example Selection Improves In-Context Learning for Speech, Text, and Visual Modalities

# 摘要

> 大型语言模型（LLMs）能够通过对话历史中的少量示例进行上下文学习（ICL），从而适应新任务，无需调整模型参数。然而，ICL的表现极大依赖于所提供的上下文示例的质量，因此，如何选择这些示例变得至关重要。本论文提出了一种创新的贝叶斯上下文示例选择方法（ByCS），它根据贝叶斯定理扩展了基于上下文示例的条件推断概率，专注于基于测试输入的逆向推断。基于准确的逆向推断概率能够带来准确的推断概率（后验概率）的假设，ByCS根据逆向推断的结果来挑选上下文示例。通过在语音、文本和图像示例上的多样化和广泛的跨任务、跨模态实验，实验结果证明了ByCS方法在不同模型、任务和模态上的有效性和鲁棒性。

> Large language models (LLMs) can adapt to new tasks through in-context learning (ICL) based on a few examples presented in dialogue history without any model parameter update. Despite such convenience, the performance of ICL heavily depends on the quality of the in-context examples presented, which makes the in-context example selection approach a critical choice. This paper proposes a novel Bayesian in-Context example Selection method (ByCS) for ICL. Extending the inference probability conditioned on in-context examples based on Bayes' theorem, ByCS focuses on the inverse inference conditioned on test input. Following the assumption that accurate inverse inference probability (likelihood) will result in accurate inference probability (posterior), in-context examples are selected based on their inverse inference results. Diverse and extensive cross-tasking and cross-modality experiments are performed with speech, text, and image examples. Experimental results show the efficacy and robustness of our ByCS method on various models, tasks and modalities.

[Arxiv](https://arxiv.org/abs/2404.14716)