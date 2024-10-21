# 大规模对话系统中的手语指令生成

发布时间：2024年10月17日

`Agent` `辅助技术` `语言教育`

> Generating Signed Language Instructions in Large-Scale Dialogue Systems

# 摘要

> 我们推出了一款目标导向的对话AI系统，首次在全球多模态对话平台上实现了美国手语（ASL）指令的增强功能。通过触摸界面，系统接收用户输入，并利用检索技术和认知词汇翻译无缝生成ASL指令。核心设计包括一个由大型语言模型驱动的符号翻译模块，以及一个基于令牌的视频检索系统，用于从食谱和wikiHow指南中传递教学内容。开发过程中，我们深入社区，融合了聋人和听力障碍者社区及专家的见解。用户反馈验证了手语指令的有效性，评分与非手语版本系统相当。此外，系统在检索准确性和文本生成质量上表现优异，通过BERTScore等指标衡量。代码库和数据集已公开，网址为https://github.com/Merterm/signed-dialogue，手语指令视频检索系统演示可在https://huggingface.co/spaces/merterm/signed-instructions获取。

> We introduce a goal-oriented conversational AI system enhanced with American Sign Language (ASL) instructions, presenting the first implementation of such a system on a worldwide multimodal conversational AI platform. Accessible through a touch-based interface, our system receives input from users and seamlessly generates ASL instructions by leveraging retrieval methods and cognitively based gloss translations. Central to our design is a sign translation module powered by Large Language Models, alongside a token-based video retrieval system for delivering instructional content from recipes and wikiHow guides. Our development process is deeply rooted in a commitment to community engagement, incorporating insights from the Deaf and Hard-of-Hearing community, as well as experts in cognitive and ASL learning sciences. The effectiveness of our signing instructions is validated by user feedback, achieving ratings on par with those of the system in its non-signing variant. Additionally, our system demonstrates exceptional performance in retrieval accuracy and text-generation quality, measured by metrics such as BERTScore. We have made our codebase and datasets publicly accessible at https://github.com/Merterm/signed-dialogue, and a demo of our signed instruction video retrieval system is available at https://huggingface.co/spaces/merterm/signed-instructions.

[Arxiv](https://arxiv.org/abs/2410.14026)