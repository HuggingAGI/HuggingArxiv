# MedDiT：一种知识驱动型扩散变换器框架，专为虚拟模拟患者环境下的动态医学图像生成而设计。

发布时间：2024年08月22日

`LLM应用`

> MedDiT: A Knowledge-Controlled Diffusion Transformer Framework for Dynamic Medical Image Generation in Virtual Simulated Patient

# 摘要

> 医学教育依赖模拟患者（SPs）提供安全环境，让学生练习临床技能，包括医学图像分析。但招募合格SP的高成本和缺乏多样化医学影像数据集带来了挑战。为此，本文推出MedDiT，一种知识控制对话框架，能动态生成与模拟患者症状相符的医学图像，促进多样化诊断技能培训。MedDiT整合患者知识图谱（KGs），动态引导大型语言模型（LLMs），控制患者特征，减少医学对话中的幻觉。同时，引入调优的扩散变换器（DiT）模型，根据KG中患者属性生成医学图像。本文通过实际演示，展示MedDiT在多样化模拟患者案例中生成相应医学图像的能力，为学生提供丰富互动的学习体验，推动医学教育，为未来医疗专业人员打造沉浸式模拟平台。这项工作展示了在教育中应用LLM、KG和DiT的可行性，强调它们在解决基于模拟患者的医学教育挑战中的潜力。

> Medical education relies heavily on Simulated Patients (SPs) to provide a safe environment for students to practice clinical skills, including medical image analysis. However, the high cost of recruiting qualified SPs and the lack of diverse medical imaging datasets have presented significant challenges. To address these issues, this paper introduces MedDiT, a novel knowledge-controlled conversational framework that can dynamically generate plausible medical images aligned with simulated patient symptoms, enabling diverse diagnostic skill training. Specifically, MedDiT integrates various patient Knowledge Graphs (KGs), which describe the attributes and symptoms of patients, to dynamically prompt Large Language Models' (LLMs) behavior and control the patient characteristics, mitigating hallucination during medical conversation. Additionally, a well-tuned Diffusion Transformer (DiT) model is incorporated to generate medical images according to the specified patient attributes in the KG. In this paper, we present the capabilities of MedDiT through a practical demonstration, showcasing its ability to act in diverse simulated patient cases and generate the corresponding medical images. This can provide an abundant and interactive learning experience for students, advancing medical education by offering an immersive simulation platform for future healthcare professionals. The work sheds light on the feasibility of incorporating advanced technologies like LLM, KG, and DiT in education applications, highlighting their potential to address the challenges faced in simulated patient-based medical education.

[Arxiv](https://arxiv.org/abs/2408.12236)