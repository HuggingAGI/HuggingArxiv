# Hespi：一款自动提取标本信息的智能流程

发布时间：2024年10月11日

`其他` `生物多样性` `计算机视觉`

> Hespi: A pipeline for automatically detecting information from hebarium specimen sheets

# 摘要

> 生物多样性数据在多个科学领域备受青睐，但依赖人工转录的瓶颈亟待突破。为此，我们研发了“Hespi”系统，利用计算机视觉技术从植物标本图像中高效提取机构标签数据。Hespi通过两个对象检测模型，精准识别并分类标签类型，并结合OCR和HTR技术提取文本。随后，通过权威数据库和大型语言模型进行双重校正，确保数据准确性。Hespi不仅在测试中表现出色，其模块化设计还允许用户根据自身需求定制模型，灵活应对各种数据提取挑战。

> Specimen associated biodiversity data are sought after for biological, environmental, climate, and conservation sciences. A rate shift is required for the extraction of data from specimen images to eliminate the bottleneck that the reliance on human-mediated transcription of these data represents. We applied advanced computer vision techniques to develop the `Hespi' (HErbarium Specimen sheet PIpeline), which extracts a pre-catalogue subset of collection data on the institutional labels on herbarium specimens from their digital images. The pipeline integrates two object detection models; the first detects bounding boxes around text-based labels and the second detects bounding boxes around text-based data fields on the primary institutional label. The pipeline classifies text-based institutional labels as printed, typed, handwritten, or a combination and applies Optical Character Recognition (OCR) and Handwritten Text Recognition (HTR) for data extraction. The recognized text is then corrected against authoritative databases of taxon names. The extracted text is also corrected with the aide of a multimodal Large Language Model (LLM). Hespi accurately detects and extracts text for test datasets including specimen sheet images from international herbaria. The components of the pipeline are modular and users can train their own models with their own data and use them in place of the models provided.

[Arxiv](https://arxiv.org/abs/2410.08740)