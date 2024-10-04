# Zodiac：一款心脏病专家级别的多智能体诊断 LLM 框架

发布时间：2024年10月02日

`LLM应用` `心脏病学`

> Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics

# 摘要

> 大型语言模型 (LLM) 在医疗领域取得了显著进展，但在特定临床实践中的专业性仍有待提升，限制了其在实际诊断中的应用。为此，我们推出了 ZODIAC，一个由 LLM 驱动的心脏病专家级框架，旨在提升 LLM 在心脏病诊断中的应用。ZODIAC 通过提取患者数据中的临床特征、检测心律失常并生成初步报告，协助心脏病专家进行诊断。为确保专业性，ZODIAC 采用多代理协作框架，并使用真实患者数据进行微调。经过独立心脏病专家的严格验证，ZODIAC 在多个指标上表现优异，超越了包括 GPT-4o、Llama-3.1-405B 和 Gemini-pro 在内的领先模型，以及 Microsoft 的 BioGPT。ZODIAC 的成功应用，如集成到心电图设备中，展示了 LLM 在医疗领域的巨大潜力，并推动了医疗设备软件 (SaMD) 的发展。

> Large language models (LLMs) have demonstrated remarkable progress in healthcare. However, a significant gap remains regarding LLMs' professionalism in domain-specific clinical practices, limiting their application in real-world diagnostics. In this work, we introduce ZODIAC, an LLM-powered framework with cardiologist-level professionalism designed to engage LLMs in cardiological diagnostics. ZODIAC assists cardiologists by extracting clinically relevant characteristics from patient data, detecting significant arrhythmias, and generating preliminary reports for the review and refinement by cardiologists. To achieve cardiologist-level professionalism, ZODIAC is built on a multi-agent collaboration framework, enabling the processing of patient data across multiple modalities. Each LLM agent is fine-tuned using real-world patient data adjudicated by cardiologists, reinforcing the model's professionalism. ZODIAC undergoes rigorous clinical validation with independent cardiologists, evaluated across eight metrics that measure clinical effectiveness and address security concerns. Results show that ZODIAC outperforms industry-leading models, including OpenAI's GPT-4o, Meta's Llama-3.1-405B, and Google's Gemini-pro, as well as medical-specialist LLMs like Microsoft's BioGPT. ZODIAC demonstrates the transformative potential of specialized LLMs in healthcare by delivering domain-specific solutions that meet the stringent demands of medical practice. Notably, ZODIAC has been successfully integrated into electrocardiography (ECG) devices, exemplifying the growing trend of embedding LLMs into Software-as-Medical-Device (SaMD).

[Arxiv](https://arxiv.org/abs/2410.02026)