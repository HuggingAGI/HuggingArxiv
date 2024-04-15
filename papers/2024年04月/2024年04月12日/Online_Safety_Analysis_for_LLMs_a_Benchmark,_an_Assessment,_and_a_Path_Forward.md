# 针对大型语言模型的网络安全评估：建立行业标准，进行全面审视，并规划未来发展方向。

发布时间：2024年04月12日

`LLM理论` `人工智能安全` `在线安全分析`

> Online Safety Analysis for LLMs: a Benchmark, an Assessment, and a Path Forward

# 摘要

> 大型语言模型（LLMs）虽广泛应用于多个领域，但其可解释性不足，引发了对其安全性的多方面担忧，如真实性、鲁棒性和公平性。最新研究致力于开发LLMs的质量保障方法，如离线检测和不确定性估计等。然而，这些方法多聚焦于生成后分析，忽略了生成过程中的在线安全分析。为此，本研究对LLMs的在线安全分析方法进行了全面评估，首先通过试点研究确认了在生成初期检测不安全内容的可行性。接着，我们创建了首个公共在线安全分析基准，涵盖了多种方法、模型、任务、数据集和评估指标。通过这一基准，我们深入分析了开源和闭源LLMs上现行在线安全分析方法的表现，发现了各自优缺点，并为不同应用场景和任务需求提供了选择最合适方法的洞见。此外，我们还探讨了混合方法的潜力，即融合多种方法以得出综合安全结论，旨在提升LLMs在线安全分析的效果。我们的研究成果为LLMs的质量保障方法开辟了新方向，有助于其在各领域的可靠应用。

> While Large Language Models (LLMs) have seen widespread applications across numerous fields, their limited interpretability poses concerns regarding their safe operations from multiple aspects, e.g., truthfulness, robustness, and fairness. Recent research has started developing quality assurance methods for LLMs, introducing techniques such as offline detector-based or uncertainty estimation methods. However, these approaches predominantly concentrate on post-generation analysis, leaving the online safety analysis for LLMs during the generation phase an unexplored area. To bridge this gap, we conduct in this work a comprehensive evaluation of the effectiveness of existing online safety analysis methods on LLMs. We begin with a pilot study that validates the feasibility of detecting unsafe outputs in the early generation process. Following this, we establish the first publicly available benchmark of online safety analysis for LLMs, including a broad spectrum of methods, models, tasks, datasets, and evaluation metrics. Utilizing this benchmark, we extensively analyze the performance of state-of-the-art online safety analysis methods on both open-source and closed-source LLMs. This analysis reveals the strengths and weaknesses of individual methods and offers valuable insights into selecting the most appropriate method based on specific application scenarios and task requirements. Furthermore, we also explore the potential of using hybridization methods, i.e., combining multiple methods to derive a collective safety conclusion, to enhance the efficacy of online safety analysis for LLMs. Our findings indicate a promising direction for the development of innovative and trustworthy quality assurance methodologies for LLMs, facilitating their reliable deployments across diverse domains.

[Arxiv](https://arxiv.org/abs/2404.08517)