# BiomedParse：一款生物医学领域的全能图像解析基础模型，实现万物一瞬解析。

发布时间：2024年05月21日

`LLM应用

理由：这篇论文介绍了一个名为BiomedParse的模型，该模型利用了大型语言模型（如GPT-4）来整合非结构化文本信息与生物医学对象本体论，以提升生物医学图像分析的性能。这表明该模型是在实际应用中利用LLM技术的一个实例，特别是在生物医学图像分析领域。因此，它属于LLM应用分类。` `生物医学` `图像分析`

> BiomedParse: a biomedical foundation model for image parsing of everything everywhere all at once

# 摘要

> 生物医学图像分析在细胞生物学、病理学、放射学等多个领域中至关重要。我们提出的BiomedParse模型，能够跨9种成像模式对82种对象进行联合分割、检测和识别。通过联合学习，BiomedParse不仅提升了各任务的准确性，还实现了创新应用，如通过文本提示自动分割图像中的所有相关对象，无需用户手动指定每个对象的边界框。我们利用了数据集附带的自然语言标签，通过GPT-4整合了非结构化文本信息与生物医学对象本体论。我们构建了一个包含六百万个图像、分割掩码和文本描述的大型数据集。在图像分割和对象检测任务中，BiomedParse均展现了卓越性能，尤其是在处理形状不规则的对象时。在对象识别任务中，BiomedParse能够一次性识别并标记图像中的所有生物医学对象。总之，BiomedParse作为一个全能工具，通过联合解决所有主要成像模式的分割、检测和识别问题，为高效的生物医学图像分析和发现奠定了基础。

> Biomedical image analysis is fundamental for biomedical discovery in cell biology, pathology, radiology, and many other biomedical domains. Holistic image analysis comprises interdependent subtasks such as segmentation, detection, and recognition of relevant objects. Here, we propose BiomedParse, a biomedical foundation model for imaging parsing that can jointly conduct segmentation, detection, and recognition for 82 object types across 9 imaging modalities. Through joint learning, we can improve accuracy for individual tasks and enable novel applications such as segmenting all relevant objects in an image through a text prompt, rather than requiring users to laboriously specify the bounding box for each object. We leveraged readily available natural-language labels or descriptions accompanying those datasets and use GPT-4 to harmonize the noisy, unstructured text information with established biomedical object ontologies. We created a large dataset comprising over six million triples of image, segmentation mask, and textual description. On image segmentation, we showed that BiomedParse is broadly applicable, outperforming state-of-the-art methods on 102,855 test image-mask-label triples across 9 imaging modalities (everything). On object detection, which aims to locate a specific object of interest, BiomedParse again attained state-of-the-art performance, especially on objects with irregular shapes (everywhere). On object recognition, which aims to identify all objects in a given image along with their semantic types, we showed that BiomedParse can simultaneously segment and label all biomedical objects in an image (all at once). In summary, BiomedParse is an all-in-one tool for biomedical image analysis by jointly solving segmentation, detection, and recognition for all major biomedical image modalities, paving the path for efficient and accurate image-based biomedical discovery.

[Arxiv](https://arxiv.org/abs/2405.12971)