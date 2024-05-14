# DoLLM：大型语言模型洞察网络流量，精准侦测地毯式轰炸DDoS攻击在这项研究中，我们将探讨大型语言模型（LLM）如何通过分析网络流量数据来识别和防御地毯式轰炸分布式拒绝服务（DDoS）攻击。通过深入研究LLM在处理复杂网络数据时的能力，我们旨在揭示其对于此类攻击模式的识别和响应机制，从而为网络安全领域提供新的防御策略。

发布时间：2024年05月13日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在网络数据分析和恶意流量检测领域的应用，特别是针对地毯式轰炸攻击的检测。通过提出的DoLLM模型，作者展示了LLMs如何将网络流量转化为语义空间中的令牌嵌入，并用于提升分布式拒绝服务（DDoS）攻击的检测能力。这种应用展示了LLMs在非传统文本处理领域的潜力，因此属于LLM应用分类。` `网络安全` `恶意流量检测`

> DoLLM: How Large Language Models Understanding Network Flow Data to Detect Carpet Bombing DDoS

# 摘要

> 大型语言模型（LLMs）能否理解非语言网络数据并帮助检测未知恶意流量？本文以地毯式轰炸攻击为例，探讨了LLMs在网络领域的应用。地毯式轰炸攻击近年来激增，对网络构成严重威胁，其低速率、多向量的特点挑战了传统防御。我们提出的DoLLM模型，利用开源LLMs，将网络流量转化为语义空间中的令牌嵌入，从而提取流量特征，提升DDoS检测能力。通过公共数据集和ISP真实数据测试，DoLLM在零-shot场景中F1分数提升高达33.3%，在实际ISP数据中至少提升20.6%，展现了其卓越的检测能力。

> It is an interesting question Can and How Large Language Models (LLMs) understand non-language network data, and help us detect unknown malicious flows. This paper takes Carpet Bombing as a case study and shows how to exploit LLMs' powerful capability in the networking area. Carpet Bombing is a new DDoS attack that has dramatically increased in recent years, significantly threatening network infrastructures. It targets multiple victim IPs within subnets, causing congestion on access links and disrupting network services for a vast number of users. Characterized by low-rates, multi-vectors, these attacks challenge traditional DDoS defenses. We propose DoLLM, a DDoS detection model utilizes open-source LLMs as backbone. By reorganizing non-contextual network flows into Flow-Sequences and projecting them into LLMs semantic space as token embeddings, DoLLM leverages LLMs' contextual understanding to extract flow representations in overall network context. The representations are used to improve the DDoS detection performance. We evaluate DoLLM with public datasets CIC-DDoS2019 and real NetFlow trace from Top-3 countrywide ISP. The tests have proven that DoLLM possesses strong detection capabilities. Its F1 score increased by up to 33.3% in zero-shot scenarios and by at least 20.6% in real ISP traces.

[Arxiv](https://arxiv.org/abs/2405.07638)