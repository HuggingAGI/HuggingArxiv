# RadFlag：一种针对医学视觉语言模型的黑箱幻觉检测手段

发布时间：2024年10月31日

`LLM应用` `医学图像`

> RadFlag: A Black-Box Hallucination Detection Method for Medical Vision Language Models

# 摘要

> 从医学图像生成准确的放射学报告，这在临床上重要却颇具挑战。当下的视觉语言模型（VLMs）虽有潜力，但易产生幻觉，可能危及患者护理。我们推出了 RadFlag，这一黑箱方法能提升放射学报告生成的准确性。该方法运用基于采样的标记技术，找出应剔除的幻觉生成内容。我们先是在不同温度下采样多个报告，再借助大型语言模型（LLM）识别样本中未获一致支持的表述，这意味着模型对这些表述的置信度低。通过校准阈值，我们将部分此类表述标记为可能的幻觉，它们要么应接受额外审查，要么被自动否决。我们的方法在识别单个幻觉句子和包含幻觉的报告时，精度颇高。作为一个仅需获取模型温度参数、易于使用的黑箱系统，RadFlag 与众多放射学报告生成模型兼容，有望全面提升自动化放射学报告的质量。

> Generating accurate radiology reports from medical images is a clinically important but challenging task. While current Vision Language Models (VLMs) show promise, they are prone to generating hallucinations, potentially compromising patient care. We introduce RadFlag, a black-box method to enhance the accuracy of radiology report generation. Our method uses a sampling-based flagging technique to find hallucinatory generations that should be removed. We first sample multiple reports at varying temperatures and then use a Large Language Model (LLM) to identify claims that are not consistently supported across samples, indicating that the model has low confidence in those claims. Using a calibrated threshold, we flag a fraction of these claims as likely hallucinations, which should undergo extra review or be automatically rejected. Our method achieves high precision when identifying both individual hallucinatory sentences and reports that contain hallucinations. As an easy-to-use, black-box system that only requires access to a model's temperature parameter, RadFlag is compatible with a wide range of radiology report generation models and has the potential to broadly improve the quality of automated radiology reporting.

[Arxiv](https://arxiv.org/abs/2411.00299)