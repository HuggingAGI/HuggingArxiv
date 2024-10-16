# AdvBDGen：一款针对 LLM 对齐的对抗性强化提示特定模糊后门生成器

发布时间：2024年10月15日

`LLM应用` `网络安全` `人工智能`

> AdvBDGen: Adversarially Fortified Prompt-Specific Fuzzy Backdoor Generator Against LLM Alignment

# 摘要

> 随着 RLHF 在 LLM 调整中的普及，对齐过程中安装后门的风险也随之上升，可能导致意外有害行为。现有后门触发器多为固定词语模式，易在数据清洗中被检测并移除。我们探索了使用特定提示的释义作为后门触发器，增强了其在 LLM 对齐过程中的隐蔽性和抗移除性。我们提出了 AdvBDGen，一个对抗性强化生成微调框架，自动生成有效、隐蔽且可跨模型转移的特定提示后门。AdvBDGen 通过生成器-判别器对，确保后门的可安装性和隐蔽性，仅需 3% 的微调数据即可设计和安装复杂触发器。这些后门在推理过程中可破解 LLM，抗扰动稳定性优于传统触发器，且更难移除。这些发现凸显了研究界迫切需要开发更强大的防御措施，以应对 LLM 对齐中的对抗性后门威胁。

> With the growing adoption of reinforcement learning with human feedback (RLHF) for aligning large language models (LLMs), the risk of backdoor installation during alignment has increased, leading to unintended and harmful behaviors. Existing backdoor triggers are typically limited to fixed word patterns, making them detectable during data cleaning and easily removable post-poisoning. In this work, we explore the use of prompt-specific paraphrases as backdoor triggers, enhancing their stealth and resistance to removal during LLM alignment. We propose AdvBDGen, an adversarially fortified generative fine-tuning framework that automatically generates prompt-specific backdoors that are effective, stealthy, and transferable across models. AdvBDGen employs a generator-discriminator pair, fortified by an adversary, to ensure the installability and stealthiness of backdoors. It enables the crafting and successful installation of complex triggers using as little as 3% of the fine-tuning data. Once installed, these backdoors can jailbreak LLMs during inference, demonstrate improved stability against perturbations compared to traditional constant triggers, and are more challenging to remove. These findings underscore an urgent need for the research community to develop more robust defenses against adversarial backdoor threats in LLM alignment.

[Arxiv](https://arxiv.org/abs/2410.11283)