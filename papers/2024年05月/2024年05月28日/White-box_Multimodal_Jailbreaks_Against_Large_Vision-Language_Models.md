# 大型视觉-语言模型面临的白盒多模态越狱挑战

发布时间：2024年05月28日

`Agent

这篇论文主要探讨了大型视觉-语言模型（VLMs）的对抗性鲁棒性问题，并提出了一种新的攻击策略，该策略同时针对文本和图像模态，以揭示VLMs的深层次脆弱性。研究中设计了一种双重优化机制，通过生成对抗性图像前缀和文本后缀，诱导模型产生有害的肯定性回答。这种策略能够绕过模型的防御机制，产生不当内容，即所谓的“越狱”。因此，这篇论文更偏向于研究如何通过设计特定的攻击策略来测试和揭示模型的脆弱性，属于Agent相关的研究范畴。` `网络安全` `人工智能安全`

> White-box Multimodal Jailbreaks Against Large Vision-Language Models

# 摘要

> 大型视觉-语言模型（VLMs）在多模态任务中的表现日益卓越，但其对抗性鲁棒性仍未被充分研究。现有评估方法主要针对图像进行单模态攻击，而对文本攻击的抵抗力则被视为理所当然。本研究提出了一种新的攻击策略，同时针对文本和图像模态，以揭示VLMs更深层次的脆弱性。我们设计了一种双重优化机制，旨在诱导模型产生高毒性的肯定性回答。首先，我们从随机噪声中生成一个对抗性图像前缀，使其在没有文本输入时也能引发有害反应，赋予图像有毒的语义。接着，我们将对抗性文本后缀与图像前缀结合并共同优化，以提高对有害指令的肯定性响应概率。这一组合被称为通用主密钥（UMK），它能嵌入恶意查询中，绕过VLMs的防御机制，产生不当内容，即所谓的“越狱”。实验证明，我们的策略能以96%的成功率越狱MiniGPT-4，凸显了VLMs的潜在风险，并呼吁开发新的对齐策略。

> Recent advancements in Large Vision-Language Models (VLMs) have underscored their superiority in various multimodal tasks. However, the adversarial robustness of VLMs has not been fully explored. Existing methods mainly assess robustness through unimodal adversarial attacks that perturb images, while assuming inherent resilience against text-based attacks. Different from existing attacks, in this work we propose a more comprehensive strategy that jointly attacks both text and image modalities to exploit a broader spectrum of vulnerability within VLMs. Specifically, we propose a dual optimization objective aimed at guiding the model to generate affirmative responses with high toxicity. Our attack method begins by optimizing an adversarial image prefix from random noise to generate diverse harmful responses in the absence of text input, thus imbuing the image with toxic semantics. Subsequently, an adversarial text suffix is integrated and co-optimized with the adversarial image prefix to maximize the probability of eliciting affirmative responses to various harmful instructions. The discovered adversarial image prefix and text suffix are collectively denoted as a Universal Master Key (UMK). When integrated into various malicious queries, UMK can circumvent the alignment defenses of VLMs and lead to the generation of objectionable content, known as jailbreaks. The experimental results demonstrate that our universal attack strategy can effectively jailbreak MiniGPT-4 with a 96% success rate, highlighting the vulnerability of VLMs and the urgent need for new alignment strategies.

![大型视觉-语言模型面临的白盒多模态越狱挑战](../../../paper_images/2405.17894/x1.png)

![大型视觉-语言模型面临的白盒多模态越狱挑战](../../../paper_images/2405.17894/model.png)

![大型视觉-语言模型面临的白盒多模态越狱挑战](../../../paper_images/2405.17894/failure_case.png)

![大型视觉-语言模型面临的白盒多模态越狱挑战](../../../paper_images/2405.17894/text_loss.png)

![大型视觉-语言模型面临的白盒多模态越狱挑战](../../../paper_images/2405.17894/twoimages.png)

![大型视觉-语言模型面临的白盒多模态越狱挑战](../../../paper_images/2405.17894/ours.png)

[Arxiv](https://arxiv.org/abs/2405.17894)