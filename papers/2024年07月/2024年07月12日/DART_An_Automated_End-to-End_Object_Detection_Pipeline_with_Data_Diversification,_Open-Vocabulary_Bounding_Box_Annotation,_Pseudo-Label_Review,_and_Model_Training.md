# DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。

发布时间：2024年07月12日

`LLM应用` `工业安全`

> DART: An Automated End-to-End Object Detection Pipeline with Data Diversification, Open-Vocabulary Bounding Box Annotation, Pseudo-Label Review, and Model Training

# 摘要

> 在工业应用中，如建筑工地的安全监控，快速准确地检测特定对象至关重要。传统方法依赖繁琐的手动标注和数据收集，难以适应多变的环境和新对象。为此，我们提出了DART，一个自动化端到端流程，简化对象检测的全流程，无需人工标注和大量数据收集，适应性强。DART通过主题驱动的图像生成模块（DreamBooth with SDXL）丰富数据，再由开放词汇对象检测（Grounding DINO）生成标注，经大型多模态模型（GPT-4o）审核后，用于训练实时检测器（YOLO）。我们在自建的建筑机械数据集Liebherr Product上应用DART，显著提升平均精度（AP）至0.832。DART的模块化设计确保了未来算法的升级、新类别的无缝集成及定制环境的适应性。相关代码和数据集已公开于https://github.com/chen-xin-94/DART。

> Swift and accurate detection of specified objects is crucial for many industrial applications, such as safety monitoring on construction sites. However, traditional approaches rely heavily on arduous manual annotation and data collection, which struggle to adapt to ever-changing environments and novel target objects. To address these limitations, this paper presents DART, an automated end-to-end pipeline designed to streamline the entire workflow of an object detection application from data collection to model deployment. DART eliminates the need for human labeling and extensive data collection while excelling in diverse scenarios. It employs a subject-driven image generation module (DreamBooth with SDXL) for data diversification, followed by an annotation stage where open-vocabulary object detection (Grounding DINO) generates bounding box annotations for both generated and original images. These pseudo-labels are then reviewed by a large multimodal model (GPT-4o) to guarantee credibility before serving as ground truth to train real-time object detectors (YOLO). We apply DART to a self-collected dataset of construction machines named Liebherr Product, which contains over 15K high-quality images across 23 categories. The current implementation of DART significantly increases average precision (AP) from 0.064 to 0.832. Furthermore, we adopt a modular design for DART to ensure easy exchangeability and extensibility. This allows for a smooth transition to more advanced algorithms in the future, seamless integration of new object categories without manual labeling, and adaptability to customized environments without extra data collection. The code and dataset are released at https://github.com/chen-xin-94/DART.

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/x1.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/x2.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/ann_gpt.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/ann_0.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/ann_1.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/ann_2.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/x3.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/n_img_per_category_stacked.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/ratio.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/gdino_score.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/confusion_matrix_gpt4o_human.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/confusion_matrix_human_human.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/confusion_matrix_0.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/confusion_matrix_1.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/yolo.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00245.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00265.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00268.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00269.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/cloudy_construction_site_0.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/underground_construction_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/right_side_3.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/multiple_machines_sunny_site_5.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/a00241.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/a09886.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/a09888.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/09884.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03917.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/05241.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/10116.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/05224.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00231.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/predictions_1.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/instance_distribution.png)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/predictions_2.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/01849.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/01852.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/01867.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/01870.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/rainy_construction_site_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/underground_construction_8.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/industrial_area_1.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/multiple_machines_harbor_2.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02752.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02758.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02759.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02807.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/desert_construction_2.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/industrial_site_1.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/rainy_construction_site_2.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/snowy_day_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02864.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02867.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02883.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/02943.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/foggy_morning_9.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/windy_day_1.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/riverbank_construction_9.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/multiple_machines_harbor_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03200.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03872.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03875.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03876.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/mountain_construction_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/urban_parking_lot_2.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/wind_farm_construction_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/railway_construction_5.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03000.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03002.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03003.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/03004.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/skyscraper_construction_5.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/sunny_construction_site_1.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/urban_demolition_0.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/large_scale_construction_3.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/image_grid_orig_aa.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/image_grid_orig_da.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/image_grid_gen_d.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00012.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00017.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00018.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00019.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/forest_construction_6.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/nighttime_construction_4.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/suburban_construction_1.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/multiple_machines_rural_area_4.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00012.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00017.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00018.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/00019.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/forest_construction_4.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/nighttime_construction_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/suburban_construction_7.jpg)

![DART 是一个全自动的物体检测流程，集成了数据多样化、开放词汇的边界框标注、伪标签审核以及模型训练。](../../../paper_images/2407.09174/multiple_machines_rural_area_4.jpg)

[Arxiv](https://arxiv.org/abs/2407.09174)