# 好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法

发布时间：2024年04月02日

`LLM应用` `人工智能` `安全与隐私`

> Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack

# 摘要

> 大型语言模型（LLMs）日益受到青睐，并广泛应用于多个场景。这些模型致力于规避非法或不道德的议题，以减少对负责任AI风险的贡献。然而，一种新兴的“越狱”攻击手法试图突破这一限制。越狱攻击本质上旨在缩小模型潜能与实际行动之间的差异。本文提出了一种创新的越狱技术——Crescendo。与传统方法不同，Crescendo通过多轮对话与模型互动，初始以无害的提示或问题展开，逐步引用模型回应，最终巧妙实现越狱。我们在多个公共系统上测试了Crescendo，包括ChatGPT、Gemini Pro等，结果表明其攻击成功率极高。此外，我们还开发了Crescendomation工具，用以自动化执行Crescendo攻击，实践证明其对最新模型同样有效。

> Large Language Models (LLMs) have risen significantly in popularity and are increasingly being adopted across multiple applications. These LLMs are heavily aligned to resist engaging in illegal or unethical topics as a means to avoid contributing to responsible AI harms. However, a recent line of attacks, known as "jailbreaks", seek to overcome this alignment. Intuitively, jailbreak attacks aim to narrow the gap between what the model can do and what it is willing to do. In this paper, we introduce a novel jailbreak attack called Crescendo. Unlike existing jailbreak methods, Crescendo is a multi-turn jailbreak that interacts with the model in a seemingly benign manner. It begins with a general prompt or question about the task at hand and then gradually escalates the dialogue by referencing the model's replies, progressively leading to a successful jailbreak. We evaluate Crescendo on various public systems, including ChatGPT, Gemini Pro, Gemini-Ultra, LlaMA-2 70b Chat, and Anthropic Chat. Our results demonstrate the strong efficacy of Crescendo, with it achieving high attack success rates across all evaluated models and tasks. Furthermore, we introduce Crescendomation, a tool that automates the Crescendo attack, and our evaluation showcases its effectiveness against state-of-the-art models.

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/MolotovChatGPT.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/MolotovGeminiUltra.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoMississippi.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoHarrypotter.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/synExample.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/sentBySent.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/sentBySentNo4.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x1.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x2.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x3.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x4.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x5.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x6.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x7.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x8.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x9.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/chatGPTStab.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/bardRefuse.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/chatGPTBar.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/bardBarfight.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoGPT4.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoUltra.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoGPT4Gemini.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoClaude.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoClaude3.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoLlama.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/ManifestoHarrypotterProfanity.png)

![好极了，那就来谈谈这个主题：《高潮》—— 一种针对多轮大型语言模型的突破性攻击手法](../../../paper_images/2404.01833/x10.png)

[Arxiv](https://arxiv.org/abs/2404.01833)