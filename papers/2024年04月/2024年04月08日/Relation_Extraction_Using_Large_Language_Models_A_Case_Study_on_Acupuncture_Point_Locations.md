# 通过大型语言模型进行关系提取研究：以针灸穴位位置为例

发布时间：2024年04月08日

`LLM应用`

> Relation Extraction Using Large Language Models: A Case Study on Acupuncture Point Locations

# 摘要

> 针灸疗效，穴位定位是关键。GPT等大型语言模型的卓越语言理解能力，为我们从文本中提取穴位位置信息提供了新机遇。本研究对比了GPT与传统深度学习模型（如LSTM和BioBERT）在提取穴位位置关系上的表现，并探讨了预训练与微调对GPT性能的影响。我们以世界卫生组织西太区标准针灸穴位为语料库，标注了361个穴位间的3174种关系。通过微平均精确匹配精确度、召回率和F1分数等指标评估，微调后的GPT-3.5在各类关系识别上均表现最佳，F1分数高达0.92。研究表明，GPT等LLM在提取穴位信息方面效果显著，有助于精确构建针灸知识模型，推动针灸培训和实践中的标准应用。同时，这一发现也为传统与补充医学的信息应用提供了新思路，展现了LLM在自然语言处理领域的广阔前景。

> In acupuncture therapy, the accurate location of acupoints is essential for its effectiveness. The advanced language understanding capabilities of large language models (LLMs) like Generative Pre-trained Transformers (GPT) present a significant opportunity for extracting relations related to acupoint locations from textual knowledge sources. This study aims to compare the performance of GPT with traditional deep learning models (Long Short-Term Memory (LSTM) and Bidirectional Encoder Representations from Transformers for Biomedical Text Mining (BioBERT)) in extracting acupoint-related location relations and assess the impact of pretraining and fine-tuning on GPT's performance. We utilized the World Health Organization Standard Acupuncture Point Locations in the Western Pacific Region (WHO Standard) as our corpus, which consists of descriptions of 361 acupoints. Five types of relations ('direction_of,' 'distance_of,' 'part_of,' 'near_acupoint,' and 'located_near') (n= 3,174) between acupoints were annotated. Five models were compared: BioBERT, LSTM, pre-trained GPT-3.5, and fine-tuned GPT-3.5, as well as pre-trained GPT-4. Performance metrics included micro-average exact match precision, recall, and F1 scores. Our results demonstrate that fine-tuned GPT-3.5 consistently outperformed other models in F1 scores across all relation types. Overall, it achieved the highest micro-average F1 score of 0.92. This study underscores the effectiveness of LLMs like GPT in extracting relations related to acupoint locations, with implications for accurately modeling acupuncture knowledge and promoting standard implementation in acupuncture training and practice. The findings also contribute to advancing informatics applications in traditional and complementary medicine, showcasing the potential of LLMs in natural language processing.

[Arxiv](https://arxiv.org/abs/2404.05415)