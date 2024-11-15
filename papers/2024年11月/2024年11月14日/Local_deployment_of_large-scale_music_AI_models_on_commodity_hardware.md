# 在商品硬件上进行大规模音乐 AI 模型的本地部署

发布时间：2024年11月14日

`LLM应用` `软件开发`

> Local deployment of large-scale music AI models on commodity hardware

# 摘要

> 我们推出了 MIDInfinite，这是一款能在本地普通硬件上借助大规模生成式 AI 模型生成符号音乐的网络应用。创建此演示时，我们把在 Lakh MIDI 数据集上预训练的大型语言模型——预期音乐转换器，移植到了机器学习编译（MLC）框架中。模型移植完成后，MLC 能支持在 C++、移动端和浏览器等多种运行环境中进行推理。我们认为 MLC 有望填补日益强大的音乐 AI 模型与音乐软件开发人员所熟悉技术之间的鸿沟。作为概念验证，我们构建了一个网络应用，用户能在浏览器中从零开始或依据提示生成源源不断的多乐器 MIDI 流。在普通硬件（一台 M3 Macbook Pro）上，我们的演示每秒能生成 51 个音符，72.9%的生成速度快于实时播放，若有 2 秒的前置缓冲，这一比例会提升至 86.3%。

> We present the MIDInfinite, a web application capable of generating symbolic music using a large-scale generative AI model locally on commodity hardware. Creating this demo involved porting the Anticipatory Music Transformer, a large language model (LLM) pre-trained on the Lakh MIDI dataset, to the Machine Learning Compilation (MLC) framework. Once the model is ported, MLC facilitates inference on a variety of runtimes including C++, mobile, and the browser. We envision that MLC has the potential to bridge the gap between the landscape of increasingly capable music AI models and technology more familiar to music software developers. As a proof of concept, we build a web application that allows users to generate endless streams of multi-instrumental MIDI in the browser, either from scratch or conditioned on a prompt. On commodity hardware (an M3 Macbook Pro), our demo can generate 51 notes per second, which is faster than real-time playback for 72.9% of generations, and increases to 86.3% with 2 seconds of upfront buffering.

[Arxiv](https://arxiv.org/abs/2411.09625)