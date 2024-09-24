# 定制技能：利用多源网络数据，高效训练机器人烹饪技能

发布时间：2024年09月23日

`Agent` `机器人`

> Skills Made to Order: Efficient Acquisition of Robot Cooking Skills Guided by Multiple Forms of Internet Data

# 摘要

> 本研究探索了如何利用互联网数据源，从一组模板机器人行为中选择合适的行为来执行特定技能。由于互联网数据缺乏物理接触信息，如位置和力度，学习使用工具的复杂技能一直是个难题。以往的研究多依赖互联网数据和基础模型来生成机器人行为。我们提出，这些数据和模型或许更适合用于从基本行为中挑选，以完成复杂任务。我们尝试了三种选择方法：利用大型语言模型进行查询，通过预训练视频编码器比较机器人与人类的行为视频，以及使用光流编码器进行类似比较。结果表明，尽管缺乏视觉信息，LLM 在模板选择上表现出色；光流编码器在性能上远超数据量更大的视频编码器；不同类型的互联网数据间存在显著协同效应。通过整合这些数据，我们设计的选择器在涉及工具的16种烹饪技能测试中，成功率高达79%。

> This study explores the utility of various internet data sources to select among a set of template robot behaviors to perform skills. Learning contact-rich skills involving tool use from internet data sources has typically been challenging due to the lack of physical information such as contact existence, location, areas, and force in this data. Prior works have generally used internet data and foundation models trained on this data to generate low-level robot behavior. We hypothesize that these data and models may be better suited to selecting among a set of basic robot behaviors to perform these contact-rich skills. We explore three methods of template selection: querying large language models, comparing video of robot execution to retrieved human video using features from a pretrained video encoder common in prior work, and performing the same comparison using features from an optic flow encoder trained on internet data. Our results show that LLMs are surprisingly capable template selectors despite their lack of visual information, optical flow encoding significantly outperforms video encoders trained with an order of magnitude more data, and important synergies exist between various forms of internet data for template selection. By exploiting these synergies, we create a template selector using multiple forms of internet data that achieves a 79\% success rate on a set of 16 different cooking skills involving tool-use.

[Arxiv](https://arxiv.org/abs/2409.15172)