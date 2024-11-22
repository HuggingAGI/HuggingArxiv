# 朝着富含上下文的自动化生物多样性评估迈进：从相机陷阱数据中获取由人工智能驱动的洞察

发布时间：2024年11月21日

`RAG` `野生动物保护`

> Towards Context-Rich Automated Biodiversity Assessments: Deriving AI-Powered Insights from Camera Trap Data

# 摘要

> 相机陷阱为生态研究带来了极大的新机遇，然而当下的自动化图像分析方法通常缺少能支撑起有效保护成果的丰富背景信息。在此，我们给出一种综合手段，把基于深度学习的视觉和语言模型加以融合，借助相机陷阱的数据来优化生态报告。我们引入了一个两阶段系统：YOLOv10 - X 用于在图像中对物种（哺乳动物和鸟类）进行定位和分类，Phi - 3.5 - vision - instruct 模型用于读取 YOLOv10 - X 绑定框标签以识别物种，克服了其在图像中难以对某些对象分类的局限。另外，Phi - 3.5 能检测更广泛的变量，比如植被类型和一天中的时段，为 YOLO 的物种检测输出增添了丰富的生态和环境背景。当两者结合时，模型的自然语言系统会处理这一输出以回答复杂的问题，并且运用检索增强生成（RAG）来借助外部信息（比如物种重量和 IUCN 状态，这些是无法通过直接视觉分析获取的信息）来丰富回应。这些信息被用于自动生成结构化报告，为生物多样性的利益相关方提供诸如物种丰度、分布、动物行为和栖息地选择等方面更深入的见解。我们的方法提供了背景丰富的描述，有助于野生动物管理决策。通过提供丰富的背景信息，我们的方法不但减少了人工工作量，还为保护工作中的及时决策提供了支持，有可能将工作模式从被动管理转变为主动管理。

> Camera traps offer enormous new opportunities in ecological studies, but current automated image analysis methods often lack the contextual richness needed to support impactful conservation outcomes. Here we present an integrated approach that combines deep learning-based vision and language models to improve ecological reporting using data from camera traps. We introduce a two-stage system: YOLOv10-X to localise and classify species (mammals and birds) within images, and a Phi-3.5-vision-instruct model to read YOLOv10-X binding box labels to identify species, overcoming its limitation with hard to classify objects in images. Additionally, Phi-3.5 detects broader variables, such as vegetation type, and time of day, providing rich ecological and environmental context to YOLO's species detection output. When combined, this output is processed by the model's natural language system to answer complex queries, and retrieval-augmented generation (RAG) is employed to enrich responses with external information, like species weight and IUCN status (information that cannot be obtained through direct visual analysis). This information is used to automatically generate structured reports, providing biodiversity stakeholders with deeper insights into, for example, species abundance, distribution, animal behaviour, and habitat selection. Our approach delivers contextually rich narratives that aid in wildlife management decisions. By providing contextually rich insights, our approach not only reduces manual effort but also supports timely decision-making in conservation, potentially shifting efforts from reactive to proactive management.

[Arxiv](https://arxiv.org/abs/2411.14219)