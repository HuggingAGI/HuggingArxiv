# 你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究

发布时间：2024年04月22日

`LLM应用` `软件工程` `版权法`

> Does Your Neural Code Completion Model Use My Code? A Membership Inference Approach

# 摘要

> 近年来，基于深度学习的自动化代码补全模型研发取得了突破性进展。然而，普遍采用 GitHub 源代码进行模型训练的做法可能牵涉版权等法律和伦理问题。本文旨在探究这一问题，提出了一个关键问题：“你的神经代码补全模型是否使用了我的代码进行训练？”我们为此设计了一种名为 CodeMI 的成员推断方法，将其从分类任务适配到更具挑战性的代码补全领域。鉴于目标模型的黑盒特性，我们训练了多个影子模型来模拟其行为，并利用这些模型的输出来训练成员分类器。该分类器能够有效地判断特定代码样本是否曾被用于训练目标模型。我们在多种神经代码补全模型上验证了这一方法，包括基于 LSTM 的模型、CodeGPT、CodeGen 和 StarCoder。实验结果显示，LSTM 和 CodeGPT 模型存在成员信息泄露，我们的推断方法能够以较高准确率（分别为 0.842 和 0.730）检测到这一点。此外，我们发现对于当前的大型代码语言模型，如 CodeGen 和 StarCoder，其数据成员资格难以被识别，这表明还有提升空间。文章最后，我们还从模型记忆的角度对这些发现进行了阐释。

> Recent years have witnessed significant progress in developing deep learning-based models for automated code completion. Although using source code in GitHub has been a common practice for training deep-learning-based models for code completion, it may induce some legal and ethical issues such as copyright infringement. In this paper, we investigate the legal and ethical issues of current neural code completion models by answering the following question: Is my code used to train your neural code completion model? To this end, we tailor a membership inference approach (termed CodeMI) that was originally crafted for classification tasks to a more challenging task of code completion. In particular, since the target code completion models perform as opaque black boxes, preventing access to their training data and parameters, we opt to train multiple shadow models to mimic their behavior. The acquired posteriors from these shadow models are subsequently employed to train a membership classifier. Subsequently, the membership classifier can be effectively employed to deduce the membership status of a given code sample based on the output of a target code completion model. We comprehensively evaluate the effectiveness of this adapted approach across a diverse array of neural code completion models, (i.e., LSTM-based, CodeGPT, CodeGen, and StarCoder). Experimental results reveal that the LSTM-based and CodeGPT models suffer the membership leakage issue, which can be easily detected by our proposed membership inference approach with an accuracy of 0.842, and 0.730, respectively. Interestingly, our experiments also show that the data membership of current large language models of code, e.g., CodeGen and StarCoder, is difficult to detect, leaving amper space for further improvement. Finally, we also try to explain the findings from the perspective of model memorization.

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x1.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x2.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/figure2.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x3.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x4.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x5.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x6.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x7.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x8.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x9.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x10.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x11.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x12.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x13.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x14.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x15.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x16.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x17.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x18.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x19.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x20.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x21.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x22.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x23.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x24.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x25.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x26.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x27.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x28.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x29.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x30.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x31.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x32.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x33.png)

![你的神经代码补全模型是否侵犯了我的代码？采用成员推断技术进行探究](../../../paper_images/2404.14296/x34.png)

[Arxiv](https://arxiv.org/abs/2404.14296)