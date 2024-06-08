# 利用残差流激活分析，守护大型语言模型免遭攻击

发布时间：2024年06月05日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在面对对抗性攻击时的安全问题，并提出了一种基于白盒访问的防御策略。通过分析LLM内部transformer层的残差激活，研究者能够高效地分类攻击提示，并通过安全微调技术增强模型的抗攻击能力。这些内容直接关联到LLMs的实际应用中的安全性问题，因此属于LLM应用分类。` `网络安全` `人工智能安全`

> Defending Large Language Models Against Attacks With Residual Stream Activation Analysis

# 摘要

> 随着大型语言模型（如OpenAI的ChatGPT）的普及，对抗性攻击的威胁日益凸显。这些攻击通过恶意输入操控模型输出，损害了模型的可信度。为此，我们的研究提出了一种基于白盒访问的防御策略，利用LLM内部transformer层的残差激活分析。我们通过分析残差流中的激活模式，实现了攻击提示的高效分类，并在多个自定义数据集上验证了其跨多种攻击场景的高准确性。此外，我们通过安全微调技术增强了模型的抗攻击能力，并评估了其对攻击检测的影响。研究结果表明，我们的方法显著提升了对抗性输入的检测与缓解能力，为LLMs的安全运行框架带来了进步。

> The widespread adoption of Large Language Models (LLMs), exemplified by OpenAI's ChatGPT, brings to the forefront the imperative to defend against adversarial threats on these models. These attacks, which manipulate an LLM's output by introducing malicious inputs, undermine the model's integrity and the trust users place in its outputs. In response to this challenge, our paper presents an innovative defensive strategy, given white box access to an LLM, that harnesses residual activation analysis between transformer layers of the LLM. We apply an established methodology for analyzing distinctive activation patterns in the residual streams for a novel result of attack prompt classification. We curate multiple datasets to demonstrate how this method of classification has high accuracy across multiple types of attack scenarios, including our newly-created attack dataset. Furthermore, we enhance the model's resilience by integrating safety fine-tuning techniques for LLMs in order to measure its effect on our capability to detect attacks. The results underscore the effectiveness of our approach in enhancing the detection and mitigation of adversarial inputs, advancing the security framework within which LLMs operate.

[Arxiv](https://arxiv.org/abs/2406.03230)