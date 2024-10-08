# DiDOTS：借助大型语言模型的力量，破解转录语音中痴呆症的迷雾

发布时间：2024年10月05日

`LLM应用` `隐私保护`

> DiDOTS: Knowledge Distillation from Large-Language-Models for Dementia Obfuscation in Transcribed Speech

# 摘要

> 痴呆症，这一影响全球数千万人的神经认知障碍，预计到2050年病例将激增三倍。令人担忧的是，最新的痴呆症分类技术进步，使得从语音转录中推断患者敏感状况成为可能，严重威胁患者隐私。现有的文本混淆方法从未涉足痴呆症领域，且依赖于难以获取的大型标注数据集。为此，我们借助多样化提示设计（零样本、少样本和基于知识）的大型语言模型（LLMs），首次尝试在语音转录中混淆痴呆症信息，填补了研究空白。评估结果显示，LLMs在痴呆症混淆方面表现卓越，但庞大的参数规模使其难以训练、存储和共享，且易受幻觉、拒绝和矛盾等效应影响。为解决这些问题，我们创新性地提出了DiDOTS方法，通过教师-学生范式和参数高效微调，从LLMs中提炼知识。DiDOTS的参数数量仅为教师LLM的十分之一，微调所需参数更是减少了千分之一。评估结果表明，DiDOTS不仅继承了LLMs的优异性能，还在两个数据集上的隐私保护性能分别提升了1.3倍和2.2倍，且在保持实用性方面超越了最先进的释义模型。

> Dementia is a sensitive neurocognitive disorder affecting tens of millions of people worldwide and its cases are expected to triple by 2050. Alarmingly, recent advancements in dementia classification make it possible for adversaries to violate affected individuals' privacy and infer their sensitive condition from speech transcriptions. Existing obfuscation methods in text have never been applied for dementia and depend on the availability of large labeled datasets which are challenging to collect for sensitive medical attributes. In this work, we bridge this research gap and tackle the above issues by leveraging Large-Language-Models (LLMs) with diverse prompt designs (zero-shot, few-shot, and knowledge-based) to obfuscate dementia in speech transcripts. Our evaluation shows that LLMs are more effective dementia obfuscators compared to competing methods. However, they have billions of parameters which renders them hard to train, store and share, and they are also fragile suffering from hallucination, refusal and contradiction effects among others. To further mitigate these, we propose a novel method, DiDOTS. DiDOTS distills knowledge from LLMs using a teacher-student paradigm and parameter-efficient fine-tuning. DiDOTS has one order of magnitude fewer parameters compared to its teacher LLM and can be fine-tuned using three orders of magnitude less parameters compared to full fine-tuning. Our evaluation shows that compared to prior work DiDOTS retains the performance of LLMs achieving 1.3x and 2.2x improvement in privacy performance on two datasets, while humans rate it as better in preserving utility even when compared to state-of-the-art paraphrasing models.

[Arxiv](https://arxiv.org/abs/2410.04188)