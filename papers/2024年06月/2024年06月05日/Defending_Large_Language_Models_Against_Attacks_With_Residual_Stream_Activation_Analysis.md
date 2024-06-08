# 利用残差流激活分析，守护大型语言模型免遭攻击之扰

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在面对对抗性攻击时的安全问题，并提出了一种基于模型内部结构的防御策略。研究内容涉及对抗性攻击的检测与缓解，以及通过安全微调技术提升模型的抗攻击能力。这些研究重点在于应用层面，即如何保护LLMs免受恶意攻击的影响，因此将其归类为LLM应用。` `网络安全` `人工智能安全`

> Defending Large Language Models Against Attacks With Residual Stream Activation Analysis

# 摘要

> 随着大型语言模型（如OpenAI的ChatGPT）的普及，对抗性攻击的威胁日益凸显。这些攻击通过恶意输入操控模型输出，损害了模型的可信度。为此，我们的研究提出了一种基于LLM内部结构的新防御策略，通过分析transformer层间的残差激活，实现了对攻击提示的精准分类。我们通过多个数据集验证了该方法在各类攻击场景中的高效性，并引入了新的攻击数据集。同时，我们通过安全微调技术提升了模型的抗攻击能力，并评估了其对攻击检测的影响。研究结果表明，我们的方法显著提升了对抗性输入的检测与缓解能力，为LLMs的安全运行奠定了坚实基础。

> The widespread adoption of Large Language Models (LLMs), exemplified by OpenAI's ChatGPT, brings to the forefront the imperative to defend against adversarial threats on these models. These attacks, which manipulate an LLM's output by introducing malicious inputs, undermine the model's integrity and the trust users place in its outputs. In response to this challenge, our paper presents an innovative defensive strategy, given white box access to an LLM, that harnesses residual activation analysis between transformer layers of the LLM. We apply an established methodology for analyzing distinctive activation patterns in the residual streams for a novel result of attack prompt classification. We curate multiple datasets to demonstrate how this method of classification has high accuracy across multiple types of attack scenarios, including our newly-created attack dataset. Furthermore, we enhance the model's resilience by integrating safety fine-tuning techniques for LLMs in order to measure its effect on our capability to detect attacks. The results underscore the effectiveness of our approach in enhancing the detection and mitigation of adversarial inputs, advancing the security framework within which LLMs operate.

[Arxiv](https://arxiv.org/abs/2406.03230)