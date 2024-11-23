# 对大型语言模型进行微调以用于 DGA 和 DNS 数据泄露检测

发布时间：2024年10月29日

`LLM应用` `网络安全` `恶意软件检测`

> Fine-tuning Large Language Models for DGA and DNS Exfiltration Detection

# 摘要

> 领域生成算法（DGA）是恶意软件用来动态生成看似随机的域名以与命令和控制（C＆C）服务器通信的恶意手段。鉴于DGA域名生成迅速且简单，检测方法必须高效精准才能奏效。大型语言模型（LLM）在实时检测任务中已展现出出色能力，成为检测DGA的理想之选。我们的工作证实了微调后的LLM在检测DGA和DNS数据泄露攻击方面的有效性。我们开发了LLM模型，并运用涵盖59种不同真实世界DGA恶意软件家族和正常域名数据的多样化数据集进行了全面评估。我们的LLM模型在检测未知DGA方面表现尤为突出，显著优于传统自然语言处理技术。我们还在DNS数据泄露数据集上对其性能进行了评估，表明其在加强网络安全措施方面行之有效。据我们所知，这是首次将LLM实际应用于DGA和DNS数据泄露检测的工作。

> Domain Generation Algorithms (DGAs) are malicious techniques used by malware to dynamically generate seemingly random domain names for communication with Command & Control (C&C) servers. Due to the fast and simple generation of DGA domains, detection methods must be highly efficient and precise to be effective. Large Language Models (LLMs) have demonstrated their proficiency in real-time detection tasks, making them ideal candidates for detecting DGAs. Our work validates the effectiveness of fine-tuned LLMs for detecting DGAs and DNS exfiltration attacks. We developed LLM models and conducted comprehensive evaluation using a diverse dataset comprising 59 distinct real-world DGA malware families and normal domain data. Our LLM model significantly outperformed traditional natural language processing techniques, especially in detecting unknown DGAs. We also evaluated its performance on DNS exfiltration datasets, demonstrating its effectiveness in enhancing cybersecurity measures. To the best of our knowledge, this is the first work that empirically applies LLMs for DGA and DNS exfiltration detection.

[Arxiv](https://arxiv.org/abs/2410.21723)