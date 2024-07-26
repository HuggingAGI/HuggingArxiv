# GPT-4o 融合数据与知识，成为预测肺癌淋巴结转移的机器学习模型的得力解释者。

发布时间：2024年07月25日

`LLM应用` `机器学习`

> The Power of Combining Data and Knowledge: GPT-4o is an Effective Interpreter of Machine Learning Models in Predicting Lymph Node Metastasis of Lung Cancer

# 摘要

> 淋巴结转移（LNM）对肺癌患者的初始治疗至关重要，但术前准确诊断LNM仍具挑战。大型语言模型（LLMs）因出色的文本生成能力而备受瞩目。本文提出一种集成方法，融合LLMs的医学知识与机器学习模型的潜在模式，以提升LNM预测准确性。我们首先构建了基于患者数据的机器学习模型，并设计提示模板，整合患者数据与模型预测概率。接着，利用OpenAI的GPT-4o，根据患者数据估算LNM风险，并结合机器学习输出进行调整。最终，通过集成GPT-4o的三个输出，得出最终预测结果。实验显示，我们的方法在LNM预测中AUC值达0.765，AP值为0.415，显著优于传统机器学习模型。这表明，LLMs能有效结合医学知识与预测概率，实现更精准的LNM预测，为临床风险预测开辟新途径。

> Lymph node metastasis (LNM) is a crucial factor in determining the initial treatment for patients with lung cancer, yet accurate preoperative diagnosis of LNM remains challenging. Recently, large language models (LLMs) have garnered significant attention due to their remarkable text generation capabilities. Leveraging the extensive medical knowledge learned from vast corpora, LLMs can estimate probabilities for clinical problems, though their performance has historically been inferior to data-driven machine learning models. In this paper, we propose a novel ensemble method that combines the medical knowledge acquired by LLMs with the latent patterns identified by machine learning models to enhance LNM prediction performance. Initially, we developed machine learning models using patient data. We then designed a prompt template to integrate the patient data with the predicted probability from the machine learning model. Subsequently, we instructed GPT-4o, the most advanced LLM developed by OpenAI, to estimate the likelihood of LNM based on patient data and then adjust the estimate using the machine learning output. Finally, we collected three outputs from the GPT-4o using the same prompt and ensembled these results as the final prediction. Using the proposed method, our models achieved an AUC value of 0.765 and an AP value of 0.415 for LNM prediction, significantly improving predictive performance compared to baseline machine learning models. The experimental results indicate that GPT-4o can effectively leverage its medical knowledge and the probabilities predicted by machine learning models to achieve more accurate LNM predictions. These findings demonstrate that LLMs can perform well in clinical risk prediction tasks, offering a new paradigm for integrating medical knowledge and patient data in clinical predictions.

![GPT-4o 融合数据与知识，成为预测肺癌淋巴结转移的机器学习模型的得力解释者。](../../../paper_images/2407.17900/figure_1.pdf)

![GPT-4o 融合数据与知识，成为预测肺癌淋巴结转移的机器学习模型的得力解释者。](../../../paper_images/2407.17900/figure_2.pdf)

![GPT-4o 融合数据与知识，成为预测肺癌淋巴结转移的机器学习模型的得力解释者。](../../../paper_images/2407.17900/figure_3.pdf)

[Arxiv](https://arxiv.org/abs/2407.17900)