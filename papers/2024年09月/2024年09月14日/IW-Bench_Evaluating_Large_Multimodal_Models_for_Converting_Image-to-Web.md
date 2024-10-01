# IW-Bench：评估大型多模态模型在图像转网页任务中的表现

发布时间：2024年09月14日

`LLM应用` `网页设计` `图像处理`

> IW-Bench: Evaluating Large Multimodal Models for Converting Image-to-Web

# 摘要

> 近期，大型多模态模型在图像理解方面取得了显著进展，但缺乏一个专门评估其图像到网页转换能力的强大基准。确保生成的网页元素完整性至关重要，这些元素包括可见和不可见类别。之前的评估方法（如BLEU）因网页中不可见元素的存在而显著易受影响。此外，测量网页布局信息，即元素间的位置关系，被先前研究忽视。为此，我们创建了IW-Bench基准，包含1200对不同难度的图像和网页代码。我们提出了元素准确性和布局准确性，分别通过解析DOM树和转换为公共子序列来评估。此外，设计了五跳多模态思维链提示，包含SoM提示注入、推断元素、布局、网页代码和反思五个步骤。通过广泛实验，我们揭示了现有大型多模态模型在图像到网页领域的性能和改进方向。

> Recently advancements in large multimodal models have led to significant strides in image comprehension capabilities. Despite these advancements, there is a lack of the robust benchmark specifically for assessing the Image-to-Web conversion proficiency of these large models. Primarily, it is essential to ensure the integrity of the web elements generated. These elements comprise visible and invisible categories. Previous evaluation methods (e.g., BLEU) are notably susceptible to significant alterations due to the presence of invisible elements in Web. Furthermore, it is crucial to measure the layout information of web pages, referring to the positional relationships between elements, which is overlooked by previous work. To address challenges, we have curated and aligned a benchmark of images and corresponding web codes (IW-Bench). Specifically, we propose the Element Accuracy, which tests the completeness of the elements by parsing the Document Object Model (DOM) tree. Layout Accuracy is also proposed to analyze the positional relationships of elements by converting DOM tree into a common subsequence. Besides, we design a five-hop multimodal Chain-of-Thought Prompting for better performance, which contains five hop: 1) SoM prompt injection. 2) Inferring Elements. 3) Inferring Layout. 4) Inferring Web code. 5) Reflection. Our benchmark comprises 1200 pairs of images and web codes with varying levels of difficulty. We have conducted extensive experiments on existing large multimodal models, offering insights into their performance and areas for improvement in image-to-web domain.

[Arxiv](https://arxiv.org/abs/2409.18980)