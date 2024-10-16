# 认知过载攻击：长上下文中的提示注入

发布时间：2024年10月15日

`LLM理论` `人工智能` `网络安全`

> Cognitive Overload Attack:Prompt Injection for Long Context

# 摘要

> 大型语言模型（LLM）在无需重新训练的情况下，已在多个领域展示了卓越的任务执行能力。这种被称为“上下文学习”（ICL）的能力虽然强大，但也使 LLM 面临各种对抗性提示和越狱攻击，这些攻击能操纵安全训练过的 LLM 产生不希望或有害的输出。本文通过类比人类认知中的学习，从认知神经科学的角度提出了对 LLM 中 ICL 的新解释。我们应用了认知负荷理论，并实证验证了 LLM 也会像人类一样遭受认知超载，即处理需求超过模型容量，导致错误。此外，我们展示了攻击者如何通过设计诱导认知超载的提示，利用 ICL 越狱 LLM，破坏其安全机制。我们通过实验验证了 GPT-4、Claude-3.5 Sonnet 等高级模型可被成功越狱，攻击成功率高达 99.99%。这些发现突显了 LLM 的关键漏洞，强调了开发防护措施的紧迫性。我们建议将认知负荷理论融入 LLM 的设计和评估，以更好地预防和减轻对抗性攻击。通过扩展实验范围并揭示 LLM 的 ICL 漏洞，我们旨在推动更安全、更可靠的 AI 系统的发展。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in performing tasks across various domains without needing explicit retraining. This capability, known as In-Context Learning (ICL), while impressive, exposes LLMs to a variety of adversarial prompts and jailbreaks that manipulate safety-trained LLMs into generating undesired or harmful output. In this paper, we propose a novel interpretation of ICL in LLMs through the lens of cognitive neuroscience, by drawing parallels between learning in human cognition with ICL. We applied the principles of Cognitive Load Theory in LLMs and empirically validate that similar to human cognition, LLMs also suffer from cognitive overload a state where the demand on cognitive processing exceeds the available capacity of the model, leading to potential errors. Furthermore, we demonstrated how an attacker can exploit ICL to jailbreak LLMs through deliberately designed prompts that induce cognitive overload on LLMs, thereby compromising the safety mechanisms of LLMs. We empirically validate this threat model by crafting various cognitive overload prompts and show that advanced models such as GPT-4, Claude-3.5 Sonnet, Claude-3 OPUS, Llama-3-70B-Instruct, Gemini-1.0-Pro, and Gemini-1.5-Pro can be successfully jailbroken, with attack success rates of up to 99.99%. Our findings highlight critical vulnerabilities in LLMs and underscore the urgency of developing robust safeguards. We propose integrating insights from cognitive load theory into the design and evaluation of LLMs to better anticipate and mitigate the risks of adversarial attacks. By expanding our experiments to encompass a broader range of models and by highlighting vulnerabilities in LLMs' ICL, we aim to ensure the development of safer and more reliable AI systems.

[Arxiv](https://arxiv.org/abs/2410.11272)