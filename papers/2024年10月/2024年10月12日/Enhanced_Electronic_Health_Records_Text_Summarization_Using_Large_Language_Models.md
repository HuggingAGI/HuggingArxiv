# 借助大型语言模型，电子健康记录的文本摘要能力得以提升。

发布时间：2024年10月12日

`LLM应用` `电子健康记录`

> Enhanced Electronic Health Records Text Summarization Using Large Language Models

# 摘要

> 电子健康记录摘要系统的发展彻底改变了患者数据管理。以往的研究通过调整大型语言模型用于临床任务，使用多样化的数据集生成通用的EHR摘要，推动了这一领域的发展。然而，临床医生通常需要特定、集中的摘要以更快地获得洞察。本项目通过创建一个生成临床医生偏好的、集中摘要的系统，改进了EHR摘要，以提高患者护理的效率。所提出的系统利用Google Flan-T5模型生成基于临床医生指定主题的定制EHR摘要。该方法涉及在以Stanford Question Answering Dataset (SQuAD)格式化的EHR问答数据集上微调Flan-T5模型，这是一个包含问题和答案的大规模阅读理解数据集。微调使用了Hugging Face Transformers库中的Seq2SeqTrainer，并优化了超参数。关键评估指标显示了有希望的结果：系统达到了81.81%的精确匹配(EM)分数。ROUGE(面向召回的概要评估替补)指标显示了强劲的表现，ROUGE-1为96.03%，ROUGE-2为86.67%，ROUGE-L为96.10%。此外，双语评估替补(BLEU)分数为63%，反映了模型在生成摘要时的连贯性。通过增强LLM的EHR摘要，本项目支持医疗保健领域的数字化转型努力，简化了工作流程，并实现了更个性化的患者护理。

> The development of Electronic Health Records summarization systems has revolutionized patient data management. Previous research advanced this field by adapting Large Language Models for clinical tasks, using diverse datasets to generate general EHR summaries. However, clinicians often require specific, focused summaries for quicker insights. This project builds on prior work by creating a system that generates clinician-preferred, focused summaries, improving EHR summarization for more efficient patient care. The proposed system leverages the Google Flan-T5 model to generate tailored EHR summaries based on clinician-specified topics. The approach involved fine-tuning the Flan-T5 model on an EHR question-answering dataset formatted in the Stanford Question Answering Dataset (SQuAD) style, which is a large-scale reading comprehension dataset with questions and answers. Fine-tuning utilized the Seq2SeqTrainer from the Hugging Face Transformers library with optimized hyperparameters. Key evaluation metrics demonstrated promising results: the system achieved an Exact Match (EM) score of 81.81%. ROUGE (Recall-Oriented Understudy for Gisting Evaluation) metrics showed strong performance, with ROUGE-1 at 96.03%, ROUGE-2 at 86.67%, and ROUGE-L at 96.10%. Additionally, the Bilingual Evaluation Understudy (BLEU) score was 63%, reflecting the model's coherence in generating summaries. By enhancing EHR summarization through LLMs, this project supports digital transformation efforts in healthcare, streamlining workflows, and enabling more personalized patient care.

[Arxiv](https://arxiv.org/abs/2410.09628)