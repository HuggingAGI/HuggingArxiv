# 借助 LLM 的检索增强推理，自动驾驶车辆在遵循法规的同时，实现了可解释的决策过程。

发布时间：2024年10月07日

`Agent` `自动驾驶` `交通管理`

> Driving with Regulation: Interpretable Decision-Making for Autonomous Vehicles with Retrieval-Augmented Reasoning via LLM

# 摘要

> 我们提出了一种可解释的自动驾驶决策框架，全面整合了交通法规、规范和安全指南，并能无缝适应不同地区。针对传统规则方法的局限，我们开发了基于 RAG 的 TRR 代理，自动检索相关交通规则。考虑到规则的复杂性，我们设计了由 LLM 驱动的推理模块，解释规则并评估行动的合规性和安全性。该框架不仅在各种场景中表现出色，还能轻松适应不同地区，增强了透明度和可靠性。

> This work presents an interpretable decision-making framework for autonomous vehicles that integrates traffic regulations, norms, and safety guidelines comprehensively and enables seamless adaptation to different regions. While traditional rule-based methods struggle to incorporate the full scope of traffic rules, we develop a Traffic Regulation Retrieval (TRR) Agent based on Retrieval-Augmented Generation (RAG) to automatically retrieve relevant traffic rules and guidelines from extensive regulation documents and relevant records based on the ego vehicle's situation. Given the semantic complexity of the retrieved rules, we also design a reasoning module powered by a Large Language Model (LLM) to interpret these rules, differentiate between mandatory rules and safety guidelines, and assess actions on legal compliance and safety. Additionally, the reasoning is designed to be interpretable, enhancing both transparency and reliability. The framework demonstrates robust performance on both hypothesized and real-world cases across diverse scenarios, along with the ability to adapt to different regions with ease.

[Arxiv](https://arxiv.org/abs/2410.04759)