# CodeHalu：在执行驱动验证的助力下，大型语言模型中产生的代码幻觉现象。

发布时间：2024年04月30日

`LLM应用` `自动化编程`

> CodeHalu: Code Hallucinations in LLMs Driven by Execution-based Verification

# 摘要

> 大型语言模型（LLMs）在代码生成领域取得了重大突破，极大地推动了自动化编程的发展，为开发者提供了强大的辅助。然而，这些模型偶尔会产生看似合理但实际并不符合预期或执行错误的代码，这种现象在编程领域被称为“幻觉”。目前，对于LLMs中的代码幻觉现象尚缺乏深入研究。为了深化对此现象的理解，我们首次提出了一种基于执行验证的代码幻觉定义方法，并定义了代码幻觉的概念。我们将代码幻觉归纳为四大类别：映射、命名、资源和逻辑幻觉，每个类别下又细分为多个子类，以便更精准地识别和应对LLMs在代码生成时所面临的挑战。我们还开发了一种动态检测算法，用于系统性地识别代码幻觉，并构建了CodeHalu基准测试，该测试包含699个任务中的8,883个样本，旨在主动监测LLMs编程时的幻觉现象。通过对16个主流LLMs的测试，我们评估了它们在代码生成中的幻觉频率和特点。研究结果显示，不同LLMs在代码生成的准确性和可靠性上存在显著差异，这强调了提升模型性能和改进训练方法的紧迫性，以确保自动生成代码的正确性和安全性。本研究不仅对代码幻觉进行了分类和量化分析，还为未来LLMs在代码生成领域的研究提供了宝贵的洞见。CodeHalu基准测试和相关代码已在 https://github.com/yuchen814/CodeHalu 上公开发布。

> Large Language Models (LLMs) have made significant advancements in the field of code generation, offering unprecedented support for automated programming and assisting developers. However, LLMs sometimes generate code that appears plausible but fails to meet the expected requirements or executes incorrectly. This phenomenon of hallucinations in the coding field has not been explored. To advance the community's understanding and research on code hallucinations in LLMs, we propose a definition method for these hallucinations based on execution verification and introduce the concept of code hallucinations for the first time. We categorize code hallucinations into four main types: mapping, naming, resource, and logic hallucinations, each further divided into different subcategories to better understand and address the unique challenges faced by LLMs during code generation. To systematically evaluate code hallucinations, we propose a dynamic detection algorithm for code hallucinations and construct the CodeHalu benchmark, which includes 8,883 samples from 699 tasks, to actively detect hallucination phenomena in LLMs during programming. We tested 16 popular LLMs on this benchmark to evaluate the frequency and nature of their hallucinations during code generation. The findings reveal significant variations in the accuracy and reliability of LLMs in generating code, highlighting the urgent need to improve models and training methods to ensure the functional correctness and safety of automatically generated code. This study not only classifies and quantifies code hallucinations but also provides insights for future improvements in LLM-based code generation research. The CodeHalu benchmark and code are publicly available at https://github.com/yuchen814/CodeHalu.

[Arxiv](https://arxiv.org/abs/2405.00253)