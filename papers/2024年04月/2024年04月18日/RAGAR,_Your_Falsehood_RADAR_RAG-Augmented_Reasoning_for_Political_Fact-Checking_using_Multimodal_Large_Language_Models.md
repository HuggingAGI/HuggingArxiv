# RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。

发布时间：2024年04月18日

`分类：RAG` `信息安全`

> RAGAR, Your Falsehood RADAR: RAG-Augmented Reasoning for Political Fact-Checking using Multimodal Large Language Models

# 摘要

> 面对政治话语中日益严峻的虚假信息挑战，迫切需要更高效的事实核查手段。本文提出了结合大型语言模型（LLMs）和检索增强生成（RAG）技术的创新方法，以提升多模态事实核查的准确性与效率。我们设计了两种新方法：RAG 链（CoRAG）和 RAG 树（ToRAG），它们能够通过分析先前证据来推理出接下来需要解答的问题，从而处理多模态的声明。与传统的子问题生成和链式思维真实性预测相比，这些方法在提高真实性预测的准确度和解释生成的质量方面取得了显著进步。本研究通过运用能够同时分析文本和图像的多模态 LLMs，极大地增强了自动化系统识别和抵御虚假信息的能力。

> The escalating challenge of misinformation, particularly in the context of political discourse, necessitates advanced solutions for fact-checking. We introduce innovative approaches to enhance the reliability and efficiency of multimodal fact-checking through the integration of Large Language Models (LLMs) with Retrieval-augmented Generation (RAG)- based advanced reasoning techniques. This work proposes two novel methodologies, Chain of RAG (CoRAG) and Tree of RAG (ToRAG). The approaches are designed to handle multimodal claims by reasoning the next questions that need to be answered based on previous evidence. Our approaches improve the accuracy of veracity predictions and the generation of explanations over the traditional fact-checking approach of sub-question generation with chain of thought veracity prediction. By employing multimodal LLMs adept at analyzing both text and images, this research advances the capability of automated systems in identifying and countering misinformation.

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/FrontPagee.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/pipelinefc_new.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/figCoragTorag-2.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/ratings_graph.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/annot.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/Question_Generation.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/QA_Elimination.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/Veracity_Prediction.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/ZSCOTPROMPT.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/CoVeFigure.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/Verification_Prompt.png)

![RAGAR，您的虚假信息侦测器：一种利用多模态大型语言模型增强推理能力，专为政治事实核查而设计的方法。](../../../paper_images/2404.12065/Correction_Prompt.png)

[Arxiv](https://arxiv.org/abs/2404.12065)