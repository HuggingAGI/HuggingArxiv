# 采用全同态加密技术，打造了一款用于保密和保护疾病分类的高效工具。

发布时间：2024年05月04日

`分类：LLM应用` `隐私保护`

> Confidential and Protected Disease Classifier using Fully Homomorphic Encryption

# 摘要

> 大型语言模型（LLMs）的广泛应用使得人们开始依赖对话式AI来获取不同领域的初步信息，包括健康咨询和疾病诊断。用户倾向于在咨询医生前，先在ChatGPT或Bard等平台上探索可能的病因。这些平台通过简化诊断流程，减轻医疗工作者的负担，并节省用户的时间与金钱，提供了显著的优势。然而，在线分享个人医疗信息也带来了风险，如恶意平台的威胁和攻击者的潜在监听。为了应对这些隐私问题，我们提出了一个创新的框架，它融合了全同态加密（FHE）和深度学习技术，以构建一个安全私密的诊断系统。该系统模拟与医生的问答互动，采用端到端的加密方式处理加密数据。针对FHE的计算限制，我们对深度神经网络和激活函数进行了适配，并提出了一种加速密文元素求和的新算法。经过一系列严格的实验，我们证实了该方法的有效性，确保了在几乎不损失性能的前提下，实现了高标准的安全性和隐私保护。

> With the rapid surge in the prevalence of Large Language Models (LLMs), individuals are increasingly turning to conversational AI for initial insights across various domains, including health-related inquiries such as disease diagnosis. Many users seek potential causes on platforms like ChatGPT or Bard before consulting a medical professional for their ailment. These platforms offer valuable benefits by streamlining the diagnosis process, alleviating the significant workload of healthcare practitioners, and saving users both time and money by avoiding unnecessary doctor visits. However, Despite the convenience of such platforms, sharing personal medical data online poses risks, including the presence of malicious platforms or potential eavesdropping by attackers. To address privacy concerns, we propose a novel framework combining FHE and Deep Learning for a secure and private diagnosis system. Operating on a question-and-answer-based model akin to an interaction with a medical practitioner, this end-to-end secure system employs Fully Homomorphic Encryption (FHE) to handle encrypted input data. Given FHE's computational constraints, we adapt deep neural networks and activation functions to the encryted domain. Further, we also propose a faster algorithm to compute summation of ciphertext elements. Through rigorous experiments, we demonstrate the efficacy of our approach. The proposed framework achieves strict security and privacy with minimal loss in performance.

![采用全同态加密技术，打造了一款用于保密和保护疾病分类的高效工具。](../../../paper_images/2405.02790/Threat_Secure.jpg)

![采用全同态加密技术，打造了一款用于保密和保护疾病分类的高效工具。](../../../paper_images/2405.02790/FullyConnected_Updated_1.jpg)

![采用全同态加密技术，打造了一款用于保密和保护疾病分类的高效工具。](../../../paper_images/2405.02790/Architecture_Updated_2.jpg)

![采用全同态加密技术，打造了一款用于保密和保护疾病分类的高效工具。](../../../paper_images/2405.02790/poly_reg.jpg)

[Arxiv](https://arxiv.org/abs/2405.02790)