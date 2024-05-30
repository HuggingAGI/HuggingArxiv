# GPT-4o遭遇语音越狱攻击挑战

发布时间：2024年05月29日

`Agent

这篇论文主要探讨了针对GPT-4o语音模式的越狱攻击，并提出了一种新型的语音越狱攻击方法VoiceJailbreak。这种攻击方法利用虚构故事来生成有效的越狱提示，从而提高攻击成功率。论文的研究重点在于评估和改进针对特定AI助手的攻击策略，这属于Agent相关的研究范畴，因为Agent在这里指的是具有特定行为和响应机制的人工智能助手。因此，这篇论文应归类于Agent。` `人工智能`

> Voice Jailbreak Attacks Against GPT-4o

# 摘要

> 人工智能助手的概念已从科幻跃入现实，GPT-4o作为最新的多模态大型语言模型，跨越音频、视觉和文本，让人机交互更加自然，科幻与现实的界限愈发模糊。然而，GPT-4o的语音模式也可能成为新的攻击目标。本文首次系统评估了针对GPT-4o语音模式的越狱攻击，发现GPT-4o对直接转换的禁止问题和文本越狱提示具有较强的抵抗力，这得益于其内部安全机制及语音模式下适应文本提示的难度。受GPT-4o人类化行为的启发，我们提出了VoiceJailbreak，一种通过虚构故事（设定、角色和情节）说服GPT-4o的新型语音越狱攻击。该攻击能生成简单而有效的越狱提示，将六种禁止场景下的平均攻击成功率从0.033大幅提升至0.778。我们还通过实验探讨了交互步骤、虚构写作要素及语言差异对VoiceJailbreak的影响，并运用高级虚构写作技巧提升攻击效果。我们期望这项研究能助力研究界打造更安全、更规范的多模态大型语言模型。

> Recently, the concept of artificial assistants has evolved from science fiction into real-world applications. GPT-4o, the newest multimodal large language model (MLLM) across audio, vision, and text, has further blurred the line between fiction and reality by enabling more natural human-computer interactions. However, the advent of GPT-4o's voice mode may also introduce a new attack surface. In this paper, we present the first systematic measurement of jailbreak attacks against the voice mode of GPT-4o. We show that GPT-4o demonstrates good resistance to forbidden questions and text jailbreak prompts when directly transferring them to voice mode. This resistance is primarily due to GPT-4o's internal safeguards and the difficulty of adapting text jailbreak prompts to voice mode. Inspired by GPT-4o's human-like behaviors, we propose VoiceJailbreak, a novel voice jailbreak attack that humanizes GPT-4o and attempts to persuade it through fictional storytelling (setting, character, and plot). VoiceJailbreak is capable of generating simple, audible, yet effective jailbreak prompts, which significantly increases the average attack success rate (ASR) from 0.033 to 0.778 in six forbidden scenarios. We also conduct extensive experiments to explore the impacts of interaction steps, key elements of fictional writing, and different languages on VoiceJailbreak's effectiveness and further enhance the attack performance with advanced fictional writing techniques. We hope our study can assist the research community in building more secure and well-regulated MLLMs.

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x1.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x2.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x3.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x4.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x5.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x6.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x7.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x8.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x9.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x10.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x11.png)

![GPT-4o遭遇语音越狱攻击挑战](../../../paper_images/2405.19103/x12.png)

[Arxiv](https://arxiv.org/abs/2405.19103)