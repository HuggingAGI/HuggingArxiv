# IDEATOR：借助 VLMs 来破解 VLMs

发布时间：2024年10月29日

`LLM应用` `计算机视觉` `网络安全`

> IDEATOR: Jailbreaking VLMs Using VLMs

# 摘要

> 随着大型视觉语言模型（VLMs）愈发引人注目，确保其在现实应用中的安全部署已成为关键要点。近来，众多研究聚焦于评估 VLMs 抵御越狱攻击的稳健性。鉴于获取多模态数据面临挑战，当下研究往往基于有害文本数据集生成对抗性或与查询相关的图像来衡量 VLM 的稳健性。然而，如此生成的越狱图像存在一定局限。对抗性图像需要对目标 VLM 进行白盒访问，且相对易防，而与查询相关的图像必须与目标有害内容相关联，限制了其多样性和有效性。本文中，我们提出了一种名为 IDEATOR 的新型越狱方法，它能自主生成恶意的图像 - 文本对用于黑盒越狱攻击。IDEATOR 是基于 VLM 的方法，灵感源于我们的猜测，即 VLM 自身或许是生成越狱提示的强大红队模型。具体来说，IDEATOR 借助 VLM 生成越狱文本，同时运用最先进的扩散模型来创建相应的越狱图像。大量实验表明 IDEATOR 高效且具有可转移性。它成功破解 MiniGPT - 4，成功率达 94％，还能无缝迁移至 LLaVA 和 InstructBLIP，成功率分别高达 82％和 88％。IDEATOR 揭示了 VLMs 此前未被察觉的漏洞，呼吁构建更先进的安全机制。

> As large Vision-Language Models (VLMs) continue to gain prominence, ensuring their safety deployment in real-world applications has become a critical concern. Recently, significant research efforts have focused on evaluating the robustness of VLMs against jailbreak attacks. Due to challenges in obtaining multi-modal data, current studies often assess VLM robustness by generating adversarial or query-relevant images based on harmful text datasets. However, the jailbreak images generated this way exhibit certain limitations. Adversarial images require white-box access to the target VLM and are relatively easy to defend against, while query-relevant images must be linked to the target harmful content, limiting their diversity and effectiveness. In this paper, we propose a novel jailbreak method named IDEATOR, which autonomously generates malicious image-text pairs for black-box jailbreak attacks. IDEATOR is a VLM-based approach inspired by our conjecture that a VLM itself might be a powerful red team model for generating jailbreak prompts. Specifically, IDEATOR employs a VLM to generate jailbreak texts while leveraging a state-of-the-art diffusion model to create corresponding jailbreak images. Extensive experiments demonstrate the high effectiveness and transferability of IDEATOR. It successfully jailbreaks MiniGPT-4 with a 94% success rate and transfers seamlessly to LLaVA and InstructBLIP, achieving high success rates of 82% and 88%, respectively. IDEATOR uncovers previously unrecognized vulnerabilities in VLMs, calling for advanced safety mechanisms.

[Arxiv](https://arxiv.org/abs/2411.00827)