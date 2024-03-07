# [VIXEN——一款专为图像差异描述而设计的视觉文本比较网络，能够精准捕捉并用语言表达图像间的细微差异。](https://arxiv.org/abs/2402.19119)

发布时间：2024年02月29日

`LLM应用`

> VIXEN: Visual Text Comparison Network for Image Difference Captioning

> 我们呈现了创新技术 VIXEN，它能凝练地以文本方式描绘两幅图像间的视觉差异，从而揭示潜在的内容篡改行为。我们的新型网络巧妙地将成对图像特征线性映射至预训练的大规模语言模型的软提示中。面对当前 IDC 数据集中训练样本不足且篡改类型的多样性匮乏的问题，我们利用 prompt-to-prompt 编辑框架下新近生成的 InstructPix2Pix 合成篡改图像进行训练，并借助 GPT-3 生产的变化摘要进一步丰富数据集。实验证明，VIXEN 可以为各种图像内容和编辑类型生成领先业界、通俗易懂的差异描述文字，有望成为抵制通过篡改图像内容散布虚假信息的有效工具。相关代码与数据已发布在 http://github.com/alexblck/vixen 。

> We present VIXEN - a technique that succinctly summarizes in text the visual differences between a pair of images in order to highlight any content manipulation present. Our proposed network linearly maps image features in a pairwise manner, constructing a soft prompt for a pretrained large language model. We address the challenge of low volume of training data and lack of manipulation variety in existing image difference captioning (IDC) datasets by training on synthetically manipulated images from the recent InstructPix2Pix dataset generated via prompt-to-prompt editing framework. We augment this dataset with change summaries produced via GPT-3. We show that VIXEN produces state-of-the-art, comprehensible difference captions for diverse image contents and edit types, offering a potential mitigation against misinformation disseminated via manipulated image content. Code and data are available at http://github.com/alexblck/vixen