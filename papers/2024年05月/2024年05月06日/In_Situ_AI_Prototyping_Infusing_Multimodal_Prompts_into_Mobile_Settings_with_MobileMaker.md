# 现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。

发布时间：2024年05月06日

`LLM应用

这篇论文探讨了多模态大型语言模型（LLMs）在移动AI功能开发中的应用，并提出了一种名为MobileMaker的AI原型设计工具，旨在帮助设计师快速制作和测试移动AI原型，并收集现场用户反馈。这与LLM的应用层面紧密相关，因为它关注的是如何利用LLMs来改善移动AI产品的开发过程和用户体验。因此，它属于LLM应用分类。` `移动应用开发` `人工智能原型设计`

> In Situ AI Prototyping: Infusing Multimodal Prompts into Mobile Settings with MobileMaker

# 摘要

> 多模态大型语言模型（LLMs）的进步，使得通过提示快速开发移动AI功能变得更加容易。尽管现场用户反馈至关重要，但获取移动环境下的早期用户反馈仍是一大挑战。LLMs的广泛性和灵活性要求我们深入理解用户可能提供的各种输入，以及他们对AI行为的期望。为此，我们开发了MobileMaker，一款AI原型设计工具，它让设计师能够快速制作可在设备上测试的移动AI原型，并允许测试者通过自然语言在现场对原型进行即时修改。我们对16名用户进行了研究，比较了使用MobileMaker创建的原型与传统工具（如Figma）的用户反馈。我们发现，MobileMaker能更自然地揭示模型输入的极端情况、AI与用户对任务理解的差异，以及AI遗漏的上下文信号。同时，尽管现场修改功能让用户感觉自己更像是设计过程的积极参与者，但它也可能限制用户的反馈，使其局限于原型工具认为更可行或可实施的变更范围内。

> Recent advances in multimodal large language models (LLMs) have lowered the barriers to rapidly prototyping AI-powered features via prompting, especially for mobile-intended use cases. Despite the value of situated user feedback, the process of soliciting early, mobile-situated user feedback on AI prototypes remains challenging. The broad scope and flexibility of LLMs means that, for a given use-case-specific prototype, there is a crucial need to understand the wide range of in-the-wild input likely to be provided by the user, as well as their in-context expectations of the AI's behavior. To explore the concept of in situ AI prototyping and testing, we created MobileMaker: an AI prototyping tool that enables designers to rapidly create mobile AI prototypes that can be tested on-device, and enables testers to make on-device, in-the-field revisions of the prototype through natural language. In an exploratory study with 16 users, we explored how user feedback on prototypes created with MobileMaker compares to that of existing prototyping tools (e.g., Figma, prompt editors). We found that MobileMaker prototypes enabled more serendipitous discovery of: model input edge cases, discrepancies between AI's and user's in-context interpretation of the task, and contextual signals missed by the AI. Furthermore, we learned that while the ability to make in-the-wild revisions led users to feel more fulfilled as active participants in the design process, it might also constrain their feedback to the subset of changes perceived as more actionable or implementable by the prototyping tool.

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/desktop-2.jpg)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/insitu.jpg)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/ui.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/json-representation.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/study-quant-results.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-john_legend.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-picnic.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-giraffe.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-pirate_ship.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-track.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-eclipse.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-turtle_swimming_in_hawaii.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-hand_stand_walks.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-poker_hand.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-106_6.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-brandy.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-4_5.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-6_5.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/milk.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-107_2.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-3_7.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cropped-5_4.png)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/cherryblossom.jpg)

![现场AI原型制作：借助MobileMaker，将多模态提示注入移动场景，实现智能交互的即时创新。](../../../paper_images/2405.03806/agile-row.png)

[Arxiv](https://arxiv.org/abs/2405.03806)