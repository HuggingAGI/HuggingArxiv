# 物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。

发布时间：2024年04月19日

`分类：LLM应用` `自动驾驶`

> Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models

# 摘要

> 视觉大型语言模型（VLMs）在自动驾驶技术上展现出广阔的应用潜力。尽管这些模型能够理解复杂环境并做出决策，但它们的融入也给自动驾驶系统带来了安全挑战。本文介绍了BadVLMDriver，一种针对自动驾驶VLMs的首创物理后门攻击手段，它通过日常物品如红色气球触发不安全操作，如急加速，暴露了自动驾驶安全性的重大威胁。我们构建了一个自动化流程，通过自然语言指令生成含有恶意行为的后门训练样本，提升了攻击的隐蔽性和场景适应性。在对两种主流VLMs、五种触发物和两种恶意行为的广泛测试中，BadVLMDriver在行人持红气球时诱发急加速的成功率达92%，从而不仅揭示了关键安全风险，也凸显了开发强大防御机制以抵御自动驾驶技术潜在威胁的迫切性。

> Vision-Large-Language-models(VLMs) have great application prospects in autonomous driving. Despite the ability of VLMs to comprehend and make decisions in complex scenarios, their integration into safety-critical autonomous driving systems poses serious security risks. In this paper, we propose BadVLMDriver, the first backdoor attack against VLMs for autonomous driving that can be launched in practice using physical objects. Unlike existing backdoor attacks against VLMs that rely on digital modifications, BadVLMDriver uses common physical items, such as a red balloon, to induce unsafe actions like sudden acceleration, highlighting a significant real-world threat to autonomous vehicle safety. To execute BadVLMDriver, we develop an automated pipeline utilizing natural language instructions to generate backdoor training samples with embedded malicious behaviors. This approach allows for flexible trigger and behavior selection, enhancing the stealth and practicality of the attack in diverse scenarios. We conduct extensive experiments to evaluate BadVLMDriver for two representative VLMs, five different trigger objects, and two types of malicious backdoor behaviors. BadVLMDriver achieves a 92% attack success rate in inducing a sudden acceleration when coming across a pedestrian holding a red balloon. Thus, BadVLMDriver not only demonstrates a critical security risk but also emphasizes the urgent need for developing robust defense mechanisms to protect against such vulnerabilities in autonomous driving technologies.

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/x1.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/x2.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/x3.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/x4.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/x5.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/trigger_compare.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/defense.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/blending_football_brake.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/blending_football_accelerate.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/blending_balloon_brake.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/blending_balloon_accelerate.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/supp1.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/supp2.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/supp3.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/edit.png)

![物理后门攻击可能对采用视觉技术的大规模语言模型的驾驶安全构成威胁。](../../../paper_images/2404.12916/x6.png)

[Arxiv](https://arxiv.org/abs/2404.12916)