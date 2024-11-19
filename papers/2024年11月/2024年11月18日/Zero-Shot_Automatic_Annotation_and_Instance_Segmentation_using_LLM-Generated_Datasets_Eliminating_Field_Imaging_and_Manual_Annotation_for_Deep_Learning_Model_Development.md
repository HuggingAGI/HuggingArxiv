# 利用 LLM 生成的数据集实现零样本自动标注与实例分割：消除深度学习模型开发中的实地成像和人工标注

发布时间：2024年11月18日

`LLM应用`

> Zero-Shot Automatic Annotation and Instance Segmentation using LLM-Generated Datasets: Eliminating Field Imaging and Manual Annotation for Deep Learning Model Development

# 摘要

> 当下，在各种应用（比如农业）中，基于深度学习的实例分割大多通过一个劳动密集型流程来实现，这一流程需要借助精密传感器进行大量实地数据采集，之后还要对图像进行细致的人工标注，给研究人员和相关组织带来了巨大的后勤与财务难题。而且，这一流程还拖慢了模型的开发与训练进程。在本研究里，我们给出了一种针对商业果园中苹果的基于深度学习的实例分割新办法，无需劳动密集型的实地数据采集和人工标注。借助大型语言模型（LLM），我们合成生成了果园图像，并运用与YOLO11基础模型集成的Segment Anything Model（SAM）对其自动标注。此方法大大降低了对物理传感器和人工数据处理的依赖，在“农业AI”领域取得重大突破。合成的、自动标注的数据集被用于训练苹果实例分割的YOLO11模型，而后在真实的果园图像上进行验证。结果显示，自动生成的标注达成了 0.9513 的 Dice 系数和 0.9303 的 IoU，证实了掩码标注的准确性和重合度。仅在这些带有自动标注的合成数据集上训练的所有 YOLO11 配置，都能精准识别和描绘苹果，凸显了该方法的有效性。具体来说，YOLO11m-seg 配置在从商业果园采集的测试图像上实现了 0.902 的掩码精度和 0.833 的掩码 mAP@50。另外，YOLO11l-seg 配置在对 40 个 LLM 生成的图像进行验证时，表现优于其他模型，实现了最高的掩码精度和 mAP@50 指标。
  关键词：YOLO，SAM，SAMv2，YOLO11，YOLOv11，Segment Anything，YOLO-SAM

> Currently, deep learning-based instance segmentation for various applications (e.g., Agriculture) is predominantly performed using a labor-intensive process involving extensive field data collection using sophisticated sensors, followed by careful manual annotation of images, presenting significant logistical and financial challenges to researchers and organizations. The process also slows down the model development and training process. In this study, we presented a novel method for deep learning-based instance segmentation of apples in commercial orchards that eliminates the need for labor-intensive field data collection and manual annotation. Utilizing a Large Language Model (LLM), we synthetically generated orchard images and automatically annotated them using the Segment Anything Model (SAM) integrated with a YOLO11 base model. This method significantly reduces reliance on physical sensors and manual data processing, presenting a major advancement in "Agricultural AI". The synthetic, auto-annotated dataset was used to train the YOLO11 model for Apple instance segmentation, which was then validated on real orchard images. The results showed that the automatically generated annotations achieved a Dice Coefficient of 0.9513 and an IoU of 0.9303, validating the accuracy and overlap of the mask annotations. All YOLO11 configurations, trained solely on these synthetic datasets with automated annotations, accurately recognized and delineated apples, highlighting the method's efficacy. Specifically, the YOLO11m-seg configuration achieved a mask precision of 0.902 and a mask mAP@50 of 0.833 on test images collected from a commercial orchard. Additionally, the YOLO11l-seg configuration outperformed other models in validation on 40 LLM-generated images, achieving the highest mask precision and mAP@50 metrics.
  Keywords: YOLO, SAM, SAMv2, YOLO11, YOLOv11, Segment Anything, YOLO-SAM

[Arxiv](https://arxiv.org/abs/2411.11285)