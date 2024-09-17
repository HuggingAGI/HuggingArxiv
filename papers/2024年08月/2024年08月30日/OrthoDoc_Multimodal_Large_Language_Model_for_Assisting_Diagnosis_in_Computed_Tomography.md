# OrthoDoc：一款专为计算机断层扫描诊断提供辅助的多模态大型语言模型

发布时间：2024年08月30日

`RAG` `图像处理`

> OrthoDoc: Multimodal Large Language Model for Assisting Diagnosis in Computed Tomography

# 摘要

> 多模态大型语言模型 (MLLM) 在图像处理领域取得了显著成就，其任务泛化和自由对话能力极大地促进了医疗诊断辅助，帮助患者更好地理解病情，增强医患信任。计算机断层扫描 (CT) 是一种广泛使用的非侵入性成像技术，用于捕捉患者内部状况。然而，过去研究中，CT 图像的复杂纹理特征使得算法难以准确解读，阻碍了通用 LLM 的诊断性能。为此，我们开发了 OrthoDoc，一种专为 CT 诊断设计的 MLLM。OrthoDoc 基于 120,000 张 CT 图像和诊断报告训练，并包含检索增强生成 (RAG) 模块，有效缓解模型幻觉。该模块结合了广泛的医学文献、教科书和解释性数据。因此，OrthoDoc 不仅能处理复杂 CT 图像，还能存储、理解和推理医学知识和语言。实验表明，OrthoDoc 优于 GPT-4 领导的商业模型，尤其在诊断常见骨科疾病如骨折、关节炎和肿瘤方面表现卓越。此外，OrthoDoc 在处理罕见和复杂病例时也展现出强大的泛化和稳定性。

> Multimodal large language models (MLLMs) have achieved significant success in the general field of image processing. Their emerging task generalization and freeform conversational capabilities can greatly facilitate medical diagnostic assistance, helping patients better understand their conditions and enhancing doctor-patient trust. Computed Tomography (CT) is a non-invasive imaging technique used to capture the internal mechanisms of a patient's condition and is widely utilized. However, in past research, the complex textural features of this imaging data have made accurate interpretation by algorithms challenging, impeding the performance of general LLMs in diagnostic assistance. To address this, we developed OrthoDoc, a MLLM designed for CT diagnostics. OrthoDoc is trained on 120,000 CT images and diagnostic reports and includes a Retrieval-Augmented Generation (RAG) module capable of effectively mitigating model hallucinations. This module is informed by extensive medical literature, textbooks, and explanatory data. Thus, OrthoDoc not only processes complex CT images but also stores, understands, and reasons over medical knowledge and language. In extensive experiments, OrthoDoc outperforms commercial models led by GPT-4, demonstrating superior diagnostic capabilities and accuracy. Specifically, OrthoDoc significantly surpasses existing models in the diagnosis of common orthopedic conditions such as fractures, arthritis, and tumors. Additionally, OrthoDoc exhibits robust generalization and stability when handling rare and complex cases.

[Arxiv](https://arxiv.org/abs/2409.09052)