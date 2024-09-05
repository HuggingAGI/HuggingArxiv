# PUB：大型语言模型在合成视觉数据解释中的图表理解评估基准与数据集

发布时间：2024年09月04日

`LLM应用` `数据分析` `商业智能`

> PUB: Plot Understanding Benchmark and Dataset for Evaluating Large Language Models on Synthetic Visual Data Interpretation

# 摘要

> 大型语言模型（LLM）在解读数据视觉呈现方面的能力，对于其在数据分析和决策支持中的应用至关重要。本文推出了一款创新的综合数据集，旨在测试LLM对多种数据可视化形式的解读能力，涵盖时间序列、直方图、小提琴图、箱线图及聚类图等。该数据集通过精确控制的参数生成，确保了现实场景的全面覆盖。我们利用与图像中视觉数据相关的问题的多模态文本提示，对ChatGPT和Gemini等顶尖模型进行了基准测试，以评估其理解和解释的准确性。  为保证数据集的新颖性和无偏性，我们的基准数据集采用自动生成方式，确保模型未曾接触过。这种方法有效排除了预学习的可能性，实现了对模型真实解读能力的公正评估。此外，我们引入了定量评估指标，为模型的性能提供了全面而有力的评价工具。  通过此数据集对多个领先LLM的基准测试，我们揭示了它们在解读不同类型视觉数据时的优势与不足。这些发现不仅为当前LLM的能力提供了深刻见解，也为未来的改进指明了方向。本研究为提升语言模型视觉解读能力的未来研究奠定了坚实基础，预示着这些模型在自动化数据分析、科学研究、教育工具及商业智能等领域的广泛应用潜力。

> The ability of large language models (LLMs) to interpret visual representations of data is crucial for advancing their application in data analysis and decision-making processes. This paper presents a novel synthetic dataset designed to evaluate the proficiency of LLMs in interpreting various forms of data visualizations, including plots like time series, histograms, violins, boxplots, and clusters. Our dataset is generated using controlled parameters to ensure comprehensive coverage of potential real-world scenarios. We employ multimodal text prompts with questions related to visual data in images to benchmark several state-of-the-art models like ChatGPT or Gemini, assessing their understanding and interpretative accuracy.
  To ensure data integrity, our benchmark dataset is generated automatically, making it entirely new and free from prior exposure to the models being tested. This strategy allows us to evaluate the models' ability to truly interpret and understand the data, eliminating possibility of pre-learned responses, and allowing for an unbiased evaluation of the models' capabilities. We also introduce quantitative metrics to assess the performance of the models, providing a robust and comprehensive evaluation tool.
  Benchmarking several state-of-the-art LLMs with this dataset reveals varying degrees of success, highlighting specific strengths and weaknesses in interpreting diverse types of visual data. The results provide valuable insights into the current capabilities of LLMs and identify key areas for improvement. This work establishes a foundational benchmark for future research and development aimed at enhancing the visual interpretative abilities of language models. In the future, improved LLMs with robust visual interpretation skills can significantly aid in automated data analysis, scientific research, educational tools, and business intelligence applications.

[Arxiv](https://arxiv.org/abs/2409.02617)