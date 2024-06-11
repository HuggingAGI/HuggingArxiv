# MASSW：助力科学工作流程，AI新数据集与基准任务登场

发布时间：2024年06月10日

`LLM应用

这篇论文介绍了MASSW数据集，该数据集利用大型语言模型（LLMs）从大量计算机科学文献中提取结构化摘要，以支持科学流程的分析和优化。这种方法直接应用了LLMs来处理和分析大规模文本数据，以辅助科学研究和创新，因此属于LLM应用类别。` `计算机科学` `科学研究`

> MASSW: A New Dataset and Benchmark Tasks for AI-Assisted Scientific Workflows

# 摘要

> 科学创新依赖于精细的流程，包括文献分析、创意生成、想法验证、结果解读及激发后续研究等关键环节。然而，这些流程的记录往往散布在大量无序的科学出版物中，给人类研究者和AI系统带来了探索科学创新领域的挑战。为此，我们推出了MASSW，一个涵盖科学流程多方面摘要的全面文本数据集。MASSW收录了过去50年17个顶尖计算机科学会议的152,000余篇同行评审文献。借助大型语言模型（LLMs），我们从中提炼出五个核心要素——背景、关键思想、方法、成果及潜在影响，与研究流程的五大步骤相呼应。这些结构化的摘要极大地便利了后续任务和分析。通过与人工标注的对比，我们验证了LLM提取摘要的准确性。MASSW通过多个创新的机器学习任务展示了其价值，这些任务可利用此数据集进行基准测试，为科学流程提供多样化的预测和建议。MASSW为研究人员提供了优化科学流程、推动领域内科学创新的新AI方法的开发和测试平台。数据集已公开，详情请访问\url{https://github.com/xingjian-zhang/massw}。

> Scientific innovation relies on detailed workflows, which include critical steps such as analyzing literature, generating ideas, validating these ideas, interpreting results, and inspiring follow-up research. However, scientific publications that document these workflows are extensive and unstructured. This makes it difficult for both human researchers and AI systems to effectively navigate and explore the space of scientific innovation. To address this issue, we introduce MASSW, a comprehensive text dataset on Multi-Aspect Summarization of Scientific Workflows. MASSW includes more than 152,000 peer-reviewed publications from 17 leading computer science conferences spanning the past 50 years. Using Large Language Models (LLMs), we automatically extract five core aspects from these publications -- context, key idea, method, outcome, and projected impact -- which correspond to five key steps in the research workflow. These structured summaries facilitate a variety of downstream tasks and analyses. The quality of the LLM-extracted summaries is validated by comparing them with human annotations. We demonstrate the utility of MASSW through multiple novel machine-learning tasks that can be benchmarked using this new dataset, which make various types of predictions and recommendations along the scientific workflow. MASSW holds significant potential for researchers to create and benchmark new AI methods for optimizing scientific workflows and fostering scientific innovation in the field. Our dataset is openly available at \url{https://github.com/xingjian-zhang/massw}.

[Arxiv](https://arxiv.org/abs/2406.06357)