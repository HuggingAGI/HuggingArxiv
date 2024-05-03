# 将自然语言转换为 Verilog 代码：我们利用大型语言模型和 ChatGPT，设计了一种递归脉冲神经网络。

发布时间：2024年05月02日

`LLM应用` `硬件设计` `神经形态计算`

> Natural Language to Verilog: Design of a Recurrent Spiking Neural Network using Large Language Models and ChatGPT

# 摘要

> 本研究探讨了利用大型语言模型（LLMs）自动化生成硬件描述语言代码的应用，旨在挖掘其在高效神经形态计算架构开发中的潜力。基于先前研究，我们利用OpenAI的ChatGPT4和自然语言指令，成功合成了一个可编程循环脉冲神经网络的寄存器传输级（RTL）Verilog模块，同时创建了测试平台以确保系统的正确性。该设计在三个案例研究中得到了验证：包括异或逻辑运算、鸢尾花分类和MNIST手写数字识别，准确率最高达96.6%。为了检验其合成和实现的可行性，该设计已在可编程门阵列上进行了原型化，并在SkyWater 130纳米技术平台上，采用开源的电子设计自动化流程实现了。此外，我们已将该设计提交至Tiny Tapeout 6芯片制造计划，以便未来进一步评估其在芯片上的性能表现。

> This paper investigates the use of Large Language Models (LLMs) for automating the generation of hardware description code, aiming to explore their potential in supporting and enhancing the development of efficient neuromorphic computing architectures. Building on our prior work, we employ OpenAI's ChatGPT4 and natural language prompts to synthesize a RTL Verilog module of a programmable recurrent spiking neural network, while also generating test benches to assess the system's correctness. The resultant design was validated in three case studies, the exclusive OR,the IRIS flower classification and the MNIST hand-written digit classification, achieving accuracies of up to 96.6%. To verify its synthesizability and implementability, the design was prototyped on a field-programmable gate array and implemented on SkyWater 130 nm technology by using an open-source electronic design automation flow. Additionally, we have submitted it to Tiny Tapeout 6 chip fabrication program to further evaluate the system on-chip performance in the future.

[Arxiv](https://arxiv.org/abs/2405.01419)