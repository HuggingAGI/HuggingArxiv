# 编号：诸如翻转漫画般的时间接地视频

发布时间：2024年11月15日

`LLM应用` `语言模型`

> Number it: Temporal Grounding Videos like Flipping Manga

# 摘要

> 视频大型语言模型（Vid-LLMs）在理解用于问答对话的视频内容上进展斐然。但它们在将这种视觉理解拓展到需要精准时间定位的任务，即视频时间接地（VTG）方面，却力不从心。为填补这一空缺，我们推出了数字提示（NumPro）这一创新方法，通过给每个视频帧添加独一无二的数字标识符，助力 Vid-LLMs 把视觉理解和时间接地关联起来。将视频视作一系列编了号的帧图像，NumPro 把 VTG 转变为一个直观的过程：依次翻阅漫画面板。这让 Vid-LLMs 能够“读取”事件时间线，精准地将视觉内容与相应的时间信息相连接。我们的实验表明，NumPro 在不增添额外计算成本的情况下，大幅提升了顶级 Vid-LLMs 的 VTG 性能。此外，在 NumPro 增强的数据集上进行微调，为 VTG 树立了新的前沿标杆，在瞬间检索的 mIoU 方面比之前的顶尖方法高出多达 6.9％，在亮点检测的 mAP 方面高出 8.5％。代码可在 https://github.com/yongliang-wu/NumPro 获取。

> Video Large Language Models (Vid-LLMs) have made remarkable advancements in comprehending video content for QA dialogue. However, they struggle to extend this visual understanding to tasks requiring precise temporal localization, known as Video Temporal Grounding (VTG). To address this gap, we introduce Number-Prompt (NumPro), a novel method that empowers Vid-LLMs to bridge visual comprehension with temporal grounding by adding unique numerical identifiers to each video frame. Treating a video as a sequence of numbered frame images, NumPro transforms VTG into an intuitive process: flipping through manga panels in sequence. This allows Vid-LLMs to "read" event timelines, accurately linking visual content with corresponding temporal information. Our experiments demonstrate that NumPro significantly boosts VTG performance of top-tier Vid-LLMs without additional computational cost. Furthermore, fine-tuning on a NumPro-enhanced dataset defines a new state-of-the-art for VTG, surpassing previous top-performing methods by up to 6.9\% in mIoU for moment retrieval and 8.5\% in mAP for highlight detection. The code will be available at https://github.com/yongliang-wu/NumPro.

[Arxiv](https://arxiv.org/abs/2411.10332)