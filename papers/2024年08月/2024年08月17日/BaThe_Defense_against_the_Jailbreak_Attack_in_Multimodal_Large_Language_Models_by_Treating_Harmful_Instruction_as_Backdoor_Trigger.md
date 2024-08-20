# BaThe：在多模态大型语言模型中，通过将有毒指令视为后门触发点，有效抵御 Jailbreak 攻击。

发布时间：2024年08月17日

`LLM应用` `网络安全` `人工智能`

> BaThe: Defense against the Jailbreak Attack in Multimodal Large Language Models by Treating Harmful Instruction as Backdoor Trigger

# 摘要

> 多模态大型语言模型 (MLLMs) 在多模态任务中表现卓越。然而，图像模态的引入可能为恶意用户提供在图像中植入有害内容的机会，以实施越狱。与基于文本的 LLMs 不同，图像信号的连续性使得恶意注入更为直接。为此，我们提出 $\textbf{BaThe}$ ($\textbf{Ba}$ckdoor $\textbf{T}$rigger S$\textbf{h}$i$\textbf{e}$ld)，一种简洁高效的越狱防御机制。该机制受启发于生成语言模型中的后门攻击研究，通过设置虚拟拒绝提示，嵌入到软文本嵌入中，有效抵御各类越狱攻击，同时对 MLLMs 性能影响甚微。

> Multimodal Large Language Models (MLLMs) have showcased impressive performance in a variety of multimodal tasks. On the other hand, the integration of additional image modality may allow the malicious users to inject harmful content inside the images for jailbreaking. Unlike text-based LLMs, where adversaries need to select discrete tokens to conceal their malicious intent using specific algorithms, the continuous nature of image signals provides a direct opportunity for adversaries to inject harmful intentions. In this work, we propose $\textbf{BaThe}$ ($\textbf{Ba}$ckdoor $\textbf{T}$rigger S$\textbf{h}$i$\textbf{e}$ld), a simple yet effective jailbreak defense mechanism. Our work is motivated by recent research on jailbreak backdoor attack and virtual prompt backdoor attack in generative language models. Jailbreak backdoor attack uses harmful instructions combined with manually crafted strings as triggers to make the backdoored model generate prohibited responses. We assume that harmful instructions can function as triggers, and if we alternatively set rejection responses as the triggered response, the backdoored model then can defend against jailbreak attacks. We achieve this by utilizing virtual rejection prompt, similar to the virtual prompt backdoor attack. We embed the virtual rejection prompt into the soft text embeddings, which we call ``wedge''. Our comprehensive experiments demonstrate that BaThe effectively mitigates various types of jailbreak attacks and is adaptable to defend against unseen attacks, with minimal impact on MLLMs' performance.

[Arxiv](https://arxiv.org/abs/2408.09093)