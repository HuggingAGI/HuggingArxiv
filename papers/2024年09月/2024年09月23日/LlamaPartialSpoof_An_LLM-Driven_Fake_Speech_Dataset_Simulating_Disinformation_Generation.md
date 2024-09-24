# LlamaPartialSpoof：一款由 LLM 驱动的假语音数据集，专为模拟虚假信息生成而设计。

发布时间：2024年09月23日

`LLM应用` `语音识别`

> LlamaPartialSpoof: An LLM-Driven Fake Speech Dataset Simulating Disinformation Generation

# 摘要

> 以往的假语音数据集仅从防御者角度出发，未考虑攻击者的多样动机。为此，我们推出了 LlamaPartialSpoof，一个包含 130 小时全假与部分假语音的数据集，利用 LLM 和语音克隆技术，旨在评估对抗措施的鲁棒性。通过分析对攻防双方均有价值的信息，我们揭示了当前系统中的若干关键漏洞，如对特定文本到语音模型或连接方法的偏见，这些漏洞可被利用以提升攻击成功率。实验显示，现有假语音检测系统在应对新场景时表现不佳，最佳等错误率仅为 24.44%。

> Previous fake speech datasets were constructed from a defender's perspective to develop countermeasure (CM) systems without considering diverse motivations of attackers. To better align with real-life scenarios, we created LlamaPartialSpoof, a 130-hour dataset contains both fully and partially fake speech, using a large language model (LLM) and voice cloning technologies to evaluate the robustness of CMs. By examining information valuable to both attackers and defenders, we identify several key vulnerabilities in current CM systems, which can be exploited to enhance attack success rates, including biases toward certain text-to-speech models or concatenation methods. Our experimental results indicate that current fake speech detection system struggle to generalize to unseen scenarios, achieving a best performance of 24.44% equal error rate.

[Arxiv](https://arxiv.org/abs/2409.14743)