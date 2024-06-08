# 利用双模态对抗性提示破解视觉语言模型

发布时间：2024年06月06日

`Agent

这篇论文主要探讨了在大规模视觉语言模型（LVLMs）中实施越狱攻击的方法，特别是提出了双模态对抗提示攻击（BAP）。这种攻击方法通过协同优化文本与视觉提示来绕过模型的安全限制，是一种主动的、策略性的攻击手段。因此，它更符合Agent分类，因为这里讨论的是一个能够主动采取行动、具有策略性的实体（即攻击方法），而不是仅仅应用或理论上的探讨。` `人工智能`

> Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt

# 摘要

> 在大规模视觉语言模型（LVLMs）领域，越狱攻击是一种红队策略，用以绕过安全限制并探索其潜在风险。传统越狱攻击多集中于视觉模态，仅通过视觉输入的干扰进行攻击，但面对融合视觉与文本特征的模型时效果不佳。为此，本文提出双模态对抗提示攻击（BAP），通过协同优化文本与视觉提示实现越狱。首先，我们在图像中嵌入普遍有害的对抗性干扰，这些干扰由少量查询无关的语料库引导，确保LVLMs对有害查询做出积极响应。接着，利用这些对抗性图像，我们针对特定有害意图优化文本提示，通过大型语言模型分析失败案例，并运用思维链推理通过反馈迭代精炼提示。我们在多个数据集和LVLMs上进行了广泛评估，结果表明我们的方法在攻击成功率上平均高出其他方法29.03%。此外，我们还展示了我们的攻击方法在商业黑盒LVLMs如Gemini和ChatGLM上的应用潜力。

> In the realm of large vision language models (LVLMs), jailbreak attacks serve as a red-teaming approach to bypass guardrails and uncover safety implications. Existing jailbreaks predominantly focus on the visual modality, perturbing solely visual inputs in the prompt for attacks. However, they fall short when confronted with aligned models that fuse visual and textual features simultaneously for generation. To address this limitation, this paper introduces the Bi-Modal Adversarial Prompt Attack (BAP), which executes jailbreaks by optimizing textual and visual prompts cohesively. Initially, we adversarially embed universally harmful perturbations in an image, guided by a few-shot query-agnostic corpus (e.g., affirmative prefixes and negative inhibitions). This process ensures that image prompt LVLMs to respond positively to any harmful queries. Subsequently, leveraging the adversarial image, we optimize textual prompts with specific harmful intent. In particular, we utilize a large language model to analyze jailbreak failures and employ chain-of-thought reasoning to refine textual prompts through a feedback-iteration manner. To validate the efficacy of our approach, we conducted extensive evaluations on various datasets and LVLMs, demonstrating that our method significantly outperforms other methods by large margins (+29.03% in attack success rate on average). Additionally, we showcase the potential of our attacks on black-box commercial LVLMs, such as Gemini and ChatGLM.

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x1.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x2.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x3.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x4.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x5.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x6.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x7.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x8.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x9.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x10.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x11.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x12.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x13.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x14.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x15.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x16.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x17.png)

![利用双模态对抗性提示破解视觉语言模型](../../../paper_images/2406.04031/x18.png)

[Arxiv](https://arxiv.org/abs/2406.04031)