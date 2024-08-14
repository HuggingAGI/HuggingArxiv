# Casper：网络大型语言模型中保护用户隐私的提示净化技术

发布时间：2024年08月13日

`LLM应用` `互联网` `隐私保护`

> Casper: Prompt Sanitization for Protecting User Privacy in Web-Based Large Language Models

# 摘要

> Web大型语言模型（LLM）服务已深入我们的互联网生活，第三方插件通过接入现实数据与服务，进一步增强了其功能。然而，这些服务及其插件的隐私影响尚不明确。敏感提示数据在云端被存储、处理及共享。为此，我们提出Casper技术，通过在发送前检测并移除敏感信息，保护用户隐私。Casper作为浏览器扩展，在用户设备上运行，无需改动在线LLM服务。其核心机制包含三层：基于规则的过滤、机器学习命名实体识别及浏览器本地LLM主题识别。实验显示，Casper能高效过滤个人身份信息与敏感主题，准确率高达98.5%与89.9%。

> Web-based Large Language Model (LLM) services have been widely adopted and have become an integral part of our Internet experience. Third-party plugins enhance the functionalities of LLM by enabling access to real-world data and services. However, the privacy consequences associated with these services and their third-party plugins are not well understood. Sensitive prompt data are stored, processed, and shared by cloud-based LLM providers and third-party plugins. In this paper, we propose Casper, a prompt sanitization technique that aims to protect user privacy by detecting and removing sensitive information from user inputs before sending them to LLM services. Casper runs entirely on the user's device as a browser extension and does not require any changes to the online LLM services. At the core of Casper is a three-layered sanitization mechanism consisting of a rule-based filter, a Machine Learning (ML)-based named entity recognizer, and a browser-based local LLM topic identifier. We evaluate Casper on a dataset of 4000 synthesized prompts and show that it can effectively filter out Personal Identifiable Information (PII) and privacy-sensitive topics with high accuracy, at 98.5% and 89.9%, respectively.

[Arxiv](https://arxiv.org/abs/2408.07004)