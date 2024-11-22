# 一种针对皮肤病检测与分类的多模态手段

发布时间：2024年11月21日

`LLM应用` `皮肤病诊断`

> A Multimodal Approach to The Detection and Classification of Skin Diseases

# 摘要

> 据 PBS 所述，近三分之一的美国人难以获取初级保健服务，另有 40%的人因担忧医疗费用而拖延就医。正因如此，即便许多疾病在皮肤上呈现出诸多身体症状，却仍未被诊断和治疗。伴随人工智能的崛起，自我诊断和疾病识别的改进愈发充满希望；不过，现有的方法受困于缺乏大规模患者数据库以及陈旧的研究方式，致使研究仅局限于少数疾病或模式。本研究借助图像和文本纳入了易于获取和使用的患者信息，用于对涵盖 26 种皮肤病类型的新数据集展开皮肤病分类，此数据集涵盖皮肤病图像（37K）及相关患者叙述。利用该数据集，为各类图像模型确立了基线，其表现优于现存方法。起初，Resnet-50 模型的准确率仅为 70%，但历经多种优化技术，准确率提升至 80%。此外，本研究针对序列分类大型语言模型（LLMs）提出了一种全新的微调策略——选项链，它在训练时把复杂的推理任务拆解为中间步骤，而非在推理阶段。凭借选项链和图像模型的初步疾病推荐，该方法在仅依据患病区域的图像以及患者对症状（诸如瘙痒或头晕）的描述的情况下，在诊断患者皮肤病方面达到了 91%的先进准确率。通过此项研究，皮肤病能够更早被诊断，临床医生能够与深度学习模型协作，给出更精准的诊断，提升生活质量并拯救生命。

> According to PBS, nearly one-third of Americans lack access to primary care services, and another forty percent delay going to avoid medical costs. As a result, many diseases are left undiagnosed and untreated, even if the disease shows many physical symptoms on the skin. With the rise of AI, self-diagnosis and improved disease recognition have become more promising than ever; in spite of that, existing methods suffer from a lack of large-scale patient databases and outdated methods of study, resulting in studies being limited to only a few diseases or modalities. This study incorporates readily available and easily accessible patient information via image and text for skin disease classification on a new dataset of 26 skin disease types that includes both skin disease images (37K) and associated patient narratives. Using this dataset, baselines for various image models were established that outperform existing methods. Initially, the Resnet-50 model was only able to achieve an accuracy of 70% but, after various optimization techniques, the accuracy was improved to 80%. In addition, this study proposes a novel fine-tuning strategy for sequence classification Large Language Models (LLMs), Chain of Options, which breaks down a complex reasoning task into intermediate steps at training time instead of inference. With Chain of Options and preliminary disease recommendations from the image model, this method achieves state of the art accuracy 91% in diagnosing patient skin disease given just an image of the afflicted area as well as a patient description of the symptoms (such as itchiness or dizziness). Through this research, an earlier diagnosis of skin diseases can occur, and clinicians can work with deep learning models to give a more accurate diagnosis, improving quality of life and saving lives.

[Arxiv](https://arxiv.org/abs/2411.13855)