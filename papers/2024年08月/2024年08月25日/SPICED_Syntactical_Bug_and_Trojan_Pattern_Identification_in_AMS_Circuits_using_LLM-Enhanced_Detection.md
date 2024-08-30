# SPICED：借助 LLM 增强检测技术，在 A/MS 电路中精准识别语法错误与特洛伊木马模式。

发布时间：2024年08月25日

`LLM应用` `集成电路`

> SPICED: Syntactical Bug and Trojan Pattern Identification in A/MS Circuits using LLM-Enhanced Detection

# 摘要

> 模拟与混合信号集成电路在现代电子领域举足轻重，涉及信号处理、放大、传感及电源管理等多项关键功能。然而，许多IC公司将生产外包给第三方，这带来了隐秘模拟木马等安全风险。传统检测手段，如电路水印或硬件监控，不仅成本高昂，且难以全面识别木马。为此，我们创新性地提出了SPICED框架，这是一个基于大型语言模型的软件解决方案，无需硬件改动即可精准检测和定位木马。该框架首次运用LLM技术，无需训练，零面积开销，通过链式思维推理和少量示例，有效教授LLM异常检测规则。实验表明，该方法在模拟基准电路上木马覆盖率和真阳性率均高达93%以上，充分证明了LLM在模拟电路中检测与定位问题的强大能力。

> Analog and mixed-signal (A/MS) integrated circuits (ICs) are crucial in modern electronics, playing key roles in signal processing, amplification, sensing, and power management. Many IC companies outsource manufacturing to third-party foundries, creating security risks such as stealthy analog Trojans. Traditional detection methods, including embedding circuit watermarks or conducting hardware-based monitoring, often impose significant area and power overheads, and may not effectively identify all types of Trojans. To address these shortcomings, we propose SPICED, a Large Language Model (LLM)-based framework that operates within the software domain, eliminating the need for hardware modifications for Trojan detection and localization. This is the first work using LLM-aided techniques for detecting and localizing syntactical bugs and analog Trojans in circuit netlists, requiring no explicit training and incurring zero area overhead. Our framework employs chain-of-thought reasoning and few-shot examples to teach anomaly detection rules to LLMs. With the proposed method, we achieve an average Trojan coverage of 93.32% and an average true positive rate of 93.4% in identifying Trojan-impacted nodes for the evaluated analog benchmark circuits. These experimental results validate the effectiveness of LLMs in detecting and locating both syntactical bugs and Trojans within analog netlists.

[Arxiv](https://arxiv.org/abs/2408.16018)