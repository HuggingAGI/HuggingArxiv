# NLP 引导的合成：从顺序程序迈向分布式程序

发布时间：2024年10月10日

`LLM应用` `软件开发` `数据处理`

> NLP-Guided Synthesis: Transitioning from Sequential Programs to Distributed Programs

# 摘要

> 随着数据处理需求的增长，PySpark 等分布式框架日益流行。然而，将传统顺序代码转换为分布式代码仍是一大挑战，常需专业知识和大量时间。现有工具虽有进步，但在速度、灵活性和适用性上仍有不足。本文介绍的 ROOP 工具，利用 BERT-NLP 模型，自动将 Python 代码转换为 PySpark 代码，简化了分布式计算资源的利用。我们测试了 14 个包含 26 个循环片段的 Python 程序，结果显示 ROOP 几乎完美，成功转换了 25 个片段，且在简单操作上仅需 44 秒。ROOP 还内置测试机制，确保代码功能一致，增加了可靠性。这项研究为自动化编程过渡提供了新途径，使开发过程更便捷高效。

> As the need for large-scale data processing grows, distributed programming frameworks like PySpark have become increasingly popular. However, the task of converting traditional, sequential code to distributed code remains a significant hurdle, often requiring specialized knowledge and substantial time investment. While existing tools have made strides in automating this conversion, they often fall short in terms of speed, flexibility, and overall applicability. In this paper, we introduce ROOP, a groundbreaking tool designed to address these challenges. Utilizing a BERT-based Natural Language Processing (NLP) model, ROOP automates the translation of Python code to its PySpark equivalent, offering a streamlined solution for leveraging distributed computing resources. We evaluated ROOP using a diverse set of 14 Python programs comprising 26 loop fragments. Our results are promising: ROOP achieved a near-perfect translation accuracy rate, successfully converting 25 out of the 26 loop fragments. Notably, for simpler operations, ROOP demonstrated remarkable efficiency, completing translations in as little as 44 seconds. Moreover, ROOP incorporates a built-in testing mechanism to ensure the functional equivalence of the original and translated code, adding an extra layer of reliability. This research opens up new avenues for automating the transition from sequential to distributed programming, making the process more accessible and efficient for developers.

[Arxiv](https://arxiv.org/abs/2410.08005)