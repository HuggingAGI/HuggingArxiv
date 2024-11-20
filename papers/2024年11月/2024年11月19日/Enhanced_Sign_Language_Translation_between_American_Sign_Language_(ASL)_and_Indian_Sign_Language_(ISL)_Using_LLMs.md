# 借助大型语言模型（LLMs）提升美国手语（ASL）与印度手语（ISL）之间的翻译效果

发布时间：2024年11月19日

`LLM应用`

> Enhanced Sign Language Translation between American Sign Language (ASL) and Indian Sign Language (ISL) Using LLMs

# 摘要

> 我们开展了一项研究，旨在为美式手语使用者与口语及印度手语（ISL）使用者搭建桥梁。该研究助力我们为学习者系统构建了全新框架。借助大型模型的技艺，打造出关键特性，涵盖： - 高效实现这两种手语的实时翻译。让 LLM 的能力用于无缝转译至 ISL。本文呈现了完整的研究及实现过程。系统核心是一条复杂的流水线，首先基于强大的随机森林分类器对美式手语手势进行重新分类与识别。识别美式手语后，将其转化为更易处理的文本。高度发展的自然语言 NLP（自然语言处理）技术大显身手，在 LLM 集成中发挥作用，接着利用 LLMs 将美式手语文本转换为 ISL，为您提供句子或短语的意图。最后一步是把翻译后的文本重新合成为 ISL 手势，借助 RIFE-Net 实现端到端的翻译体验。此框架面临关键挑战，比如自动处理手势的多变性以及克服美式手语与印度手语之间的语言差异。通过自动化翻译流程，我们期望大幅提升手语使用者的便利性。美式手语与印度手语之间的交流鸿沟不再构成阻碍；这一超酷的创新旨在让我们的社区更加紧密相连。而且我们满怀信心地坚信，我们的框架能够在各类手语方言中应用相同的原则。

> We have come up with a research that hopes to provide a bridge between the users of American Sign Language and the users of spoken language and Indian Sign Language (ISL). The research enabled us to create a novel framework that we have developed for Learner Systems. Leveraging art of Large models to create key features including: - Real-time translation between these two sign languages in an efficient manner. Making LLM's capability available for seamless translations to ISL. Here is the full study showing its implementation in this paper. The core of the system is a sophisticated pipeline that begins with reclassification and recognition of ASL gestures based on a strong Random Forest Classifier. By recognizing the ASL, it is translated into text which can be more easily processed. Highly evolved natural language NLP (Natural Language Processing) techniques come in handy as they play a role in our LLM integration where you then use LLMs to be able to convert the ASL text to ISL which provides you with the intent of sentence or phrase. The final step is to synthesize the translated text back into ISL gestures, creating an end-to-end translation experience using RIFE-Net. This framework is tasked with key challenges such as automatically dealing with gesture variability and overcoming the linguistic differences between ASL and ISL. By automating the translation process, we hope to vastly improve accessibility for sign language users. No longer will the communication gap between ASL and ISL create barriers; this totally cool innovation aims to bring our communities closer together. And we believe, with full confidence in our framework, that we're able to apply the same principles across a wide variety of sign language dialects.

[Arxiv](https://arxiv.org/abs/2411.12685)