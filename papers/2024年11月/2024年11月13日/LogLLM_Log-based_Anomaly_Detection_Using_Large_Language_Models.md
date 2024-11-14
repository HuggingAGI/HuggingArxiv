# LogLLM：使用大型语言模型进行基于日志的异常检测

发布时间：2024年11月13日

`LLM应用` `异常检测`

> LogLLM: Log-based Anomaly Detection Using Large Language Models

# 摘要

> 软件系统经常在日志中记录重要的运行时信息以帮助进行故障排除。基于日志的异常检测已成为一个关键的研究领域，旨在通过日志数据识别系统问题，最终提高软件系统的可靠性。传统的深度学习方法往往难以捕获嵌入在通常以自然语言组织的日志数据中的语义信息。在本文中，我们提出了 LogLLM，这是一个基于日志的异常检测框架，利用了大型语言模型（LLM）。LogLLM 使用 BERT 从日志消息中提取语义向量，同时利用基于 Transformer 解码器的模型 Llama 对日志序列进行分类。此外，我们引入了一个投影仪来对齐 BERT 和 Llama 的向量表示空间，确保对日志语义有一致的理解。与需要日志解析器提取模板的传统方法不同，LogLLM 使用正则表达式预处理日志消息，简化了整个过程。我们的框架通过一个新颖的三阶段过程进行训练，旨在提高性能和适应性。在四个公共数据集上的实验结果表明，LogLLM 优于最先进的方法。即使在处理不稳定的日志时，它也能有效地捕获日志消息的语义并准确检测异常。

> Software systems often record important runtime information in logs to help with troubleshooting. Log-based anomaly detection has become a key research area that aims to identify system issues through log data, ultimately enhancing the reliability of software systems. Traditional deep learning methods often struggle to capture the semantic information embedded in log data, which is typically organized in natural language. In this paper, we propose LogLLM, a log-based anomaly detection framework that leverages large language models (LLMs). LogLLM employs BERT for extracting semantic vectors from log messages, while utilizing Llama, a transformer decoder-based model, for classifying log sequences. Additionally, we introduce a projector to align the vector representation spaces of BERT and Llama, ensuring a cohesive understanding of log semantics. Unlike conventional methods that require log parsers to extract templates, LogLLM preprocesses log messages with regular expressions, streamlining the entire process. Our framework is trained through a novel three-stage procedure designed to enhance performance and adaptability. Experimental results across four public datasets demonstrate that LogLLM outperforms state-of-the-art methods. Even when handling unstable logs, it effectively captures the semantic meaning of log messages and detects anomalies accurately.

[Arxiv](https://arxiv.org/abs/2411.08561)