# 不仅限于检测，我们利用大型语言模型来预测物联网网络中的网络攻击。

发布时间：2024年08月26日

`LLM应用` `物联网` `网络安全`

> Beyond Detection: Leveraging Large Language Models for Cyber Attack Prediction in IoT Networks

# 摘要

> 近年来，物联网（IoT）设备频繁成为大规模网络攻击的目标，且随着IoT技术的普及，这一趋势愈发严峻。尽管现有的入侵检测系统在攻击检测上投入了大量努力，但它们大多仍处于被动响应状态，仅针对特定模式或异常行为作出反应。为此，我们提出了一种前瞻性的解决方案，旨在在恶意活动造成损害之前进行预测和缓解。本文介绍了一种创新的网络入侵预测框架，该框架融合了大型语言模型（LLM）和长短期记忆（LSTM）网络。框架中，两个LLM模型通过反馈循环协同工作：一个微调的GPT模型负责预测网络流量，另一个微调的BERT模型则评估这些流量。随后，LSTM分类器在这些评估结果中识别出恶意数据包。在CICIoT2023数据集上的测试表明，我们的框架在预测准确性上取得了显著进步，总体准确率高达98%，为应对IoT网络安全挑战提供了强有力的技术支持。

> In recent years, numerous large-scale cyberattacks have exploited Internet of Things (IoT) devices, a phenomenon that is expected to escalate with the continuing proliferation of IoT technology. Despite considerable efforts in attack detection, intrusion detection systems remain mostly reactive, responding to specific patterns or observed anomalies. This work proposes a proactive approach to anticipate and mitigate malicious activities before they cause damage. This paper proposes a novel network intrusion prediction framework that combines Large Language Models (LLMs) with Long Short Term Memory (LSTM) networks. The framework incorporates two LLMs in a feedback loop: a fine-tuned Generative Pre-trained Transformer (GPT) model for predicting network traffic and a fine-tuned Bidirectional Encoder Representations from Transformers (BERT) for evaluating the predicted traffic. The LSTM classifier model then identifies malicious packets among these predictions. Our framework, evaluated on the CICIoT2023 IoT attack dataset, demonstrates a significant improvement in predictive capabilities, achieving an overall accuracy of 98%, offering a robust solution to IoT cybersecurity challenges.

[Arxiv](https://arxiv.org/abs/2408.14045)