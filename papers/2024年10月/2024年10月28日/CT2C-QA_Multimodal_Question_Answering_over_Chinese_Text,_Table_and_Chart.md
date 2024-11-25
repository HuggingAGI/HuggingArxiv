# CT2C-QA：针对中文文本、表格和图表的多模态问答

发布时间：2024年10月28日

`Agent` `问答系统` `多模态`

> CT2C-QA: Multimodal Question Answering over Chinese Text, Table and Chart

# 摘要

> 多模态问答（MMQA）意义重大，它能整合来自诸如表格、图表和文本等不同数据形式的见解，从而达成全面的理解和精准的回应。现有的大多数 MMQA 研究仅聚焦于两种模态，像图像-文本问答、表格-文本问答以及图表-文本问答，而针对文本、表格和图表联合分析的研究还相当稀缺。在本文中，我们推出了 C$	ext{T}^2$C-QA，这是一个开创性的基于中文推理的问答数据集，涵盖了从 200 个精选网页精心整理的大量文本、表格和图表。我们的数据集模拟真实网页，能很好地检验模型分析和推理多模态数据的能力，因为问题的答案可能存在于各种模态中，甚至可能根本不存在。此外，我们还提出了 AED（	extbf{分配}、	extbf{专家}和	extbf{决策}），这是一个通过不同代理间的协作部署、信息交互和集体决策来实现的多代理系统。具体而言，分配代理负责挑选和激活专家代理，包括精通文本、表格和图表的那些。决策代理负责依据这些专家代理提供的分析见解给出最终判定。我们进行了全面的分析，将 AED 与包括 GPT-4 在内的各种最先进的 MMQA 模型作比较。实验结果显示，包括 GPT-4 在内的当前方法都还未达到我们数据集设定的标准。

> Multimodal Question Answering (MMQA) is crucial as it enables comprehensive understanding and accurate responses by integrating insights from diverse data representations such as tables, charts, and text. Most existing researches in MMQA only focus on two modalities such as image-text QA, table-text QA and chart-text QA, and there remains a notable scarcity in studies that investigate the joint analysis of text, tables, and charts. In this paper, we present C$\text{T}^2$C-QA, a pioneering Chinese reasoning-based QA dataset that includes an extensive collection of text, tables, and charts, meticulously compiled from 200 selectively sourced webpages. Our dataset simulates real webpages and serves as a great test for the capability of the model to analyze and reason with multimodal data, because the answer to a question could appear in various modalities, or even potentially not exist at all. Additionally, we present AED (\textbf{A}llocating, \textbf{E}xpert and \textbf{D}esicion), a multi-agent system implemented through collaborative deployment, information interaction, and collective decision-making among different agents. Specifically, the Assignment Agent is in charge of selecting and activating expert agents, including those proficient in text, tables, and charts. The Decision Agent bears the responsibility of delivering the final verdict, drawing upon the analytical insights provided by these expert agents. We execute a comprehensive analysis, comparing AED with various state-of-the-art models in MMQA, including GPT-4. The experimental outcomes demonstrate that current methodologies, including GPT-4, are yet to meet the benchmarks set by our dataset.

[Arxiv](https://arxiv.org/abs/2410.21414)