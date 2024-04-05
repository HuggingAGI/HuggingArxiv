# JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。

发布时间：2024年04月03日

`LLM应用` `多模态` `安全性`

> JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks

# 摘要

> 随着多模态大型语言模型（MLLMs）技术的飞速进步，如何保护这些模型不受恶意数据侵害，同时确保它们与人类价值观相符，成为了一项紧迫的挑战。本文探讨了一个尚未被充分研究的问题：那些成功攻破大型语言模型（LLMs）的技术，是否同样适用于攻破MLLMs。为此，我们推出了JailBreakV-28K这一创新基准，旨在测试LLM破解技术在MLLMs上的适用性，评估MLLMs抵御各类破解攻击的能力。通过使用本文提出的2000个恶意查询样本，结合先进的LLM破解手段，我们生成了20000个文本破解提示，以及8000个来自最新MLLMs破解活动的图像破解样本。这个全面的测试集涵盖了28000个对抗性测试案例。我们对10个开源MLLMs的测试结果显示，源自LLMs的攻击具有较高的成功率，暴露了MLLMs在处理文本时的一个重大安全漏洞。研究结果凸显了未来研究亟需解决MLLMs在文本和视觉输入方面的对齐弱点。

> With the rapid advancements in Multimodal Large Language Models (MLLMs), securing these models against malicious inputs while align- ing them with human values has emerged as a critical challenge. In this paper, we investigate an important and unexplored question of whether techniques that successfully jailbreak Large Language Models (LLMs) can be equally effective in jailbreaking MLLMs. To explore this issue, we in- troduce JailBreakV-28K, a pioneering benchmark designed to assess the transferability of LLM jailbreak techniques to MLLMs, thereby evaluat- ing the robustness of MLLMs against diverse jailbreak attacks. Utilizing a dataset of 2, 000 malicious queries that is also proposed in this paper, we generate 20, 000 text-based jailbreak prompts using advanced jailbreak attacks on LLMs, alongside 8, 000 image-based jailbreak inputs from recent MLLMs jailbreak attacks, our comprehensive dataset includes 28, 000 test cases across a spectrum of adversarial scenarios. Our evaluation of 10 open- source MLLMs reveals a notably high Attack Success Rate (ASR) for attacks transferred from LLMs, highlighting a critical vulnerability in MLLMs that stems from their text-processing capabilities. Our findings underscore the urgent need for future research to address alignment vulnerabilities in MLLMs from both textual and visual inputs.

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x1.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x2.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x3.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x4.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/LLMJS.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/MultiJail.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/Question_Set.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/Safebench.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/HarmfulTasks.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/harmbench.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/Redteam2K.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x5.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x6.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x7.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x8.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x9.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x10.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x11.png)

![JailBreakV-28K：针对越狱攻击，评估多模态大型语言模型鲁棒性的基准测试。](../../../paper_images/2404.03027/x12.png)

[Arxiv](https://arxiv.org/abs/2404.03027)