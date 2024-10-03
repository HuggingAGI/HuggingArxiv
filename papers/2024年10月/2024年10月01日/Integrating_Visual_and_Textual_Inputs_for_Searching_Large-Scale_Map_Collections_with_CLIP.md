# 结合视觉与文本信息，利用 CLIP 技术高效搜索海量地图资源

发布时间：2024年10月01日

`LLM应用` `图书馆` `文化遗产`

> Integrating Visual and Textual Inputs for Searching Large-Scale Map Collections with CLIP

# 摘要

> 尽管地图在数字收藏中占据重要地位，但当前的浏览方式仍局限于目录和元数据。本文探索了通过自然语言、视觉和多模态输入（如“带海怪的地图”或“更多灰度”）交互式搜索大规模地图收藏的可能性。我们以国会图书馆的562,842张地图为例，利用CLIP模型生成嵌入，并开发代码实现探索性搜索。通过与图书馆工作人员的合作，我们展示了搜索结果，并分析了其优缺点和潜力。此外，我们还创建了一个包含10,504对地图-标题的微调数据集，并提供了微调CLIP模型的架构。所有代码均以交互式Jupyter笔记本形式公开，便于重用。最后，我们探讨了这些方法在各类文化机构数字化和原生数字收藏中的应用前景与挑战。

> Despite the prevalence and historical importance of maps in digital collections, current methods of navigating and exploring map collections are largely restricted to catalog records and structured metadata. In this paper, we explore the potential for interactively searching large-scale map collections using natural language inputs ("maps with sea monsters"), visual inputs (i.e., reverse image search), and multimodal inputs (an example map + "more grayscale"). As a case study, we adopt 562,842 images of maps publicly accessible via the Library of Congress's API. To accomplish this, we use the mulitmodal Contrastive Language-Image Pre-training (CLIP) machine learning model to generate embeddings for these maps, and we develop code to implement exploratory search capabilities with these input strategies. We present results for example searches created in consultation with staff in the Library of Congress's Geography and Map Division and describe the strengths, weaknesses, and possibilities for these search queries. Moreover, we introduce a fine-tuning dataset of 10,504 map-caption pairs, along with an architecture for fine-tuning a CLIP model on this dataset. To facilitate re-use, we provide all of our code in documented, interactive Jupyter notebooks and place all code into the public domain. Lastly, we discuss the opportunities and challenges for applying these approaches across both digitized and born-digital collections held by galleries, libraries, archives, and museums.

[Arxiv](https://arxiv.org/abs/2410.01190)