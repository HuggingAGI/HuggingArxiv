# 多模态大型语言模型在处理不完整信息的胸部X光片分析中的应用价值

发布时间：2024年09月19日

`LLM应用` `放射学`

> Utility of Multimodal Large Language Models in Analyzing Chest X-ray with Incomplete Contextual Information

# 摘要

> 背景：尽管大型语言模型（LLM）在临床应用中日益增多，但面对不完整的放射报告时，其性能仍显不足。我们探索了多模态LLM（结合文本与图像）在提升胸部放射报告准确性与理解力方面的潜力，以期增强其在临床决策中的效用。目的：旨在检验LLM在处理不完整及多模态胸部放射报告时生成准确诊断的能力。方法：我们采用MIMIC-CXR数据库中的300对影像与报告，对比了三种LLM（OpenFlamingo、MedFlamingo、IDEFICS）在纯文本与多模态模式下的表现。通过逐步删除报告内容的20%、50%及80%，评估其影响。同时，引入胸部X光图像，分析其对模型性能的提升效果，并进行统计学比较。结果：纯文本模式下，各模型表现相近，其中OpenFlamingo在完整报告上略胜一筹（p<0.001）。然而，数据缺失显著削弱了所有模型的性能。值得关注的是，图像的加入大幅提升了MedFlamingo与IDEFICS的准确性（p<0.001），使其在不完整报告下也能与OpenFlamingo媲美甚至超越。结论：面对不完整放射数据，LLM可能表现不佳，但多模态LLM的引入显著增强了其可靠性，为临床决策提供了有力支持。关键词：大型语言模型；多模态；语义分析；胸部放射学；临床决策支持。

> Background: Large language models (LLMs) are gaining use in clinical settings, but their performance can suffer with incomplete radiology reports. We tested whether multimodal LLMs (using text and images) could improve accuracy and understanding in chest radiography reports, making them more effective for clinical decision support.
  Purpose: To assess the robustness of LLMs in generating accurate impressions from chest radiography reports using both incomplete data and multimodal data. Material and Methods: We used 300 radiology image-report pairs from the MIMIC-CXR database. Three LLMs (OpenFlamingo, MedFlamingo, IDEFICS) were tested in both text-only and multimodal formats. Impressions were first generated from the full text, then tested by removing 20%, 50%, and 80% of the text. The impact of adding images was evaluated using chest x-rays, and model performance was compared using three metrics with statistical analysis.
  Results: The text-only models (OpenFlamingo, MedFlamingo, IDEFICS) had similar performance (ROUGE-L: 0.39 vs. 0.21 vs. 0.21; F1RadGraph: 0.34 vs. 0.17 vs. 0.17; F1CheXbert: 0.53 vs. 0.40 vs. 0.40), with OpenFlamingo performing best on complete text (p<0.001). Performance declined with incomplete data across all models. However, adding images significantly boosted the performance of MedFlamingo and IDEFICS (p<0.001), equaling or surpassing OpenFlamingo, even with incomplete text. Conclusion: LLMs may produce low-quality outputs with incomplete radiology data, but multimodal LLMs can improve reliability and support clinical decision-making.
  Keywords: Large language model; multimodal; semantic analysis; Chest Radiography; Clinical Decision Support;

[Arxiv](https://arxiv.org/abs/2410.07111)