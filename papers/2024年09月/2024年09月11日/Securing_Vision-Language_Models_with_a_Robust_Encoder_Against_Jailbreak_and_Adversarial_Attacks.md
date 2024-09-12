# 用坚固的编码器守护视觉-语言模型，抵御越狱与对抗攻击

发布时间：2024年09月11日

`LLM应用` `人工智能` `网络安全`

> Securing Vision-Language Models with a Robust Encoder Against Jailbreak and Adversarial Attacks

# 摘要

> 大型视觉-语言模型 (LVLMs) 在多模态任务中表现出色，推动了 AI 的进步。然而，这些模型对对抗性攻击，尤其是越狱攻击，仍然脆弱。为此，我们提出了 Sim-CLIP+，一种通过孪生架构微调 CLIP 视觉编码器的新防御机制，增强模型对扰动的抵抗力。Sim-CLIP+ 即插即用，无需修改现有架构，且计算开销极小。实验证明，Sim-CLIP+ 在保持高准确性的同时，显著提升了对多种攻击的鲁棒性。详细信息和代码请访问 https://github.com/speedlab-git/Robust-Encoder-against-Jailbreak-attack.git。

> Large Vision-Language Models (LVLMs), trained on multimodal big datasets, have significantly advanced AI by excelling in vision-language tasks. However, these models remain vulnerable to adversarial attacks, particularly jailbreak attacks, which bypass safety protocols and cause the model to generate misleading or harmful responses. This vulnerability stems from both the inherent susceptibilities of LLMs and the expanded attack surface introduced by the visual modality. We propose Sim-CLIP+, a novel defense mechanism that adversarially fine-tunes the CLIP vision encoder by leveraging a Siamese architecture. This approach maximizes cosine similarity between perturbed and clean samples, facilitating resilience against adversarial manipulations. Sim-CLIP+ offers a plug-and-play solution, allowing seamless integration into existing LVLM architectures as a robust vision encoder. Unlike previous defenses, our method requires no structural modifications to the LVLM and incurs minimal computational overhead. Sim-CLIP+ demonstrates effectiveness against both gradient-based adversarial attacks and various jailbreak techniques. We evaluate Sim-CLIP+ against three distinct jailbreak attack strategies and perform clean evaluations using standard downstream datasets, including COCO for image captioning and OKVQA for visual question answering. Extensive experiments demonstrate that Sim-CLIP+ maintains high clean accuracy while substantially improving robustness against both gradient-based adversarial attacks and jailbreak techniques. Our code and robust vision encoders are available at https://github.com/speedlab-git/Robust-Encoder-against-Jailbreak-attack.git.

[Arxiv](https://arxiv.org/abs/2409.07353)