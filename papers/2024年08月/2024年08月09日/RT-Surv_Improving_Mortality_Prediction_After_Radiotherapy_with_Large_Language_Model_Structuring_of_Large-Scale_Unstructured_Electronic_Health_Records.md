# RT-Surv 利用大型语言模型，将大规模非结构化电子健康记录结构化，从而提升放射治疗后死亡率预测的准确性。

发布时间：2024年08月09日

`LLM应用` `人工智能`

> RT-Surv: Improving Mortality Prediction After Radiotherapy with Large Language Model Structuring of Large-Scale Unstructured Electronic Health Records

# 摘要

> 在放射治疗中，精准选择患者是防止治疗无效的关键。传统生存预测模型因依赖结构化数据而常显不足。本研究探索了大型语言模型（LLM）在整合非结构化电子健康记录（EHR）数据方面的潜力，以提升生存预测的精确度。研究分析了延世癌症中心2013至2023年间34,276名患者的结构化与非结构化数据。通过单次学习，开源LLM成功结构化了非结构化EHR数据，其准确率高达87.5%，远超特定医学LLM的35.8%。大型LLM在提取临床相关特征方面表现更佳，如患者的一般状况和疾病范围，这些特征与生存率紧密相关。将这些LLM结构化的临床特征融入生存预测模型，显著提升了模型的准确性，深度学习模型的C指数从0.737跃升至0.820，同时增强了模型的临床解释性。研究表明，即便未经专门医学训练，通用领域LLM也能有效处理大规模非结构化EHR数据，大幅提升临床预测模型的准确性与可解释性。

> Accurate patient selection is critical in radiotherapy (RT) to prevent ineffective treatments. Traditional survival prediction models, relying on structured data, often lack precision. This study explores the potential of large language models (LLMs) to structure unstructured electronic health record (EHR) data, thereby improving survival prediction accuracy through comprehensive clinical information integration. Data from 34,276 patients treated with RT at Yonsei Cancer Center between 2013 and 2023 were analyzed, encompassing both structured and unstructured data. An open-source LLM was used to structure the unstructured EHR data via single-shot learning, with its performance compared against a domain-specific medical LLM and a smaller variant. Survival prediction models were developed using statistical, machine learning, and deep learning approaches, incorporating both structured and LLM-structured data. Clinical experts evaluated the accuracy of the LLM-structured data. The open-source LLM achieved 87.5% accuracy in structuring unstructured EHR data without additional training, significantly outperforming the domain-specific medical LLM, which reached only 35.8% accuracy. Larger LLMs were more effective, particularly in extracting clinically relevant features like general condition and disease extent, which closely correlated with patient survival. Incorporating LLM-structured clinical features into survival prediction models significantly improved accuracy, with the C-index of deep learning models increasing from 0.737 to 0.820. These models also became more interpretable by emphasizing clinically significant factors. This study shows that general-domain LLMs, even without specific medical training, can effectively structure large-scale unstructured EHR data, substantially enhancing the accuracy and interpretability of clinical predictive models.

[Arxiv](https://arxiv.org/abs/2408.05074)