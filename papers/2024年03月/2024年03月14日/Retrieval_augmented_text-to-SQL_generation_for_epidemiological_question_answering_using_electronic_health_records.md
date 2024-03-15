# [为解决基于电子健康记录的流行病学问题，我们提出了一种检索增强型文本转SQL生成方法，该方法能够有效利用存储在电子健康记录中的信息，以准确生成满足复杂查询需求的SQL语句。](https://arxiv.org/abs/2403.09226)

发布时间：2024年03月14日

`RAG`

``

`流行病学`

> Retrieval augmented text-to-SQL generation for epidemiological question answering using electronic health records

> EHR和索赔数据蕴含着丰富的现实世界信息，能揭示患者的健康状况和医疗服务利用情况。然而，由于医学术语复杂且需构建复杂的SQL查询，利用这些数据库解答流行病学问题实属不易。为此，我们引入一种创新的端到端方法，将文本转SQL生成技术与检索增强生成（RAG）相结合，用以借助EHR和索赔数据应对流行病学问题。研究表明，我们在文本转SQL流程中融入医学编码环节的做法成效显著，明显优于传统的简单提示输入策略。尽管当前语言模型在无监督应用上精度仍有待提高，但本研究在实际工业背景下的案例证明，RAG为提升它们的能力开辟了一条充满希望的道路。

> Electronic health records (EHR) and claims data are rich sources of real-world data that reflect patient health status and healthcare utilization. Querying these databases to answer epidemiological questions is challenging due to the intricacy of medical terminology and the need for complex SQL queries. Here, we introduce an end-to-end methodology that combines text-to-SQL generation with retrieval augmented generation (RAG) to answer epidemiological questions using EHR and claims data. We show that our approach, which integrates a medical coding step into the text-to-SQL process, significantly improves the performance over simple prompting. Our findings indicate that although current language models are not yet sufficiently accurate for unsupervised use, RAG offers a promising direction for improving their capabilities, as shown in a realistic industry setting.

![为解决基于电子健康记录的流行病学问题，我们提出了一种检索增强型文本转SQL生成方法，该方法能够有效利用存储在电子健康记录中的信息，以准确生成满足复杂查询需求的SQL语句。](../../../paper_images/2403.09226/workflow.png)