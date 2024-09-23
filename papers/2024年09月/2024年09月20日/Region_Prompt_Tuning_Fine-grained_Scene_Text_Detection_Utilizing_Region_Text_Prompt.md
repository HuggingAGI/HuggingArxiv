# 区域提示调优：通过区域文本提示实现精细场景文本检测

发布时间：2024年09月20日

`LLM应用` `计算机视觉` `文本检测`

> Region Prompt Tuning: Fine-grained Scene Text Detection Utilizing Region Text Prompt

# 摘要

> 近期，提示调优技术成功将如 CLIP 这样的大规模模型应用于场景文本检测等下游任务。然而，传统文本提示往往聚焦全局特征，忽视细粒度细节，导致检测中细粒度文本被忽略。为此，我们提出区域提示调优 (RPT) 方法，通过区域文本提示关注细粒度特征。RPT 将文本分解为单个字符，视觉特征图分割为区域视觉令牌，建立字符与令牌的一对一关系，确保字符匹配令牌的局部特征，避免细节遗漏。我们引入共享位置嵌入和双向距离损失，确保字符与目标文本对齐。此外，在编码前后进行字符-令牌交互，细化细粒度信息。最终，结合图像-文本过程的通用分数图与字符-令牌匹配的区域分数图，生成平衡全局与局部特征的分数图，输入 DBNet 进行文本检测。实验证明，RPT 在 ICDAR2015、TotalText 和 CTW1500 等基准上表现优异，显著提升了场景文本检测的准确性。

> Recent advancements in prompt tuning have successfully adapted large-scale models like Contrastive Language-Image Pre-trained (CLIP) for downstream tasks such as scene text detection. Typically, text prompt complements the text encoder's input, focusing on global features while neglecting fine-grained details, leading to fine-grained text being ignored in task of scene text detection. In this paper, we propose the region prompt tuning (RPT) method for fine-grained scene text detection, where region text prompt proposed would help focus on fine-grained features. Region prompt tuning method decomposes region text prompt into individual characters and splits visual feature map into region visual tokens, creating a one-to-one correspondence between characters and tokens. This allows a character matches the local features of a token, thereby avoiding the omission of detailed features and fine-grained text. To achieve this, we introduce a sharing position embedding to link each character with its corresponding token and employ a bidirectional distance loss to align each region text prompt character with the target ``text''. To refine the information at fine-grained level, we implement character-token level interactions before and after encoding. Our proposed method combines a general score map from the image-text process with a region score map derived from character-token matching, producing a final score map that could balance the global and local features and be fed into DBNet to detect the text. Experiments on benchmarks like ICDAR2015, TotalText, and CTW1500 demonstrate RPT impressive performance, underscoring its effectiveness for scene text detection.

[Arxiv](https://arxiv.org/abs/2409.13576)