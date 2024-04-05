# 针对 GPT-4V 的红队测试：这款 AI 能否抵御单模态或多模态的攻击逃逸？

发布时间：2024年04月04日

`LLM理论` `安全性评估` `人工智能`

> Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?

# 摘要

> 为挑战大型语言模型（LLMs）的安全性，已提出多种越狱攻击手段，暴露了LLMs的安全漏洞。这些攻击手段不只局限于文本，还通过干扰视觉输入，将攻击延伸至多模态大型语言模型（MLLMs）。然而，普遍评估标准的缺失，使得性能再现和公正比较变得困难。特别是对于闭源的顶尖（Sota）模型，如GPT-4V，缺乏全面的评估。针对这些问题，本研究首先构建了一个包含1445个有害问题、覆盖11项安全政策的综合越狱评估数据集。利用此数据集，对11种不同的LLMs和MLLMs进行了深入的红队测试，涵盖了从Sota专有模型到开源模型。我们进一步深入分析了评估结果，结果显示：（1）GPT4和GPT-4V在抵御越狱攻击方面，相比其他开源LLMs和MLLMs表现出更强的鲁棒性。（2）在开源模型中，Llama2和Qwen-VL-Chat的鲁棒性更为突出。（3）相比文本攻击手段，视觉越狱手段的通用性相对受限。相关数据集和代码已在 https://anonymous.4open.science/r/red_teaming_gpt4-C1CE/README.md 上公布。

> Various jailbreak attacks have been proposed to red-team Large Language Models (LLMs) and revealed the vulnerable safeguards of LLMs. Besides, some methods are not limited to the textual modality and extend the jailbreak attack to Multimodal Large Language Models (MLLMs) by perturbing the visual input. However, the absence of a universal evaluation benchmark complicates the performance reproduction and fair comparison. Besides, there is a lack of comprehensive evaluation of closed-source state-of-the-art (SOTA) models, especially MLLMs, such as GPT-4V. To address these issues, this work first builds a comprehensive jailbreak evaluation dataset with 1445 harmful questions covering 11 different safety policies. Based on this dataset, extensive red-teaming experiments are conducted on 11 different LLMs and MLLMs, including both SOTA proprietary models and open-source models. We then conduct a deep analysis of the evaluated results and find that (1) GPT4 and GPT-4V demonstrate better robustness against jailbreak attacks compared to open-source LLMs and MLLMs. (2) Llama2 and Qwen-VL-Chat are more robust compared to other open-source models. (3) The transferability of visual jailbreak methods is relatively limited compared to textual jailbreak methods. The dataset and code can be found here https://anonymous.4open.science/r/red_teaming_gpt4-C1CE/README.md .

[Arxiv](https://arxiv.org/abs/2404.03411)