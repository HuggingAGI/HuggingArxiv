# RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。

发布时间：2024年04月18日

`RAG` `政治话语分析` `信息验证`

> RAGAR, Your Falsehood RADAR: RAG-Augmented Reasoning for Political Fact-Checking using Multimodal Large Language Models

# 摘要

> 面对政治话语中虚假信息的日益严峻挑战，迫切需要更高效的事实核查策略。本研究创新性地将大型语言模型（LLMs）与先进的检索增强生成（RAG）推理技术相结合，提出了两种新颖的方法：RAG 链（CoRAG）和 RAG 树（ToRAG）。这些方法通过基于已有证据推理出接下来需要解答的问题，来处理多模态的声明。与传统的子问题生成和链式思维真实性预测相比，我们的方案在提高真实性预测的准确性和解释生成方面取得了显著进步。通过利用擅长分析文本与图像的多模态 LLMs，本研究进一步提升了自动化系统在识别和抵御虚假信息方面的能力。

> The escalating challenge of misinformation, particularly in the context of political discourse, necessitates advanced solutions for fact-checking. We introduce innovative approaches to enhance the reliability and efficiency of multimodal fact-checking through the integration of Large Language Models (LLMs) with Retrieval-augmented Generation (RAG)- based advanced reasoning techniques. This work proposes two novel methodologies, Chain of RAG (CoRAG) and Tree of RAG (ToRAG). The approaches are designed to handle multimodal claims by reasoning the next questions that need to be answered based on previous evidence. Our approaches improve the accuracy of veracity predictions and the generation of explanations over the traditional fact-checking approach of sub-question generation with chain of thought veracity prediction. By employing multimodal LLMs adept at analyzing both text and images, this research advances the capability of automated systems in identifying and countering misinformation.

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/FrontPagee.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/pipelinefc_new.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/figCoragTorag-2.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/ratings_graph.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/annot.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/Question_Generation.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/QA_Elimination.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/Veracity_Prediction.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/ZSCOTPROMPT.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/CoVeFigure.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/Verification_Prompt.png)

![RAGAR——您的虚假信息侦测器：通过增强的 RAG 推理技术，结合多模态大型语言模型，为政治事实核查提供支持。](../../../paper_images/2404.12065/Correction_Prompt.png)

[Arxiv](https://arxiv.org/abs/2404.12065)