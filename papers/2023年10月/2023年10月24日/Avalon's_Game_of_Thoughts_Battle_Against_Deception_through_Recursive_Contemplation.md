# 阿瓦隆的思维之战：借助递归沉思，与欺骗进行较量。

发布时间：2023年10月24日

`Agent` `人工智能`

> Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation

# 摘要

> 最新的大型语言模型（LLMs）在“LLM作为代理”的研究领域取得了巨大进展。但普遍存在一个假设，即LLMs处理的信息总是真实可信的，这忽略了人类社会和人工智能生成内容中普遍存在的欺诈和误导信息。这种疏忽使得LLMs容易受到恶意操控，可能会产生不良后果。本研究以复杂的阿瓦隆游戏为实验平台，探究LLMs在充满欺骗的环境中的表现。阿瓦隆游戏充满虚假信息，需要玩家运用复杂的逻辑，是一场名副其实的“思维游戏”。受人类玩家在游戏中展现的递归思维和视角转换能力的启发，我们提出了一种新的框架——递归思考（ReCon），旨在提升LLMs识别和抵御欺骗信息的能力。ReCon融合了构思和精炼两个思考阶段；构思阶段产生初步的想法和表达，而精炼阶段则对这些想法和表达进行进一步的打磨。此外，我们还分别在这两个阶段中融入了一阶和二阶的视角转换。具体而言，一阶视角转换使LLM代理能够推测他人的心理状态，而二阶视角转换则涉及理解他人对代理心理状态的看法。ReCon与不同LLMs结合后，在阿瓦隆游戏中的广泛实验结果显示，它能有效帮助LLMs识别并规避欺骗信息，无需额外的训练或数据。最后，我们对ReCon的有效性提供了可能的解释，并探讨了LLMs在安全性、推理能力、语言风格和格式方面的当前限制，这可能为未来的研究提供了宝贵的洞见。

> Recent breakthroughs in large language models (LLMs) have brought remarkable success in the field of LLM-as-Agent. Nevertheless, a prevalent assumption is that the information processed by LLMs is consistently honest, neglecting the pervasive deceptive or misleading information in human society and AI-generated content. This oversight makes LLMs susceptible to malicious manipulations, potentially resulting in detrimental outcomes. This study utilizes the intricate Avalon game as a testbed to explore LLMs' potential in deceptive environments. Avalon, full of misinformation and requiring sophisticated logic, manifests as a "Game-of-Thoughts". Inspired by the efficacy of humans' recursive thinking and perspective-taking in the Avalon game, we introduce a novel framework, Recursive Contemplation (ReCon), to enhance LLMs' ability to identify and counteract deceptive information. ReCon combines formulation and refinement contemplation processes; formulation contemplation produces initial thoughts and speech, while refinement contemplation further polishes them. Additionally, we incorporate first-order and second-order perspective transitions into these processes respectively. Specifically, the first-order allows an LLM agent to infer others' mental states, and the second-order involves understanding how others perceive the agent's mental state. After integrating ReCon with different LLMs, extensive experiment results from the Avalon game indicate its efficacy in aiding LLMs to discern and maneuver around deceptive information without extra fine-tuning and data. Finally, we offer a possible explanation for the efficacy of ReCon and explore the current limitations of LLMs in terms of safety, reasoning, speaking style, and format, potentially furnishing insights for subsequent research.

[Arxiv](https://arxiv.org/abs/2310.01320)