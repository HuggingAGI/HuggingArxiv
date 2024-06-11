# VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充

发布时间：2024年06月08日

`LLM应用

这篇论文介绍了一种基于大型语言模型（LLMs）的新方法——Volume Patch LLM（VP-LLM），用于条件3D补全任务。该方法通过将不完整的3D对象切割成小块并独立编码，然后结合文本提示输入LLM，以捕捉块间关系并赋予3D对象语义。这种方法在处理复杂指令和理解3D对象方面显示出优越的性能，超越了现有的基于扩散的3D补全模型。因此，这篇论文属于LLM应用类别，因为它展示了LLM在特定应用场景（即3D补全）中的实际应用和效果。` `3D建模` `人工智能`

> VP-LLM: Text-Driven 3D Volume Completion with Large Language Models through Patchification

# 摘要

> 近期研究在条件3D补全上多依赖CLIP或BERT处理文本，但这些方法难以应对复杂指令。相比之下，大型语言模型（LLMs）在多模态任务中展现出卓越潜力。基于此，我们开发了Volume Patch LLM（VP-LLM），通过单一前向传播实现条件3D补全。首先，我们将不完整的3D对象切割成独立编码的小块，然后将这些编码块与文本提示一同输入LLM，指导其捕捉块间关系并赋予3D对象语义。实验证明，VP-LLM在解读复杂指令和理解3D对象方面表现出色，其生成质量超越了基于扩散的顶尖3D补全模型。

> Recent conditional 3D completion works have mainly relied on CLIP or BERT to encode textual information, which cannot support complex instruction. Meanwhile, large language models (LLMs) have shown great potential in multi-modal understanding and generation tasks. Inspired by the recent advancements of LLM, we present Volume Patch LLM (VP-LLM), which leverages LLMs to perform conditional 3D completion in a single-forward pass. To integrate a 3D model into the LLM tokenization configuration, the incomplete 3D object is first divided into small patches that can be encoded independently. These encoded patches are then fed into an LLM along with the text prompt, instructing the LLM to capture the relations between these patches as well as injecting semantic meanings into the 3D object. Our results demonstrate a strong ability of LLMs to interpret complex text instructions and understand 3D objects, surpassing state-of-the-art diffusion-based 3D completion models in generation quality.

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x1.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x2.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x3.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x4.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/8855c5531c093275146f724acb952fba_airplane_gt.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/95240a3e33d607bd88803e631d9fa455_airplane_gt.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/5d0e79c02907bb8f5cde8c99e4b182f9_car_gt.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/a57e65f0c8f21ebc31780fdd33037c9d_car_gt.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/supp_iter.png)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x5.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x6.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x7.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x8.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x9.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x10.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x11.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x12.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x13.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x14.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x15.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x16.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x17.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x18.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x19.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x20.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x21.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x22.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x23.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x24.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x25.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x26.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x27.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x28.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x29.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x30.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x31.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x32.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x33.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x34.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x35.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x36.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x37.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x38.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x39.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x40.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x41.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x42.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x43.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x44.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x45.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x46.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x47.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x48.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x49.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x50.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x51.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x52.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x53.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x54.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x55.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x56.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x57.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x58.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x59.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x60.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x61.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x62.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x63.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x64.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x65.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x66.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x67.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x68.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x69.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x70.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x71.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x72.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x73.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x74.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x75.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x76.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x77.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x78.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x79.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x80.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x81.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x82.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x83.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x84.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x85.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x86.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x87.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x88.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x89.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x90.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x91.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x92.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x93.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x94.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x95.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x96.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x97.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x98.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x99.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x100.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x101.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x102.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x103.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x104.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x105.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x106.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x107.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x108.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x109.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x110.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x111.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x112.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x113.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x114.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x115.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x116.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x117.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x118.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x119.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x120.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x121.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x122.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x123.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x124.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x125.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x126.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x127.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x128.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x129.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x130.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x131.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x132.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x133.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x134.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x135.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x136.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x137.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x138.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x139.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x140.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x141.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x142.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x143.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x144.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x145.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x146.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x147.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x148.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x149.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x150.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x151.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x152.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x153.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x154.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x155.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x156.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x157.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x158.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x159.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x160.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x161.jpeg)

![VP-LLM：借助大型语言模型的补丁化技术，实现文本驱动的3D体积完美填充](../../../paper_images/2406.05543/x162.jpeg)

[Arxiv](https://arxiv.org/abs/2406.05543)